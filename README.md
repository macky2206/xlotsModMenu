MainActivity
```
invoke-static {p0}, Lcom/android/support/Main;->Start(Landroid/content/Context;)V
```
AndroidManifest.xml
1
```
<uses-permission android:name="android.permission.SYSTEM_ALERT_WINDOW"/>
```
2
```
<service android:name="com.xlots.support.Launcher" android:enabled="true"
    android:exported="false" android:stopWithTask="true" />
```
