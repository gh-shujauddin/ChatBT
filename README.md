<!-- 
![GitHub Cards Preview](https://github.com/Spikeysanju/Expenso/blob/master/art/EXPENSO-ANDROID.png?raw=true)
-->
# ChatBT
A Simple Bluetooth Chat application 📱 built to demonstrate the use of modern android architecture component with MVVM Architecture 🏗 and bluetooth services.

<br />


## Day Mode 🌞
Pair Devices- Host | Pair Devices- Client | Host Chat Screen | Client Chat Screen 
--- | --- | --- |--- 
![](https://github.com/gh-shujauddin/ChatBT/assets/73093103/a06f31f2-1b4c-4988-80cd-9c933e725469) | ![](https://github.com/gh-shujauddin/ChatBT/assets/73093103/d7b5c4a3-cfb0-47cc-b4ae-c820279e7ebe) | ![](https://github.com/gh-shujauddin/ChatBT/assets/73093103/6c663544-b731-434b-8d4e-5d526dbf5417) | ![](https://github.com/gh-shujauddin/ChatBT/assets/73093103/bc69c63e-c29b-4d86-bcaa-6c9f2013a8bc)

<br />

## Built With 🛠
- [Kotlin](https://kotlinlang.org/) - First class and official programming language for Android development.
- [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) - For asynchronous and more..
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Collection of libraries that help you design robust, testable, and maintainable apps.
  - [Stateflow](https://developer.android.com/kotlin/flow/stateflow-and-sharedflow) - StateFlow is a state-holder observable flow that emits the current and new state updates to its collectors. 
  - [Flow](https://kotlinlang.org/docs/reference/coroutines/flow.html) - A flow is an asynchronous version of a Sequence, a type of collection whose values are lazily produced.
  - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Stores UI-related data that isn't destroyed on UI changes. 
- [Material Components for Android](https://github.com/material-components/material-components-android) - Modular and customizable Material Design UI components for Android.
<!-- - [Figma](https://figma.com/) - Figma is a vector graphics editor and prototyping tool which is primarily web-based. -->

<br />

## Package Structure 📦
    
    com.qadri.chatbt # Root Package
    ├── di                  # Hilt DI Modules 
    ├── data                # For data handling.
    │   ├── chat            # Files for data transfer login using bluetooth
    |
    ├── presentation        # UI 
    │   ├── component       # All the UI Screens
    |   
    ├── domain              # All data clesses or extensible functions


<br />


## Architecture 🗼
This app uses [***MVVM (Model View View-Model)***](https://developer.android.com/jetpack/docs/guide#recommended-app-arch) architecture.

![](https://github.com/TheCodeMonks/Notes-App/blob/master/screenshots/ANDROID%20ROOM%20DB%20DIAGRAM.jpg)

## Build-tool 🧰
You need to have [Android Studio Beta 3 or above](https://developer.android.com/studio/preview) to build this project.
<br>
<img src="./beta_android.png" height="200" alt="Beta-studio"/>

<br>

<br>

## Contact 📩
Have an project? DM us at 👇

Drop a mail to:- mshuja.uq@gmail.com

<br>

<!-- ## Donation 💰
If this project help you reduce time to develop, you can give me a cup of coffee :) 

<a href="https://www.buymeacoffee.com/Li0hsl4" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

<br>
-->
