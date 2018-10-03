##  [Background Location Updates in Android "O"](https://codelabs.developers.google.com/codelabs/background-location-updates-android-o/index.html?index=..%2F..%2Findex#0)
## 更正
在 app/build.gradle 裡面的
```aidl
android {
   compileSdkVersion "android-O"
   defaultConfig {
       ...
       targetSdkVersion "O"
       ...
   }
   ...
}
```
應該改成
```aidl
android {
   compileSdkVersion 26
   defaultConfig {
       ...
       targetSdkVersion 26
       ...
   }
   ...
}
```
