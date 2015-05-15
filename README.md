# GooglePlus
Integrate google plus login in android app and retrieve basic user profile like name, email, gender, profile picture etc.

Enable Google+API. Create a new Client ID for Installed Applications in console.google.com by creating a new project. Select
Android, enter your project's package name and SHA1 certificate. Enable Deep Linking and click on Create Client ID button. 

Now go to build.gradle file (not root level) and inside depandencies, enter compile 'com.google.android.gms:play-services:7.0.0'.
This will include google play services for google plus Login.

