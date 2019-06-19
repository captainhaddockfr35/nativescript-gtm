# Nativescript Google Tag Manager

[![npm version](https://badge.fury.io/js/nativescript-gtm.svg)](http://badge.fury.io/js/nativescript-gtm)

[![NPM](https://nodei.co/npm/nativescript-gtm.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/nativescript-gtm/)


Use Firebase + GTM into your Nativescript application

## (Optional) Prerequisites / Requirements

* Install the [nativescript-firebase plugin](https://github.com/eddyverbruggen/nativescript-plugin-firebase)
* Create a Google Tag Manager account

## Installation


```javascript
tns plugin add nativescript-gtm
```

## Usage 

### iOS
Create an iOS container if your Google Tag Manager account doesn't have one:
* Sign in to your Google Tag Manager account.
* Click *ADMIN* in the top navigation bar.
* On the *CONTAINER* column, click the drop-down menu and select *CREATE CONTAINER*.
* Enter a container name.
* Select iOS container.
* Select Firebase (iOS) SDK.
* Click CREATE.

Download your container:
* Sign in to your Google Tag Manager account.
* Select your iOS container.
* Click Versions in the top navigation bar.
* Click **Actions** > **Download** on the selected container version.
* The name of the downloaded file is the container ID with a .json extension.

Add the downloaded container to your project:
* Create the folder `App_Resources/iOS/container`
* Copy the downloaded file into this new folder (usually `PROJECT_ROOT/App_Resources/container/GTM-XXXXXX.json`).


### Android
* Sign in to your Google Tag Manager account.
* Select a mobile container.
* Click Versions in the top navigation bar.
* Click **Actions** > **Download** on the selected container version.
* Create the `App_Resources/Android/src/main/assets/containers` folder if it doesn't exist. Copy the downloaded container to the folder.

    
## License

Apache License Version 2.0, January 2004
