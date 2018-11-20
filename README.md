# ios-googlemaps-view
Google Maps Current Location Viewer


## Features

* Full screen Google Maps view
* Detect current location
* Detect current place
* Get location info
* Link to Map navigation
* Link to website

## Components used

* Google Maps SDK for iOS (https://developers.google.com/maps/documentation/ios-sdk/current-place-tutorial)
  * Google Maps View (`GMSMapView`)
  * Google Maps Marker (`GMSMarker`)
  * Google Places Client (`GMSPlacesClient`)
  * iOS Location API (`CLLocationManager`, `CLLocation`)
  
  ## Screenshots
  
![](screenshots/ev-charge-map.png)

![](screenshots/ev-charge-info.png)


## Usage

* Download or clone the project 
* Install cocoa pods if not installed (See https://cocoapods.org/)
  *  `sudo gem install cocoapods`
* Execute in a command line
  * `pod install`
* Open the application project from the `.xcworkspace` file
  * `open ios-googlemaps-view.xcworkspace`
