# Coding-Nightmare-
I need help figuring out how to code an app that I intend to create using Android studio,( sorry if i'm a little slow on picking up on content...i'm 14), but all the feedback and help would really be appreciated...also please include tons of tips please
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.remindo.remindo" >

    <uses-feature android:name="android.hardware.type.watch" />

    <application
        android:allowBackup="true"
        android:icon="@mipmap/ic_launcher"
        android:label="@string/app_name"
        android:theme="@android:style/Theme.DeviceDefault" >
        <activity
            android:name=".MyStubBroadcastActivity"
            android:label="MyStubBroadcastActivity" >
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
        <activity
            android:name=".MyDisplayActivity"
            android:allowEmbedded="true"
            android:exported="true"
            android:taskAffinity=""
            android:theme="@android:style/Theme.DeviceDefault.Light" >
        </activity>

        <receiver
            android:name=".MyPostNotificationReceiver"
            android:exported="true" >
            <intent-filter>
                <action android:name="com.remindo.remindo.SHOW_NOTIFICATION" />
            </intent-filter>
        </receiver>
    </application>
    <activity android:name="MyNoteActivity">
        <intent-filter>
            <action android:name="android.intent.action.SET_TIMER" />
            <category android:name="com.remindo.remindo.SET_TIMER" />
        </intent-filter>
    </activity>

        </application>
        <activity android:name="MyRemminderActivity">
        <intent-filter>
            <action android:namee""

        </intent-filter>

















</manifest>


