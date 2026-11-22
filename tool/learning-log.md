# Tool Learning Log

## Tool: **Flutter**

## Project: **RNG Game**

### 10/19/26:
* Flutter is mostly an app-oriented coding engine.
  * It uses widgets (which are the building blocks)
    * This includes **Title bars, buttons, navigation**, etc. 
    * Only really works on _Windows_ and _iOS_. 
  * Flutter includes **debugging tools**.
* Commands like `flutter doctor` is important for tool setups.
  * `create` -> command to create a new project
  * `run` -> use this to run your projects
  * `test` -> used to test and debug your app
  * `build` -> Needed to build a finalized version of your app. 
```java
void main() {
  runApp(const MainApp());
}
```
* The main function is the **entry point** to any _Dart_ program.

### 11/3/26:
* To use Flutter in _Windows_, The first step is to download "Andriod Studio Emulator" to see the "phone" digtialy on the app as you code. (Make sure to download the latest version to code smoothly)

  * After, require the VS Code Studio to act as the coding terminal for the Flutter app (downloaded already)

  * Need extensions to code easily to check bracket endings & colored. (Not required)

  * Download XCode & Andriod Emulator (The main reason: they both support Flutter with easier navagation)

* To make an app, you need the Command terminal built on the computer to access/create the Flutter terminal (In Android Studio)  

  * `Scaffold` and `MaterialApp` widgets are the most important for building a **Flutter** app.

    * Both are needed to build an app. (Basically the skeleton of the code) 
* THE VIDEO THAT I'M CURRENTLY [WATCHING](https://www.youtube.com/watch?v=CD1Y2DmL5JM). The section that I'm up to -> `32:34` - `45:22`. 

### 11/20/26
* After successfully setting up Flutter in my **IDE**, it is finally time to showcase some **code/concepts** that I have learned in this [video](https://www.youtube.com/watch?v=CD1Y2DmL5JM) -> `45:30` - `1:23:40`.

  * Coding an app is way more complex then you think. Here are some things I needed to know first before coding 
    
    * Firstly, the "main" coding **file** in order to code the whole app is called "`main.dart`". That is the inner-body.

    * All widgets are **REQUIRED** to have capital letters or else there will be _multiple_ errors

    * The widgets need arguements (basically just parameters) to declare a function for itself. 
  
  * Some code to implement a "banner" (just a navbar) in the app:
  
  ```java
  appBar: AppBar(
      title: Text('App Title')
      ) // AppBar (Navbar)
  ```
* Next learning log, I will show how to make the bottom navbar (with home & settings), which takes more time to make. It requires image icons to upload from files in your computer






<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
