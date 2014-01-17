yt-jukebox
==========

> A YouTube Jukebox element built with Polymer.js.  

![](http://i.imgur.com/D8LpCUT.png)

## Setup

Install with [npm](https://npmjs.org/) and [bower](http://bower.io): `npm install && bower install`. You can then preview the application by running `grunt server`.

Run `bower info yt-jukebox` to list the available versions of `yt-jukebox` available.

### Usage:

Include the element after referencing `<link rel="import" href="polymer.html">` in your page:
    
```
<yt-jukebox></yt-jukebox>
```

Attributes supported:

* `maxResults` - the maximum number of results to display  
* `muted` - whether the video player should be muted
* `index` - the tab to display

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
* yt-jukebox-ratings (polymer-ui-ratings)
* yt-jukebox-tabs (polymer-ui-tabs)
* yt-jukebox-selector (polymer-selector)

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

## License

MIT © [Addy Osmani](http://addyosmani.com)
