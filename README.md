# Drone looper for PureData

There are dozens of loopers on the market but all of them are lacking the features I need.

This is the implementation of the looper in PureData.
Some other objects could be useful in other setups.

The development is going in https://agraef.github.io/purr-data/ and that means there could be bugs or suboptimal working in stock PureData.

Note: don't try to read the code, it is not for human consumption.

## Usage

* Open `looper-test.pd`.
* Turn on DSP in main PureData window.
* Click "record" to start recording, "stoprecord" to stop recording
* Click "play" to start playing, "stop" to stop playing.
* --> Adjust numbers on the right side of the looper to set start and stop points for the loop realtime

That's it, folks.

If anyone knows looper that has features marked with --> please let me know -- that is the features I miss and the reason for implementation.


## License and authors

* Author: Timur Batyrshin
* License: MIT
