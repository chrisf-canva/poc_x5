# POC for X5 engine intead of Android system webview 

- Aug 2, 2021

  Phase 1: use [cordova-plugin-tbs-x5-engine-static](https://www.npmjs.com/package/cordova-plugin-tbs-x5-engine-static)


### Install
1. Add android plugin
```
cordova platform add android@9.0.0
```
2. Add *cordova-plugin-tbs-x5-engine-static* plugin
```
yarn add -D cordova-plugin-tbs-x5-engine-static
cordova plugin add cordova-plugin-tbs-x5-engine-static
```
3. Set android minSdkVersion

   Set `minSdkVersion` at platforms/android/CordovaLib/build.gradle#L65 to be **15**
