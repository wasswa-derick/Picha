[![CircleCI](https://circleci.com)](https://circleci.com/)
[![Maintainability](https://api.codeclimate.com)](https://codeclimate.com)
[![Test Coverage](https://api.codeclimate.com/)](https://codeclimate.com)

Picha
=====

An application that allows users to get images for their wallpapers as well as acting as a background for quotes rendered to users.

### [Picha on Google Play Store](https://play.google.com/store/apps/details?id=com.rosen.jambo)


## Screenshots


## Getting Started and Installation

1. Open up the terminal and clone the repository under any directory using `git clone https://github.com/wasswa-derick/Picha.git`.

2. In Android Studio, under the file menu select open, then select an existing project and navigate to the project you just cloned.

3. Build the project using `./gradlew build`.

4. Run the application on a connected device or emulator.


### Prerequisites

1. [Set up Android Studio](https://developer.android.com/studio/install)

2. [Enable Kotlin in Android Studio](https://medium.com/@elye.project/setup-kotlin-for-android-studio-1bffdf1362e8)

3. [Run application on emulator](https://developer.android.com/studio/run/emulator)

4. [Run application on android device](https://developer.android.com/studio/run/device)


## Running the tests (Unit and Instrumentation tests)

1. Run tests using `./gradlew test` or `./gradlew jacocoTestReport`.

Unit tests can be run using one of the following:
~~~~
./gradlew test
~~~~

Jacoco Tests report (Run both instrumented and unit tests at once).
~~~~
./gradlew jacocoTestReport
~~~~

2. To run instrumentation tests, endeavor to have an emulator or an Android Device connected either via USB or WIFI.


## Architecture
* Model View ViewModel (MVVM)


## Dependencies

* [Android](https://www.android.com/) - Operating System
* [Retrofit](https://square.github.io/retrofit/) - HTTP Requests
* [Kotlin](https://kotlinlang.org/) - Programing language
* [Room](https://developer.android.com/topic/libraries/architecture/room) - Local database
* [Dagger 2](https://github.com/google/dagger) - Dependency Injection
* [RxAndroid](https://github.com/ReactiveX/RxAndroid) - Asynchronous and event-based functionality
* [RxJava](https://github.com/ReactiveX/RxJava) - Asynchronous and event-based functionality
* [Picasso](http://square.github.io/picasso/) - Image processing


## Authors
[Derick Wasswa](https://github.com/wasswa-derick)


## Credits
All props to [Unsplash](https://unsplash.com) for availing the service.
