MobileMapStarter
================

A starting framework for mobile maps using Cordova/Phonegap.
A minimal but functional, standalone mobile app from which to build your own creations.

This app is designed for Phonegap/Cordova, therefore it is HTML, JavaScript, and CSS.

Components of this app:

* HTML/CSS/JS layout -- The app is ready to compile and run via Phonegap.

* config.xml -- The app is ready to upload to Phonegap Build. The included config.xml specifies permissions, icons and splash screens, and more in an easy-to-edit template.

* jQuery Mobile -- A mobile-style user interface theme. Includes jQuery which makes JavaScript useful.

* Leaflet -- Quick, pretty, easy tiled maps.

* File API and L.TileLayer caching system -- Cache Leaflet tiles to device storage for offline use.


COMPILING IT / TESTING IT
================

This ready-to-run app is designed for use with Phonegap/Cordova, particularly Phonegap Build. Simply upload to Phonegap Build and you'll get back a working phone app.

This code can also form the starting content of the _www_ folder in your Cordova/Phonegap application, and then compiled with Eclipse and XCode.

The HTML/JS will work in Google Chrome, if you enable file access:
    chrome.exe --allow-file-access
I don't recommend developing using file:// URLs, as the File API is still buggy even if you give the --allow-file-access-from-files flag. Instead, install a webserver on your machine and use http://localhost/ URLs.



WALKTHROUGH: EXPLAINING THE CODE & CUSTOMIZING YOUR APP
================

Start with index.js This includes basic settings such as default lat/lng/zoom and your Bing API key.

Check out config.xml to start personalizing your app: the name, author attribution, permissions, and so on.

Swap out splash screens and icons. See splash.png and icon.png, then the splash/ and icons/ folders.

Now start customizing HTML (index.html), CSS (index.css), and JavaScript code (index.js), and start swapping out icons and other graphics under the img/ folder.

Additional, possibly useful, utility functions are found in library.js


BUGS / TODO / WISHES
================

* Nothing, the app is perfect in every way.  ;)

