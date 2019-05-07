ML Kit OCR (Bar Code & Text Recognition)
============
This repository contains the code for:
- [x] the ML Kit **Text Recognition** API
- [ ] the ML Kit **Barcode Scanning** API

Introduction
------------
With this project, you will be able to build an Android app that uses various features
of ML Kit to recognize text and identify bar code in images with your camera and pictures
from your mobile storage. You will learn how to use the built in on-device with ML Kit.

Pre-requisites
--------------
* A recent version of Android Studio (v3.0+)
* Android Studio Emulator or a physical Android device
* The sample code

Getting Started
---------------
1. What's ML Kit and why use it

> ML Kit is a mobile SDK that brings machine learning expertise to Android and iOS apps in a powerful yet easy-to-use package.
Furthermore, there's no need to have deep knowledge of neural networks or model optimization, whether you're new or experienced
in machine learning, you can easily implement the functionality you need in just a few lines of code.

2. How does it work

> This project is an Android app that can automatically recognize the contents of a barcode or a text from a provided image.
> For that your app will utilize:
> * the ML Kit **Barcode Scanning** API to scan and process barcodes without requiring an internet connection
> * the ML Kit **Text Recognition** API to detect text in image

3. Getting set up

> 1) Fork the project via `github`<br/>
> 2) Clone the project `git clone https://github.com/crendu/OCR_mlkit_BarCode-Text.git`<br/>
> 3) Import the project into Android Studio<br/>
> 4) Add the following dependencies:  (you may need to update some of them)<br/>
> &emsp; In the project file build.gradle:<br/>
> &emsp;&emsp; _buildscript {<br/>
> &emsp;&emsp;&emsp;&emsp; dependencies {<br/>
> &emsp;&emsp;&emsp;&emsp;&emsp;&emsp; classpath 'com.google.gms:google-services:4.2.0' // Add this line<br/>
> &emsp;&emsp;&emsp;&emsp; }<br/>
> &emsp;&emsp; }_<br/>
> 
> &emsp; In the app file build.gradle:<br/>
> &emsp;&emsp; _dependencies {<br/>
> &emsp;&emsp;&emsp;&emsp; // Add this lines<br/>
> &emsp;&emsp;&emsp;&emsp; implementation 'com.android.support:cardview-v7:28.0.0'<br/>
> &emsp;&emsp;&emsp;&emsp; implementation 'com.theartofdev.edmodo:android-image-cropper:2.7.+' // Image crop library<br/>
> &emsp;&emsp;&emsp;&emsp; implementation 'com.google.android.gms:play-services-vision:16.2.0' // Image to text google library<br/>
> &emsp;&emsp;&emsp;&emsp; implementation 'com.google.firebase:firebase-core:16.0.8' // Firebase library<br/>
> &emsp;&emsp; }<br/>
> &emsp;&emsp; ...<br/>
> &emsp;&emsp; apply plugin: 'com.google.gms.google-services'  // Add to the bottom of the file_<br/>

4. Run the starter app

> Now that you have imported the project into Android Studio and maked sure the dependencies for ML Kit are updated, you are
ready to run the app for the first time. Start the Android Studio emulator, and click Run in the Android Studio toolbar.
> 
> The app should launch on your device/emulator. At this point, you should see a basic layout with an image icon at the top
to import a photo (from camera/storage).

Autors
------
* Clément RENDU - [LinkedIn](https://www.linkedin.com/in/clementrendu/)

Screenshots
-----------
None for the moment.

License
-------
[Uncopyrighted](http://zenhabits.net/uncopyright/)
