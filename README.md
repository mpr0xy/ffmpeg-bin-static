ffmpeg-bin-static
====

Static binaries for `ffmpeg`.

Based on <https://github.com/joshwnj/ffprobe-static>.

Binaries are from <https://ffmpeg.org/download.html>

Usage
----

```js
var ffmpeg = require('ffmpeg-bin-static');
console.log(ffmpeg.path);
```

Version Notes
----

Currently supports Mac OS X (64-bit and Arm64), Linux (32 and 64-bit) and Windows
(64-bit).

Currently version `6.0` is installed for Mac, Windows and Linux.

I pulled the versions from the ffmpeg static build pages linked from the
official ffmpeg site. Namely:

* [64 bit Mac OSX](https://evermeet.cx/ffmpeg/)
* [64 bit Linux](https://johnvansickle.com/ffmpeg/)
* [32 bit Linux](http://johnvansickle.com/ffmpeg/)
* [64 bit Windows](https://www.gyan.dev/ffmpeg/)

