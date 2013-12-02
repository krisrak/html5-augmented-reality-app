html5-augmented-reality-app
===========================

Simple Augmented Reality App implemented using HTML5 and Cordova with Foursquare data overlay (and US cities overlay)

Uses Foursquare API to search for locations and plots the location on Google Maps.
Uses Cordova API to access device compass, accelerometer and geolocation.

Must be built using Intel XDK or use Phonegap build.

App developed during 2 day XDK hackathon at Intel.
Developed using Intel XDK tool - http://html5dev-software.intel.com

=

*_app must be tested using Intel XDK's App Preview or build app using Intel XDK._

=

###index_UScities.html###
Shows 12 US Cities in list view, map view and augmented reality mode. Uses Cordova APIs for accelerometer, compass and geolocation.

=

###index_UScities_xdkAR.html###
Shows 12 US Cities in list view, map view and augmented reality mode. Uses Cordova APIs for accelerometer, compass and geolocation. Uses intel.xdk JS bridge API to enable camera in background and overlays data in augmented reality mode. 

=

###index_foursquare.html###
Shows foursquare places data in list view, map view and augmented reality mode. Uses Cordova APIs for accelerometer, compass and geolocation.

*_requires you to sign up for foursquare developer account and add client id and client secret to the source code_

=

###index_foursquare_xdkAR.html###
Shows foursquare places data in list view, map view and augmented reality mode. Uses Cordova APIs for accelerometer, compass and geolocation. Uses intel.xdk JS bridge API to enable camera in background and overlays data in augmented reality mode. 

*_requires you to sign up for foursquare developer account and add client id and client secret to the source code_

=

__index.html = index_UScities.html__

=

Screenshots
=

###foursquare listView###
![alt tag](https://raw.github.com/krisrak/html5-augmented-reality-app/master/screenshots/foursquare_listView.png)  

-

###foursquare mapView###
![alt tag](https://raw.github.com/krisrak/html5-augmented-reality-app/master/screenshots/foursquare_mapView.png)
 
- 
   
###foursquare XDK AR mode###
![alt tag](https://raw.github.com/krisrak/html5-augmented-reality-app/master/screenshots/foursquare_xdkARmode.png)  

-

###US Cities AR mode###
![alt tag](https://raw.github.com/krisrak/html5-augmented-reality-app/master/screenshots/UScities_ARmode.png)

-
