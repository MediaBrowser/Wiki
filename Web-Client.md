# Emby Web Client
Emby Web Client is main interface between you and your Emby Server, it is from this web interface you can edit all your server settings, share content with friends and view media content. All these features are documented navigation to your right. 

# Setup Guide
•	Emby Web Client is installed for you and configured with default settings during installation of your Emby Server to access it all you need to do it go to: http://{your server ip}:8086.
•	During first setup it is recommended that you sign up for Emby Connect to enable you to access your server from anywhere.  

# Server Management
Emby Web interface is an convenient place to manage all aspects of your Emby Server, be it library, users or Plugins it a one stop    for everything. Mangment features are only available to users who are tagged as server administers and can be accessed from to top    left hand menu and ”Manage Server”.   

# Media Player
From Emby Web Client you can both view media directly in your browser or you can remote control any active Emby Client. This includes Emby Theater for Windows or the Emby app for either Android or iOS. 

The app supports casting to Chromecast devices. To connect to your Chromecast device, simply click the cast icon in the top right corner of the app. You'll then be asked which device you'd like to connect to.
Once connected, any content you play will be sent to the Chromecast device. You're able to play individual files, entire folders, shuffle, instant mix, queue, and more. For more information, see Chromecast.

# Direct Play Media Formats
Direct Play highly dependent your browser codec support, please refer to your browser documentation for codec support. 

# Best Practices for Direct Play
Leave the app's streaming bitrate setting on the default value of Auto, if possible. The app will perform bandwidth tests with your Emby Server to determine the maximum playable bitrate.

If you are customizing the bitrate setting, then you will need to compare the bitrate of your files to the bitrate setting in the app. You can find the bitrate of a file by checking the media info in the web interface. If the bitrate of a file is higher than the setting in the app, transcoding will be required. Increasing the bitrate setting in the app can help reduce transcoding, but may impact playback performance if your network connection is not fast enough to handle it.
