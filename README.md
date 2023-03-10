# VideoLow
VideoLow is a lightweight, free tool for Windows based on [ffmpeg](https://github.com/FFmpeg/FFmpeg) that allows you to compress, transcode and trim /clip mp4 videos (and also audio files (mp3 and aac)) easily.
This is the perfect tool if you want to create a clip from a video to send to your friends. 
Avoid large file sizes by selecting a smaller bitrate and speed up the process by utilizing your GPU.


It currently supports h.264 and hevc (h.265) video codecs, as well as mp3 and aac audio codecs.
The GUI is made with [QT 5](https://github.com/qt/qt5).

# Features
- select a video per drag & drop
- review videos / audio with a built-in video player
- trim videos / audio
- select start and end position for the trimmed part during playback
- choose to export the video / audio with specific settings
- remove audio from a video or only export the audio
- quick export options for easier access
- trim only function that trims the video without reencoding which results in an almost instantly trimmed video
- supports AMD (amf) and Nvidia (nvenc) hardware accelerated codecs

![Main Window](https://user-images.githubusercontent.com/29144928/206918013-8584c8d9-c00f-4f2b-b3bf-8848a5af1377.png)

![Trim Window](https://user-images.githubusercontent.com/29144928/206918099-7c68bcff-838a-4ad8-ac36-2995273cbf69.png)


# Build

- requires CMake
- requires QT 5
- requires Visual Studio as Compiler

```
git clone ...
cd VideoLow
./build-all.bat
```
