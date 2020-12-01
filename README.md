# Android Webview Guide
Guide to implement webview with permissions to camera and select file option using basic permissions. 

## Menifiest.Xml

Add these lines in AndroidManifest.xml

```
<uses-permission android:name="android.permission.CAMERA"/>
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
```

```
<uses-feature android:name="android.hardware.camera"/>
```
</br>

Attached [file](WebViewActivity.java) contains the sample code to implement webview. 


