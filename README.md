
# GDK for Android

## Installation

GDK is available through [JitPack](https://jitpack.io/). To install it, simply follow the instructions:


Add it in your root build.gradle at the end of repositories:
```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

Add the dependency
```
implementation "com.github.blockstram:gdk_android:$gdk_version"
```