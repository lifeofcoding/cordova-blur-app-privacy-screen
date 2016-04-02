# cordova-plugin-blurry-privacy-screen
Blurs app content when it goes into the background to prevent legibility of sensitive information.
(The snapshot in the app switcher will display the app blurred. [iOS only! Tested with iOS 8.1 and 9.2])

### To Install via Ionic
```ionic plugin add https://github.com/lifeofcoding/cordova-blur-app-privacy-screen.git --save```

### To Install via Cordova
```cordova plugin add https://github.com/lifeofcoding/cordova-blur-app-privacy-screen.git --save```

That is it! it will automatically take effect!

# Roadmap
* The ability to specify blur style in config.xml of your app
* Android support

_Initial release v0.0.1 Only support iOS because that is all I needed this plugin for, but I am putting the challenge out there for someone to help contribute Android support to the plugin! (Tip: Set `FLAG_SECURE` for android would be needed, and perhaps a transparent image with a blur effect on it can be used to overlay the app.)_
