<h1 align="center">NotifyMe</h1>
<h4 align="center">A decentralised check-in system for meetings and events</h4>
<br />
<div align="center">
  <img width="180" height="180" src="https://github.com/notifyme-app/notifyme-app-android/raw/develop/app/src/main/app_icon-playstore.png" />
  <br />
  <br />
  <a href="https://play.google.com/store/apps/details?id=ch.ubique.notifyme">Download Android App</a>
  <br />
  <br />
  <a href="https://apps.apple.com/app/id1537859001">Download iOS App</a>
</div>

## Introduction

The app is a decentralised check-in system for meetings and events. Users can check in to a venue by scanning a QR Code. The check in is stored locally and encrypted. In case one of the visitors tests positive subsequent to a gathering, all other participants can be easily informed via the app. The app uses the [CrowdNotifier SDK](https://github.com/CrowdNotifier/crowdnotifier-sdk-android) based on the [CrowdNotifier White Paper](https://github.com/CrowdNotifier/documents) by Wouter Lueks (EPFL) et al. The app design, UX and implementation was done by [Ubique](https://ubique.ch/). More information can be found [here](https://notify-me.ch).

## Try it now!
1. Install the Android or iOS app. [Download Android App](https://play.google.com/store/apps/details?id=ch.ubique.notifyme) [Download iOS App](https://apps.apple.com/app/id1537859001)
2. Go to the [QR code generator page](https://qr-gen.notify-me.ch/) and create your own Entry and Trace QR codes.
3. Scan the QREntry with the app to check-in to your venue.
4. Check out in the app after some time.
5. Scan the QRtrace with any QR code reader and open the URL.
6. Enter the time range for which you want to warn people who were at your venue and upload the data.

## Work in Progress
The NotifyMe App system contains alpha-quality code only and is not yet complete. It has not yet been reviewed or audited for security and compatibility. We are both continuing the development and have started a security review. This project is truly open-source and we welcome any feedback on the code regarding both the implementation and security aspects.
This repository contains the open prototype Application, so please focus your feedback for this repository on implementation issues.

## Repositories
All code can be found in the following repositories:
* Android SDK: [crowdnotifier-sdk-android](https://github.com/CrowdNotifier/crowdnotifier-sdk-android)
* iOS SDK: [crowdnotifier-sdk-ios](https://github.com/CrowdNotifier/crowdnotifier-sdk-ios)
* Android Demo App: [notifyme-app-android](https://github.com/notifyme-app/notifyme-app-android)
* iOS Demo App: [notifyme-app-ios](https://github.com/notifyme-app/notifyme-app-ios)
* Backend SDK: [notifyme-sdk-backend](https://github.com/notifyme-app/notifyme-sdk-backend)
* Web Apps: [notifyme-webpages](https://github.com/notifyme-app/notifyme-webpages)



## Further Documentation
The full set of documents for CrowdNotifier is at https://github.com/CrowdNotifier/documents. Please refer to the technical documents and whitepapers for a description of the implementation.

## License
This project is licensed under the terms of the MPL 2 license. See the [LICENSE](LICENSE) file.
