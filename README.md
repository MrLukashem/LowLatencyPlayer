# LowLatencyPlayer
Low latency audio/video player using OpenSL SE lib

-----------------------------------------------------------------
It is player on android platform.

The LowLatencyPlayer don't use high level java API like MediaPlayer/AudioTrack.
It use native c++11/14 code and OpenSL SE library. Probably decoding audio/video will be made by native MediaCodec.
Most of forces will be pass to create low latency audio playback and method how to do it will be described soon.
