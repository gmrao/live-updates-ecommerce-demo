# This repo is no longer updated. Please refer to [ionic-team/portals-ecommerce-demo](https://github.com/ionic-team/portals-ecommerce-demo/) instead. It includes live updates.

## live-updates-ecommerce-demo
E-commerce Demo App using Ionic Portals with Live Updates

This is an example application built in iOS and Android. Both are using the same web resources for their Portals.

## Portals Registration Key

To try our Ionic Portals demo, both iOS and Android applications require you to input a Portals registration key. You may get a key by going to [ionic.io/register-portals](https://ionic.io/register-portals). Follow the instructions below to add your key to each platform demo application.

## iOS
### Portals registration key

Get you registration key from [ionic.io/register-portals](https://ionic.io/register-portals), then uncomment the following line in `AppDelegate.swift` and replace `YOUR_KEY_HERE` with your key.

```Swift
// Register Portals
PortalManager.register("YOUR_KEY_HERE");
```

Build and run the iOS app

## Android
### Portals registration key

Get you registration key from [ionic.io/register-portals](https://ionic.io/register-portals), then uncomment the following line in `EcommerceApp.java` and replace `YOUR_KEY_HERE` with your key.

```Java
// Register Portals
PortalManager.register("YOUR_KEY_HERE");
```

Build and run the Android app

## Web
### Building

Before you build the iOS or Android source you will need to build the web resources.

#### Checkout and Profile Web App
- `cd ./web`
- `npm install`
- `npm run build`

#### Help Web App
- `cd ./web_help`
- `npm install`
- `npm run build`
