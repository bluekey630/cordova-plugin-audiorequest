# cordova-plugin-audiofocus
AudioFocus is a Cordova plugin for Android platform that allows requesting of audio focus.
> Android uses audio focus to moderate audio playback—only apps that hold the audio focus should play audio.

### Installation
Using Cordova/Ionic

```sh
$ cordova plugin add https://github.com/bluekey630/cordova-plugin-audiorequest.git
```

### Usage
```js
window.audioFocus.requestFocus(function() {
    // succeeded to gain focus
}, function() {
    // failed to gain focus
});
```

License
----
Apache License, Version 2.0
