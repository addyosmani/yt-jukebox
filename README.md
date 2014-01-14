yt-jukebox
==========

A YouTube Jukebox application built with Polymer. Shown at DotJS. 


![](http://i.imgur.com/D8LpCUT.png)

### Notes

* This is a Polymer port of [JukeTube](https://github.com/jgthms/juketube) - an AngularJS app.
* This application is not yet ready for production use
* It does not use the newer Bower setup for Polymer elements (yet)
* It has only been tested in Chromium edge builds / Canary
* It uses custom versions of elements found in polymer-elements
* A tutorial based on a newer version of this app is currently planned

### Elements

* yt-jukebox
* yt-input
* yt-search
* yt-video
* polymer-ui-ratings
* polymer-ui-tabs

### Purpose

When you attend parties, YouTube is often used as the sole music provider. People in turn launch the video they want to hear. The process goes as follows:

* open a new tab
* browse to YouTube
* search for a video
* open and instantly pause it (to preload it)
* wait for the current video to stop
* launch the new video

Several problems arise from this process:

* need to wait for the current video to stop before launching a new one
* need to permanently have someone queuing and launching a new video
* no automatic play, so if the current video ends, there's no music
* time spent queuing a new video
* tons of tabs opened

### Features

JukeTube is an attempt to simplify this scenario.

* Single page app
* Ajax search
* Playlists (upcoming and archived videos)
* Automatic play (as soon as the current video ends)