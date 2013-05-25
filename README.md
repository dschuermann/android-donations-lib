# Android Donations Lib

Android Donations Lib supports donations by Google Play Store, PayPal, and Flattr.

It is used in my projects AdAway, FasterGPS, and NTP-Sync.

# NEWS

* Now uses Gradle Build System (http://tools.android.com/tech-docs/new-build-system)
* No xml configuration needed anymore!
* Fragment can be instantiated and used in any Activity.
* Using Gradle you can build "product flavors": One version with Google Play Donation capability and one with Paypal and Flattr!

# Contribute

Fork Android Donations Lib and do a pull request. I will merge your changes back into the main project.

# Screenshot

![Screenshot](http://github.com/dschuermann/android-donations-lib/raw/master/screenshot.png)

# Add the lib to your project

* ExampleApp depends on "libraries/Donations" and has two product flavors defined in its gradle configuration.
* See 
* When publishing the app you have to create in-app products for your app in the Google Play Store that matches the ones you defined in ``private static final String[] GOOGLE_CATALOG``