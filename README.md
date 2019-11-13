# Wandering with Google Maps

**Note that you will need to add an API key for the solution code to run**.

## Introduction
Building apps with Google Maps allows you to add features to your app such as satellite imagery, robust UI controls for maps, location tracking, and location markers. You can add value to the standard Google Maps by showing information from your own data set, such as the locations of well-known fishing or climbing areas. You can also create games where the player explores the physical world, like a treasure hunt or the recent trend of augmented reality games.
In this lesson, you will create a Google Maps app called Wander that displays customized maps and shows the user's location.

## What you should already know
Runtime permissions.
Kotlin
Creating, building, and running apps in Android Studio.

## What you'll learn
Obtain an API key.
Integrate a Google Map in your app.
Display different map types.
Style the Google Map.
Add markers to your map.
Enable the user to place a marker on a point of interest (POI).
Enable location tracking.

## What you'll do
Get an API key from the Google API Console and register the key to your app.
Create the Wander app, which has an embedded Google Map.
Add custom features to your app such as markers and styling.
Enable location tracking in your app.

## Obtain the API key
1. Open the debug version of the google_maps_api.xml file.
2. In the file, look for a comment with a long URL. The URL's parameters include specific information about your app.
3. Copy and paste the URL into a browser.
4. Follow the prompts to create a project in the Google API Console. Because of the parameters in the provided URL, the API Console knows to automatically enable the Google Maps Android API.
5. Create an API key and click Restrict Key to restrict the key's use to Android apps. The generated API key should start with AIza.
6. In the google_maps_api.xml file, paste the key into the google_maps_key string where it says YOUR_KEY_HERE.
