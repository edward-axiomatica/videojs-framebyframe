videojs-framebyframe
====================

Allows users to step frame-by-frame through a video. This has to make an unfortunate assumption about framerate, but it should be "ok" for general use. If you can run framerate detection on the server side, this plugin works perfectly for you.

[Check out the demo](http://erasche.github.io/videojs-framebyframe)

## Framerate Issues

We have no way to get the actual framerate, so we make a guess.

- http://stackoverflow.com/questions/20336955/how-to-step-one-frame-forward-and-one-frame-backward-in-video-playback
- http://stackoverflow.com/questions/4298084/html5-frame-by-frame-viewing-frame-seeking
- https://github.com/videojs/video.js/issues/692
