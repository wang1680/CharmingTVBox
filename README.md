# Charming TV Box

A streaming media player based on Electron and Shaka-player.

# Regarding the current status of CharmingTVBox
CharmingTVBox was initially developed as a lightweight player for PC with a clean interface, primarily to support simple DASH and HLS playback. However, many users seemed to expect more capabilities from it. Due to limitations inherent in Electron and Chromium, it couldn’t meet demands such as cross-platform support across mobile and TV devices, or more advanced decoding capabilities.

Therefore, I shifted my focus to MPV and VLC as underlying engines and chose Flutter as the framework to build a new player. This new player supports DASH and HLS playback as before, but can also handle a wider variety of unusual media formats. In theory, it is designed to be cross-platform, but given limited resources, the initial release will likely support only macOS and Windows. Once the features stabilize, support for TV platforms and Android/iOS will be considered.

However, it is impossible to release on iOS App Store because the DASH decryption component completely violates Apple’s policies by bypassing the system’s native, regulated decryption channels.

The new player is named Charming Player. Progress is going well, it’s now in the final stages of development, and I look forward to sharing it with everyone soon.

