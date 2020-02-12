### Official documents

- AOSP document:

    [https://source.android.com/devices/tv](https://source.android.com/devices/tv)<br>
    [https://source.android.com/devices/audio/tv](https://source.android.com/devices/audio/tv)


- Android developer (Android SDK) document:

    https://developer.android.com/tv<br>
    https://developer.android.com/training/tv<br>
    https://developer.android.com/training/tv/tif/tvinput<br>
    https://developer.android.com/design/tv<br>

- API reference:

    https://developer.android.com/reference/android/media/tv/package-summary.html

TIF companion library: https://bintray.com/google/tif-companion/tif-companion


### AOSP

- framework:

    frameworks/base/services/core/java/com/android/server/tv/<br>
    frameworks/base/media/java/android/media/tv/

- HAL:

    hardware/libhardware/include/hardware//tv_input.h<br>
    hardware/libhardware/modules/tv_input/<br>
    hardware/interfaces/tv/<br>

    frameworks/base/services/core/jni/com_android_server_tv_TvInputHal.cpp

- APP:

    developers/build/prebuilts/androidtv/<br>
    packages/apps/TV


### Samples
TIF TVInput example:
- android formal : https://github.com/googlesamples/androidtv-sample-inputs
- CSDN : https://github.com/songwenju/TIFSample


    `<tv-input>`[](http://androidxref.com/9.0.0_r3/xref/frameworks/base/core/res/res/values/attrs.xml#8654) in the manifest of TVInput service
