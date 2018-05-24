<p align="center">
	<img width="72" height="72" src="art/ic_launcher-web.png"/>
</p>
<h3 align="center">ScreenCapture</h3>
<p align="center">
<a href="" target="_blank"><img src="https://img.shields.io/badge/release-v1.0-blue.svg"></img></a>
</p>

## create mp4 with MediaProjection，there is no voice for the time being

## according to [ScreenRecorder][1] adaptation,thanks [Yrom Wang][2]

## usage:

### dependencies :

```
dependencies {
    //...
    implementation 'com.hd:screencapture:1.0'
}
```

### code

```
ScreenCapture.with(activity).startCapture();
```

[1]: https://github.com/yrom/ScreenRecorder
[2]: https://github.com/yrom
