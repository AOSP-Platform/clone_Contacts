## Clone AOSP platform_packages_apps_Contacts

This is repository to build AOSP Contacs app outside the AOSP source tree using gradle.



## Notes

* I'm not sure if this application will actually run without crashes, I don't want to replace my system dialer with this app. Need to fork AOSP Contacts and change package names etc.. to make it installable as a separate app.
* Other AOSP based Contacs apps might compile with these build scripts too with minimal modifications.
* Bundled lib packages are needed to build the app. `aosp-android.jar` is the `android.jar` for api 28 with hidden apis bundled, it's extracted from a AOSP build tree. `sdk.jar` is taken from `android_prebuilts`
