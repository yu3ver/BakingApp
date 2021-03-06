
<a style="margin-bottom: 0;" 
	href='https://play.google.com/store/apps/details?id=it.instantapps.bakingapp'>
	<img alt='Get it on Google Play' 
	src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' height="80px"/>
</a>

# Baking app
It was evaluated by certified [Udacity](https://www.udacity.com/course/android-developer-nanodegree-by-google--nd801) code reviewer and was graded as "Exceeds Specifications".

## Why this Project?
As a working Android developer, you often have to create and implement apps where you are responsible for designing and planning the steps you need to take to create a production-ready app. Unlike Popular Movies where we gave you an implementation guide, it will be up to you to figure things out for the Baking App.

## What Will I Learn?
In this project you will:
* Use MediaPlayer/Exoplayer to display videos.
* Handle error cases in Android.
* Add a widget to your app experience.
* Leverage a third-party library in your app.
* Use Fragments to create a responsive design that works on phones and tablets.


## Rubric

### General App Usage
- [x] App should display recipes from provided network resource.
- [x] App should allow navigation between individual recipes and recipe steps.
- [x] App uses RecyclerView and can handle recipe steps that include videos or images.
- [x] App conforms to common standards found in the Android Nanodegree General Project Guidelines.

### Components and Libraries
- [x] Application uses Master Detail Flow to display recipe steps and navigation between them.
- [x] Application uses Exoplayer to display videos.
- [x] Application properly initializes and releases video assets when appropriate.
- [x] Application should properly retrieve media assets from the provided network links. It should properly handle network requests.
- [x] Application makes use of Espresso to test aspects of the UI.
- [x] Application sensibly utilizes a third-party library to enhance the app's features. That could be helper library to interface with Content Providers if you choose to store the recipes, a UI binding library to avoid writing findViewById a bunch of times, or something similar.

### Homescreen Widget
- [x] Application has a companion homescreen widget.
- [x] Widget displays ingredient list for desired recipe.

## Screens

![screen](https://user-images.githubusercontent.com/18085976/32411293-8fe77754-c1ad-11e7-860f-2062db16e73a.png)


## Libraries

* [Glide](https://github.com/bumptech/glide)
* [OkHttp](https://github.com/square/okhttp)
* [Retrofit 2](https://square.github.io/retrofit/)
* [Butter Knife](https://jakewharton.github.io/butterknife/)
* [Apache Common Version](http://commons.apache.org/)
* [Exoplayer](https://github.com/google/ExoPlayer/)
* [Firebase jobdispatcher ](https://github.com/firebase/firebase-jobdispatcher-android/)
* [Espresso](https://developer.android.com/training/testing/espresso/index.html)
* [Android-Iconics](https://github.com/mikepenz/Android-Iconics)

## Test 

### Firebase Test Robo (Passed)

* [Galaxy S7 edge, livello API 23](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-01T17%3A23%3A29.734Z_b1aq/hero2lte-23-en_US-portrait/video.mp4)
* [Galaxy S7, livello API 23](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-02T17%3A33%3A53.559Z_7q6i/herolte-23-en_US-landscape/video.mp4)
* [Huawei P8 lite, livello API 21](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-01T17%3A23%3A29.734Z_b1aq/hwALE-H-21-en_US-portrait/video.mp4)
* [LG G6 LGUS997, livello API 24](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-01T17%3A23%3A29.734Z_b1aq/lucye-24-en_US-portrait/video.mp4)
* [Low-resolution MDPI phone, Virtual, livello API 23](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-02T17%3A01%3A44.994Z_jowi/NexusLowRes-23-en_US-landscape/video.mp4)
*  [Nexus 10, Virtual, livello API 21](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-02T17%3A19%3A03.091Z_28lo/Nexus10-21-en_US-portrait/video.mp4)
* [Nexus 5, livello API 23](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-03T14%3A00%3A20.010Z_5j5y/hammerhead-23-en_US-portrait/video.mp4)
* [Nexus 5, Virtual, livello API 23](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-02T17%3A19%3A03.091Z_28lo/hammerhead-23-en_US-portrait/video.mp4)
* [Nexus 5X, Virtual, livello API 26](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-02T17%3A19%3A03.091Z_28lo/Nexus5X-26-en_US-portrait/video.mp4)
* [Nexus 6, Virtual, livello API 21](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-02T17%3A01%3A44.994Z_jowi/Nexus6-21-en_US-landscape/video.mp4)
* [Nexus 6P, Virtual, livello API 26](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-02T17%3A19%3A03.091Z_28lo/Nexus6P-26-en_US-portrait/video.mp4)
* [Nexus 7 (2012), Virtual, livello API 21](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-02T17%3A19%3A03.091Z_28lo/Nexus7-21-en_US-portrait/video.mp4)
* [Pixel, livello API 26](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-01T17%3A23%3A29.734Z_b1aq/sailfish-26-en_US-portrait/video.mp4)
* [Sony XPERIA XZ Premium, livello API 25](https://storage.googleapis.com/test-lab-7mbff5754t2f0-nqu2bv2ntmrs8/web-build_2017-11-05T02%3A42%3A20.784Z_irew/G8142-25-en_US-portrait/video.mp4)


### Google Play 
* [Verified by Google Play Protect](https://www.android.com/play-protect/)

## License

    Copyright 2017 Benedetto Pellerito

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
