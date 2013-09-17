LocationLibrary
===============

This Library uses LocationClient from google-play-services

You need to add Permission and receiver in menifest file in your AndroidMenfest.xml

While Using this library,
Make sure you declaire Receivers in your Project. LocationReceived
and declare permissions for fine location and coarse location.

You need to add this in your AndroidMenfest.xml
<pre>
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />

<receiver
android:name="com.LocationLibrary.locations.receiver.LocationReceived"
android:exported="true" >
</receiver></pre>
