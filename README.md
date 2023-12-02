# manifest1
````
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools">

    <uses-permission
        android:name="com.android.alarm.permission.SET_ALARM" />
    <application
        android:allowBackup="true"
        android:dataExtractionRules="@xml/data_extraction_rules"
        android:fullBackupContent="@xml/backup_rules"
        android:icon="@drawable/logoproject"
        android:label="@string/app_name"
        android:roundIcon="@drawable/logoproject"
        android:supportsRtl="true"
        android:theme="@style/Base.Theme.AppIntent"
        tools:targetApi="31">

        <activity
            android:name=".MainActivity"
            android:exported="true">
            <intent-filter>
                <action android:name="android.intent.action.SET_ALARM" />
                <category android:name="android.intent.category.DEFAULT" />
            </intent-filter>
        </activity>

        <activity
            android:name=".HelloActivity"
            android:exported="true" />

        <activity
            android:name=".TwoactActivity"
            android:exported="true" />

        <activity
            android:name=".Twoact2Activity"
            android:exported="true" />

        <activity
            android:name=".CountActivity"
            android:exported="true" />

        <activity
            android:name=".SianidaActivity"
            android:exported="true" />

        <activity
            android:name=".SplashScreen"
            android:exported="true"
            android:theme="@style/SplashScreen">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />
                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>

</manifest>
````
