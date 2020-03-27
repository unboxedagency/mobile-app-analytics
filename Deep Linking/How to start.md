1. Update Firebase SDK where applicable (both for iOS & Android for native apps)

	SDK details: https://github.com/unboxedagency/mobile-app-analytics/blob/master/Firebase/FirebaseSDK(Pods)

	Official documentation
	
	- For iOS: https://firebase.google.com/docs/ios/setup
		
	- Full SDK doucmentation: https://github.com/firebase/firebase-ios-sdk
  
  	- For Android: https://firebase.google.com/docs/android/setup
  
    	- Full SDK doucmentation: https://github.com/firebase/firebase-android-sdk
    
    
2. Add support for Universal Links (iOS)

	- For iOS: https://developer.apple.com/library/archive/documentation/General/Conceptual/AppSearch/UniversalLinks.html#//apple_ref/doc/uid/TP40016308-CH12-SW2
	
	- Create an "apple-app-site-association" file that contains JSON data about the URLs that your app can handle. The file should be added on your domain's root or /.well-known/ directory (for example: https://www.istegelsin.com/apple-app-site-association or https://www.istegelsin.com/.well-known/apple-app-site-association)

3.  Add support App Links (Android)

	- Create intent filters in your manifest
	- Add code to your app’s activities to handle incoming links
	- Associate your app and your website with Digital Asset Links
	
	DETAILS: https://developer.android.com/studio/write/app-link-indexing
