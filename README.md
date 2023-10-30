# Newsant News App 📰
An Android news application implemented using the MVVM pattern, Retrofit2, Paging3, Dagger-Hilt, Flow, ViewModel, Coroutines, Room, Navigation Components, View Binding and some other libraries from the [Android Jetpack] . Newsant app fetches data from the [NewsAPI] .


## Architecture
The architecture of this application relies and complies with the following points below:
* A single-activity architecture, using the [Navigation Components](https://developer.android.com/guide/navigation) to manage fragment operations.
* Pattern [Model-View-ViewModel](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93viewmodel)(MVVM) which facilitates a separation of development of the graphical user interface.
* [Android architecture components](https://developer.android.com/topic/libraries/architecture/) which help to keep the application robust, testable, and maintainable.

<p align="center"><a><img src="https://raw.githubusercontent.com/mayokunthefirst/Instant-Weather/master/media/final-architecture.png" width="700"></a></p>

## Technologies used:

* [Kotlin](https://kotlinlang.org/) - First class and official programming language for Android development.
* [Retrofit](https://square.github.io/retrofit/) a REST Client for Android which makes it relatively easy to retrieve and upload JSON (or other structured data) via a REST based webservice.
* [Dagger Hilt](https://dagger.dev/hilt/) for dependency injection.
* [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) to store and manage UI-related data in a lifecycle conscious way.
* [Flow](https://developer.android.com/kotlin/flow) for handling asynchronous data streams.
* [Navigation Component](https://developer.android.com/guide/navigation) to handle all navigations and also passing of data between destinations.
* [Material Design](https://m3.material.io/) an adaptable system of guidelines, components, and tools that support the best practices of user interface design.
* [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) Coroutines help in managing background threads and reduces the need for callbacks.
* [Room](https://developer.android.com/topic/libraries/architecture/room) persistence library which provides an abstraction layer over SQLite to allow for more robust database access while harnessing the full power of SQLite.
* [Paging Library](https://developer.android.com/topic/libraries/architecture/paging/v3-overview) helps you load and display small chunks of data at a time.
* [Coil](https://coil-kt.github.io/coil/) - An image loading library for Android backed by Kotlin Coroutines.

## App Icon 📱
<img src="https://github.com/mondal-souvik/git/assets/100204863/55c7cccb-0c86-4812-b552-99e374e8a882" width="80px" hspace="40">

## Some Screenshots

**Dark Theme :**

<img src="https://github.com/mondal-souvik/git/assets/100204863/6e5da5cf-087e-4ef6-acaf-bcb8753a7bb3" height="470" width="220" hspace="10">
<img src="https://github.com/mondal-souvik/git/assets/100204863/74bc929b-0984-41c0-a171-7f6699602158" height="470" width="220" hspace="10">
<img src="https://github.com/mondal-souvik/git/assets/100204863/f53b49e7-532c-4f46-8c97-68fab59c1ba4" height="470" width="220" hspace="10">
<br/>
<br/>
<img src="https://github.com/mondal-souvik/git/assets/100204863/241f3e5f-cc2a-4c69-b760-bc0ae994568e" height="470" width="220" hspace="10">
<img src="https://github.com/mondal-souvik/git/assets/100204863/b24d8860-da7b-4b8f-acd8-b02c7865be42" height="470" width="220" hspace="10">
<img src="https://github.com/mondal-souvik/git-two/assets/100204863/f230ae36-923b-433b-8260-8b31f2ecbc38" height="470" width="220" hspace="10">

<br/>
<br/>
<br/>

**Light Theme :**

<img src="https://github.com/mondal-souvik/git-two/assets/100204863/ee411289-cd76-4548-a17b-ac2a9ece210f" height="470" width="220" hspace="10">
<img src="https://github.com/mondal-souvik/git-two/assets/100204863/b73bd36d-11e8-40ef-95af-48c0be339457" height="470" width="220" hspace="10">
<img src="https://github.com/mondal-souvik/git-two/assets/100204863/823ad3da-d453-4e61-ab7a-018b2e109ff2" height="470" width="220" hspace="5">
<br/>
<br/>
<img src="https://github.com/mondal-souvik/git-two/assets/100204863/810d6a40-cc01-489b-80f2-ae10885ad449" height="470" width="220" hspace="10">
<img src="https://github.com/mondal-souvik/git-two/assets/100204863/42453298-c636-401c-948b-63df316c8630" height="470" width="220" hspace="10">
<img src="https://github.com/mondal-souvik/git-two/assets/100204863/8ba67238-5b56-4597-aa10-fb2fa1526b30" height="470" width="220" hspace="10">

## Download APK
<img src="https://github.com/mondal-souvik/git-two/assets/100204863/47ea6bb6-0431-4d69-829b-112b1b7b4f54" width="110px" hspace="10">

[Android Jetpack]: https://developer.android.com/jetpack
[NewsAPI]: https://newsapi.org/
