Latest Version 
--------------
##### _Nov 21st, 2016_ - [v2.2.6](https://github.com/devtodev-analytics/unity-sdk/releases/latest)

Getting Started
---------------
Full description of the integration process of devtodev SDK and all the accessible features can be found on the page with [official devtodev documentation](https://www.devtodev.com/help/73).

Changelog
---------
See [releases](https://github.com/devtodev-analytics/unity-sdk/releases).

#### Version 2.2.4
* Android initialization in Awake method fixed.

#### Version 2.2.3
* Improved compatibility with iOS 10 and Android N

#### Version 2.2.2
* Android N support

#### Version 2.2.1
* WebGL fixes

#### Version 2.2
* Added new "Progression event". First of all, the event is used for the games with short (within one game session) locations, game levels. The event allows you to gather data on passing the locations and get statistics on parameters which vary during the the location passing.
* Work of ReplaceUserId method when one existing user is renamed to another existing user is fixed.
* [Android] Custom push icons setters was added.
* [Android] Possible crash caused by Google Play Services absence if push-notifications are used is fixed.

#### Version 2.1.1
* WACK serfitication was fixed

#### Version 2.1
* User profile feature is added. Here you can store properties about a specific user.
* New methods for managing preset and custom properties of user profile are added.
* Old methods: age, gender and cheater, are removed. These properties are moved to user profile.
* Initial referrer data tracking method is added
* Unity 4.6.5 Support added
 Attention! If you install SDKs versions (1.*) 2.0, 2.0.1 or 2.0.2, you have to delete them before integrate the latest version. To do that, delete following files and catalogues:
 For 1.*
 Assets/DevToDev/ (the folder)
 Assets/Plugins/Android/  (files android-suport-v4.jar, AndroidManifest.xml, devtodev.jar, devtodev_android_wrapper.jar, google-play-  services.jar)
 Assets/Plugins/iOS/ (files AccrualType.h, CustomEventParams.h, all DevToDev*.h, Gender.h, libdevtodev.a, ReceiptStatus.h, SocialNetwork.h, TimeStatus.h, TutorialState.h)
 Assets/Plugins/Metro/devtodev.dll
 For 2.0
 Assets/devtodev (the folder) 
 Assets/Plugins/DevToDevOSX.bundle
 After deleting, unpack devtodev.unitypackage version 2.1 and replace all the files. If you used an ​interface integration, you have to re-integrate SDK.

#### Version 2.0.2
* WebGL support added

#### Version 2.0.1
* Improved compatibility with the 5th version of Unity

#### Version 2.0
* Unified SDK for Unity! One SDK for all platforms.
