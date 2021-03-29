# cordova-plugin-gaodelocation
# cordova高德定位插件

- [原始README](README_ORIGIN.md)
- [原始仓库](https://github.com/waliu/cordova-plugin-gaodelocation-chenyu)

> 2020/10/28

> 兼容Capacitor

### 安装
```shell script
npm install git+http://192.168.3.168:12000/tool/cordova-plugin-gaodelocation-chenyu.git
npm install @ionic-native/gao-de-location
ionic cap sync
```

### 配置

#### Android
> `android/app/src/main/AndroidManifest.xml`
```xml
<manifest>
  <application>
    <meta-data android:name="com.amap.api.v2.apikey" android:value="$ANDROID_API_KEY"></meta-data>
    <service android:name="com.amap.api.location.APSService"/>
  </application>
</manifest>
```

### iOS

> `ios/App/App/config.xml`
```xml
<widget>
  <preference name="IOS_API_KEY" value="$IOS_API_KEY"/>
</widget>
```
