# ionic2-google-maps-native
Google maps native in Ionic 2

### 1. Install the the latest version of the Ionic CLI:

`$ npm install -g ionic`

### 2. Install Cordova

`$ npm install -g cordova`

### 3. Clone this repository

`$ git clone https://github.com/mayrarodriguez1709/ionic2-google-maps-native`

### 4. Navigate to the ionic2-google-maps-native directory:

`$ cd ionic2-google-maps-native`

### 5. Install the dependencies

`$ npm install`

`$ ionic state restore`

### 6. In your console, add KEYS for ANDROID and IOS

`$ ionic plugin add cordova-plugin-googlemaps --variable API_KEY_FOR_ANDROID=”HERE_YOU_ANDROID_API_KEY” --variable API_KEY_FOR_IOS=”HERE_YOU_IOS_API_KEY”`

you can get one in https://developers.google.com/maps/

### 7. In your console again, add the cordova plugin 

`$ ionic plugin add cordova-plugin-geolocation`

### 8. Run your project!

`$ ionic run android $ ionic run ios`

and ¡Voilá!

Note: If you're using an emulator you have to install the GAPPS (Google apps) previously.
