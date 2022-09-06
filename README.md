# Android-WebView-Example
Example project to showcase how to load a local html file into a webview within an Android application

Mainly written because [edent](https://twitter.com/edent) asked the [question](https://twitter.com/edent/status/1566876367861563393)

Application consits of one Web View with the layout defined in [app/src/main/res/layout/activity_main.xml](https://github.com/devwithzachary/Android-WebView-Example/blob/main/app/src/main/res/layout/activity_main.xml), and an activity to load the html [app/src/main/java/site/zpweb/webviewsample/MainActivity.kt](https://github.com/devwithzachary/Android-WebView-Example/blob/main/app/src/main/java/site/zpweb/webviewsample/MainActivity.kt).

The HTML file is stored in the asset folder [app/src/main/assets](https://github.com/devwithzachary/Android-WebView-Example/tree/main/app/src/main/assets)

By loading the URL using the file schema relative linking to files within the asset folder "should" (untested) work just fine.

See [WebView](https://developer.android.com/reference/android/webkit/WebView) for more details.
