# Top10Downloader
This is an Android app that uses apple's RSS feeds to display the Top Apps that were downloaded. This multi-threaded application will pull data from the RSS feeds, and allow the user to download the top apps, which will be processing in the background (in another thread) and will notify the user when it's done downloading in the UI.

This application requires internet permissions. Add the following line to your Manifest file 
```<uses-permission android:name="android.permission.INTERNET" />```

Find Apples available RSS feeds for use here: https://www.apple.com/rss/
