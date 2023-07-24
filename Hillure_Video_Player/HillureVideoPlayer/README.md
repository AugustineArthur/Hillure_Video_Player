# Hillure Video Player for Android
 ![App Icon](https://github.com/me50/AugustineArthur/blob/cs50/problems/2022/x/project/20220329_105742.png)
#### Watch Video Demo of the app: [Here](https://www.youtube.com/watch?v=oEkov5x229E&t=11s)
## Description
 This app supports or runs most mp4 files on android devices.
 It has a very simple user-friendly UI(the most basic form) that even people who are not
 good in the usage of modern technology can use easily.
 This app was created to serve as a simplified user friendly video player.
 This app was built using **Android Studio** and the language used is **Java**.
## Installation
 * No other softwares have to be installed in order to run the app
 * All you need to install this app is an android device with an android version of **4.4 or above**

## Features
 * Auto loads all video files on the device after launching the app
 ![Load Screen](https://github.com/me50/AugustineArthur/blob/cs50/problems/2022/x/project/loadScreen.png)


 * Displays a poster image of all video files
 * Displays the name of all files in a marquee form to facilitate full visibility of the file or video name
 * Auto plays a video when clicked on
 * No looping at the end of the video
## Usage
 * Upon The first launch of the app, the user would be asked to grant permission for the app to access the video files on the device
 ![Grant Permission](https://github.com/me50/AugustineArthur/blob/cs50/problems/2022/x/project/permission.png)

 * Swipe up gesture needed to increase volume level  while video is in play
 ![Swiping Up](https://github.com/me50/AugustineArthur/blob/cs50/problems/2022/x/project/Swipe%20Up.jpg)

 * Swipe down gesture needed to decrease volume level while video is in play
 ![Swiping Down](https://github.com/me50/AugustineArthur/blob/cs50/problems/2022/x/project/Swipe%20down.jpg)

 * left Swipe gesture needed to rewind the video while video is in play
 ![Swiping left](https://github.com/me50/AugustineArthur/blob/cs50/problems/2022/x/project/Swipe%20left.jpg)

 * Right swipe gesture needed to fast forward the video while in play
 ![Swiping right](https://github.com/me50/AugustineArthur/blob/cs50/problems/2022/x/project/Swipe%20forward.jpg)

 * control buttons are placed below the screen to pause or continue the video while in play

## Design
 * **VideoViewHolder.java** - This file was implemented in the program to design and define how the video files would be loaded after the app is launched
 * **PlayerActivity.java** - This file was implemented to define how the environment of the video player will look while the video is being played
 * **MainActivity.java** - This file was implemented to coordinated all other files used in the app, it defines the core functions of the app
 * **CustomAdapter.java** - This files was implemented to get or load all the video files found on the android device
 * **SelectListener.java** - This is a java interfaces file that is defined to perform some action after a video file has been selected or clicked on

## Dependencies
1. 'com.karumi:dexter:6.2.2'
2. 'com.github.halilozercan:BetterVideoPlayer:kotlin-SNAPSHOT'
    * **android:id="@+id/player"**
    * **android:layout_width="match_parent"**
    * **android:layout_height="wrap_content"**
    * **app:bvp_autoPlay="true"**
    * **app:bvp_captionSize="22sp"**
    * **app:bvp_disableControls="false"**
    * **app:bvp_gestureType="SwipeGesture"**
    * **app:bvp_hideControlsOnPlay="true"**
    * **app:bvp_pauseDrawable="@drawable/bvp_action_pause"**
    * **app:bvp_playDrawable="@drawable/bvp_action_play"**
    * **app:bvp_restartDrawable="@drawable/bvp_action_restart">**
 3.  maven {url 'https://jitpack.io'}

## Possible Improvements
* Ability to Delete and rename video files
* More control options like the speed of the video while in play
* Ability to show subtitles while video is in play

## Authors
 * Eric Augustine Arthur

