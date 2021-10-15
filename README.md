# Beginning Android Developer

## Udacity Android courses
- https://developer.android.com/courses/kotlin-bootcamp/overview
- https://developer.android.com/courses/kotlin-android-fundamentals/overview
- https://developer.android.com/courses/kotlin-android-advanced/overview

## Develop An Application
- Pick the smallest app you can think of and get it done.
- Plow through all of the steps required to release an app (with help or without, depending on your preference).
- Going through a full cycle will give you immense experience, and also a portfolio to show off.
- Ideas for basic app:
  - A custom calculator that can send the result to your email address.
  - A one-shot Tweet app.
  - A soundboard of fart noises.
  - A flashlight app.
- Once you’ve decided on that, break it down into smaller sections; an app that plays a single MP3 file, a button that changes colour when you press it or an asynchronous image downloader. Make each of these work before you try and build it into your larger project.
- This way will teach you how to work modularly, an invaluable skill if you’ve never worked on a true OO project before, and it will give you a finished mini-project at the end of each coding session to look at and say: "I made that".

## Best Practices
- Never hardcode your string, dimensions or value into code, put them into XML resources instead, e.g. `strings.xml`, `dimens.xml`.
- Refactor common attributes used in layout XML into style. You will save yourself sometimes to amend them when changes appear.
- Always build layouts so that they can scale.
- Avoid nested layout where possible, it's bad for performance. Best practice is to use `ConstraintLayout`.
- Use and love fragments.
- Use `RecyclerView` for performance.
- Don't write code that blocks thread execution. Keep heavy-duty / time-consuming stuffs from UI thread so that it doesn't compete with the UI rendering. Use `launch`, `withContext`.
- Make use of `dp` for layout size and `sp` for text size.
- Mock your layout using `tools:` namespace.
- Code to handle rotations up front.

## Activity Lifecycle
- Understand it.
- Print the [Android Activity Lifecycle](https://user-images.githubusercontent.com/28914732/137526236-74c80cfe-8f64-49a4-99c4-9b0bcabae225.png) on a big poster and stick it to a wall or something else near you. At the beginning (and for me, also later) it's very helpful!

## Design
- Be well versed on the design guidelines for Android (https://developer.android.com/design/index.html).
- You will need it to develop your own application.

## Architecture
- [MVVM](https://developer.android.com/jetpack/guide)

## Testing
- JUnit, Mockito, Espresso.
- [Test apps on Android](https://developer.android.com/training/testing)
- Do tests early or you won't do them at all.
- You will create better quality apps and save yourself plenty of time from repeated UI testing on multiple devices.

## IDE
- Use Android Studio.
- There are many plugins in Android Studio, make use of them.
  - Personal favourites: CodeGlance, Markdown.
- Use Android Studio features. It will reduce your development time a lot later on.
  - Refactor (Function, etc.)
  - Templates
  - Shortcuts (`Shift` + `Shift`, `Cmd` + `Click`, `Cmd` + `E`, `Cmd` + `Shift` + `F`, `Cmd` + `,`)
- Use custom color scheme for Logcat (https://medium.com/tedpark-developer/android-studio-how-to-change-logcat-color-3c17a10beef8).
- When using ADB, connect to a device over Wi-Fi (https://developer.android.com/studio/command-line/adb#connect-to-a-device-over-wi-fi-android-11+).
- Device Emulator to test the behavior of your app on various devices with different Android versions.
- APK Analyzer to analyze the size of the app by inspecting the APK content.
- Realtime Profilers to analyze real-time statistics on CPU, memory, and network usage.

## Libraries
- Retrofit, Glide, Dagger, Picasso

## Version Control
- Git

## Release
- Target the highest api level you can get away with.
- https://developer.android.com/distribute/best-practices/launch/launch-checklist

## Other Resources
- Books: Pragmatic Programmer, Mark Murphy's books.
- Learn to program with either free or paid options.
- Reddit: r/AndroidDev.
- Twitter: JakeWharton, Cyril Mottier, @androidDev (tips: also see who they follow).
- Google's Android Developer YouTube Channel (https://www.youtube.com/channel/UCVHFbqXqoYvEWM1Ddxl0QDg). Most of these videos are 5-10mins long and each cover one aspect of Android dev. Watch just one everyday and you'll learn a TON.
- Android Developers Blogspot (https://android-developers.googleblog.com/). Google's official outlet for new Android announcements.
- Android API Guides (https://developer.android.com/guide). Most of the time, you'll find yourself here looking for methods within a class, but it's fun to just browse around and see what's there, you'll learn a lot and have more tools in your toolbox.
- Podcasts: Android Developers Backstage, Fragmented Podcast.

## Advices
- Don't be afraid of animation, it's not that difficult, and it adds a nice touch.
- Read everything. As a junior unless you're up against a deadline, your time is best spent expanding your education. Spend at least an hour a day reading something related to Android. Even going over something you think you know well can sometimes bring new nuggets of information. Your education is never ending because Android moves extremely fast. So keep reading, keep learning, and always move forward.
- The code you write is like a love note to the next developer that has to deal with it. Show them how much you love them with clarity and comments on the difficult stuff.
