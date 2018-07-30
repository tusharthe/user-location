# user-location
Android User Location


Ask for permission  Androidmainfest.xml

    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
    <uses-permission android:name="android.permission.INTERNET" xmlns:android="#unknown" />
    
    
    Build.gradle(Mudule App)
       compile  'com.google.android.gms:play-services:11.8.0'
       
       
implements  GoogleApiClient.ConnectionCallbacks, GoogleApiClient.OnConnectionFailedListener, com.google.android.gms.location.LocationListener     
