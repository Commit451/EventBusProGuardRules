# EventBusProGuardRules
ProGuard rules for EventBus shipped as an AAR!

[![Build Status](https://travis-ci.org/Commit451/EventBusProGuardRules.svg?branch=master)](https://travis-ci.org/Commit451/EventBusProGuardRules) [![](https://jitpack.io/v/Commit451/EventBusProGuardRules.svg)](https://jitpack.io/#Commit451/EventBusProGuardRules)

# Gradle Dependency

Add this in your root `build.gradle` file (**not** your module `build.gradle` file):

```gradle
allprojects {
	repositories {
		...
		maven { url "https://jitpack.io" }
	}
}
```

Then, add the library to your project `build.gradle`
```gradle
dependencies {
    compile 'com.github.Commit451:EventBusProGuardRules:3.0.0.0'
}
```

# Source
greenrobot kindly provides the appropriate ProGuard rules on their [site](http://greenrobot.org/eventbus/documentation/proguard/)

# Thanks
Thanks to greenrobot for the awesomeness that is EventBus, and to [Artem](https://github.com/artem-zinnatullin) for the idea of making this a library


License
--------

    Copyright 2016 Commit 451
    Copyright 2015 Markus Junginger, greenrobot

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
