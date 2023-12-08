# SheShield
I Developed This WomenSafety App via Kotlin and Many More Features in it. 

Introduction to Android:
Android is a mobile operating system (OS) developed by Google. It is based on the Linux kernel and is designed primarily for touchscreen devices such as smartphones and tablets. Android has become one of the most popular operating systems in the world, powering a vast array of mobile devices.
History of Android:
1.	Android Inc.: Android was founded by Andy Rubin, Rich Miner, Nick Sears, and Chris White in October 2003. The initial goal of Android was to create an advanced operating system for digital cameras. However, due to the changing market demands, the focus shifted to creating a mobile phone platform.
2.	Acquisition by Google (2005): In August 2005, Google acquired Android Inc., signaling its entry into the mobile device market. The acquisition allowed Google to establish a presence in the growing smartphone industry.
3.	Open Handset Alliance (2007): In November 2007, the Open Handset Alliance (OHA) was formed, a consortium of technology and mobile companies led by Google. The OHA aimed to develop open standards for mobile devices and promote the Android platform.
4.	Android OS Releases:
 
•	Android 1.0 (2008): The first commercial version of Android was released in September 2008 on the HTC Dream smartphone.
•	Cupcake, Donut, Eclair, Froyo (2009-2010): These were incremental updates with improvements to features and performance.
•	Gingerbread, Honeycomb (2010-2011): Gingerbread focused on refining the user interface, while Honeycomb was designed specifically for tablets.
•	Ice Cream Sandwich, Jelly Bean (2011-2012): These versions aimed at unifying the smartphone and tablet experiences.
•	KitKat, Lollipop, Marshmallow (2013-2015): These versions introduced visual and performance enhancements along with new features.
•	Nougat, Oreo (2016-2017): These versions focused on improving system performance, battery life, and security.
•	Pie, Android 10 (2018-2019): Introduced gesture-based navigation and improved privacy features.
•	Android 11 (2020): Focused on improving communication and device controls.
•	Android 12 (2021): Introduced a major redesign called "Material You," emphasizing customization and personalization.
5.	Android Today:
•	Android has evolved into a versatile platform used not only in smartphones and tablets but also in smartwatches, TVs, and other smart devices.
•	The Google Play Store provides a vast repository of applications for Android users.
•	Android is an open-source platform, allowing developers to customize and modify the operating system to suit their needs.
Understanding the evolution of Android is crucial for exam preparation, as questions may cover the historical development, key milestones, and major features introduced in different Android versions.

API Level
In the context of Android development, the term "API level" refers to a version of the Android SDK (Software Development Kit) that provides a set of tools and libraries for developers to create Android applications. Each Android version is assigned a unique API level, which serves as a reference point for developers when building and testing their apps.
Here's a breakdown of what an API level entails:
1.	SDK Version Number: The API level is represented by an integer value, such as 23, 24, 25, etc. This value corresponds to a specific version of the Android SDK.
2.	Compatibility: Apps are compiled against a specific API level, ensuring compatibility with devices running that Android version or later. Developers can set the minimum and target API levels in their app's manifest file to specify the range of Android versions the app is designed to support.
3.	Features and APIs: Each API level introduces new features, enhancements, and APIs (Application Programming Interfaces) that developers can utilize in their applications. Conversely, some older APIs may become deprecated as the Android platform evolves.
4.	Testing and Development: Developers use API levels to test their apps on different Android versions, ensuring that the apps function correctly and take advantage of the latest features without breaking compatibility with older devices.
For example, an app developed with a minimum API level of 21 would be compatible with devices running Android 5.0 (Lollipop) and newer versions. As developers increase the API level, they gain access to newer features, but the app may not be compatible with devices running older Android versions. Managing API levels is crucial for creating apps that reach a broad audience while leveraging the latest capabilities offered by the Android platform.

Android Architecture
 
The Android operating system follows a layered architecture, which is designed to provide a robust and flexible framework for mobile devices. The key components of the Android architecture include:
1.	Linux Kernel:
•	The foundation of the Android operating system.
•	Manages hardware resources such as memory, processors, and device drivers.
•	Provides essential features like security, process management, and power management.
2.	Hardware Abstraction Layer (HAL):
•	Sits between the Linux Kernel and the Android framework.
•	Abstracts the hardware-specific implementation details, allowing the upper layers to remain hardware-agnostic.
3.	Android Runtime (ART):
•	The runtime environment where Android applications run.
•	In earlier versions, Dalvik was used as the runtime, but ART became the default starting with Android 5.0 (Lollipop).
•	Responsible for executing and managing Android app code.
4.	Native Libraries:
•	Libraries written in C and C++ that provide core functionalities to the Android system.
•	Includes libraries for graphics rendering, media playback, and database access.
5.	Android Framework:
•	A set of APIs and tools that developers use to build Android applications.
•	Consists of various modules like Activity Manager, Content Providers, View System, Location Manager, etc.
•	Provides a rich set of pre-built components for building UI, handling data, and managing app behavior.
6.	System Apps:
•	Essential applications that come pre-installed on Android devices.
•	Examples include the Phone app, Contacts app, Settings app, etc.
•	Part of the Android Open Source Project (AOSP) and can be replaced or customized by device manufacturers.
7.	Application Layer:
•	The top layer where third-party applications reside.
•	Developers create apps using the Android SDK and Java (or Kotlin) programming languages.
•	Apps can leverage the features provided by the Android framework.
8.	User Interface (UI):
•	The visual elements that users interact with.
•	Managed through XML layouts and programmatically in the app code.
•	The UI can include activities, fragments, views, and widgets.
This layered architecture provides a modular and scalable framework for Android, allowing for flexibility, customization, and support for a wide range of devices. Developers can create apps that run on various Android devices, from smartphones and tablets to smart TVs and wearables, thanks to the adaptability of the Android architecture.

Android Core Building Blocks
Android applications are built using a variety of components that work together to create a seamless user experience. The core building blocks of an Android application include:
1.	Activities:
•	An activity represents a single screen with a user interface.
•	Acts as an entry point for user interaction.
•	Multiple activities can be combined to create a complete application.
2.	Services:
•	Services perform background tasks without a user interface.
•	Used for tasks that continue even when the application is not in the foreground, such as playing music or handling network transactions.
3.	Broadcast Receivers:
•	Broadcast receivers respond to system-wide broadcast announcements.
•	Allow applications to respond to events like the completion of a file download or a low battery warning.
4.	Content Providers:
•	Content providers manage and expose a structured set of data to applications.
•	Enable data sharing between applications, making it possible for one app to access and modify the data of another app (with proper permissions).
5.	Fragments:
•	Fragments are modular, reusable components within an activity.
•	Can be combined to create flexible UI designs that adapt to different screen sizes and orientations.
6.	Intent:
•	Intents are messaging objects used to request an action from another app component.
•	They can be explicit (specifying the target component) or implicit (declaring a desired action and letting the system find an appropriate component).
7.	Views and ViewGroups:
•	Views are the UI components that form the building blocks of an Android application.
•	ViewGroups are containers that hold multiple views and define the layout structure.
8.	Layout XML Files:
•	XML files define the layout and appearance of the UI elements.
•	Android developers use XML files to describe the structure of the user interface.
9.	Manifest File:
•	The AndroidManifest.xml file provides essential information about the application to the Android system.
•	Specifies the app's components, permissions, and other crucial details.
10.	Resources:
•	Resources such as images, strings, and layouts are stored separately from the code.
•	This allows for easier localization and customization without modifying the code.
Understanding how these core building blocks interact and utilizing them effectively is key to developing robust and user-friendly Android applications. Each component plays a specific role in the overall structure of an Android app, and developers combine them to create diverse and interactive user experiences.

How to Create An Activity:
1.	Create simple class and extends it with AppCompatActivity.
2.	Override the oncreate() methods (it is the method of activity life-cycle).
3.	Call setContentView(R.layout.layout_name) method.
Lifecycle Of Activity
The Android `Activity` lifecycle describes the various states an `Activity` goes through from its creation to its destruction. Understanding the lifecycle is crucial for managing the behavior of your app and ensuring a smooth user experience. The `Activity` lifecycle methods are called by the system at different points in the activity's existence. Here is an overview of the key lifecycle methods:

1. **onCreate():**
   - Called when the activity is first created.
   - This is where initialization and setup occur.
   - You typically set up the UI elements and initialize variables in this method.

2. **onStart():**
   - Called when the activity becomes visible to the user.
   - At this point, the activity is in the foreground but may not have focus.
   - It's a good place to start animations or refresh data that's displayed to the user.

3. **onResume():**
   - Called when the activity is about to start interacting with the user.
   - This is where you should start anything that consumes resources or perform actions that need to be active while the activity is visible and in focus.
   - For example, register broadcast receivers or acquire resources.

4. **onPause():**
   - Called when the activity is going into the background but is still visible.
   - You should stop or adjust resources that are consuming valuable system resources.
   - Save data that should persist between instances of the activity.

5. **onStop():**
   - Called when the activity is no longer visible to the user.
   - Release resources that might be needed while the activity is not in view.

6. **onRestart():**
   - Called when the activity is restarting after being stopped.
   - This method is followed by `onStart()`.

7. **onDestroy():**
   - Called before the activity is destroyed.
   - Cleanup and release resources here.
   - This method is not always called, as the system may kill the process without calling it in certain situations.

Here's a basic flow of the `Activity` lifecycle:

onCreate() -> onStart() -> onResume() -> (user interacts with the activity) -> onPause() -> onStop() -> (activity is brought back to the foreground) -> onRestart() -> onStart() -> onResume() -> (activity is finished or the app is closed) -> onPause() -> onStop() -> onDestroy()

During the lifecycle transitions, the system might also call methods like `onSaveInstanceState()` and `onRestoreInstanceState()` to help the activity save and restore its state, especially in situations where the system might need to recreate the activity. Understanding these lifecycle methods is crucial for proper resource management and creating a responsive and user-friendly Android app.

Android, layouts
They are used to define the structure and appearance of the user interface (UI) for an app. They are defined using XML files and determine how the different UI elements, such as buttons, text fields, and images, are organized and displayed on the screen. Android supports a variety of layout types to accommodate different design requirements. Here are some commonly used layout types:

 1. LinearLayout:
   - Arranges UI elements in a single column or row.
   - You can specify the orientation as either vertical or horizontal.

   Example:
   ```xml
   <LinearLayout
       xmlns:android="http://schemas.android.com/apk/res/android"
       android:layout_width="match_parent"
       android:layout_height="match_parent"
       android:orientation="vertical">

       <!-- UI elements go here -->

   </LinearLayout>
   ```

 2. RelativeLayout:
   - Positions UI elements relative to each other or the parent container.
   - Allows for flexible and dynamic UI design.

   Example:
   ```xml
   <RelativeLayout
       xmlns:android="http://schemas.android.com/apk/res/android"
       android:layout_width="match_parent"
       android:layout_height="match_parent">

       <!-- UI elements with layout parameters go here -->

   </RelativeLayout>
   ```

3. ConstraintLayout:
   - Similar to RelativeLayout but with a more flexible and powerful constraint-based layout system.
   - Allows you to create complex layouts with a flat view hierarchy.

   Example:
   ```xml
   <androidx.constraintlayout.widget.ConstraintLayout
       xmlns:android="http://schemas.android.com/apk/res/android"
       android:layout_width="match_parent"
       android:layout_height="match_parent">

       <!-- UI elements with constraints go here -->

   </androidx.constraintlayout.widget.ConstraintLayout>
   ```

### 4. **FrameLayout:**
   - A simple layout that acts as a placeholder for a single view.
   - Often used for fragments or as a container for fragments.

   Example:
   ```xml
   <FrameLayout
       xmlns:android="http://schemas.android.com/apk/res/android"
       android:layout_width="match_parent"
       android:layout_height="match_parent">

       <!-- Single UI element goes here -->

   </FrameLayout>
   ```

 5. GridLayout:
   - Arranges UI elements in a grid.
   - Useful for creating forms or tables with rows and columns.

   Example:
   ```xml
   <GridLayout
       xmlns:android="http://schemas.android.com/apk/res/android"
       android:layout_width="match_parent"
       android:layout_height="match_parent"
       android:rowCount="2"
       android:columnCount="2">

       <!-- UI elements with layout parameters go here -->

   </GridLayout>
   ```

These are just a few examples, and Android provides several other layout types to suit different design needs. Additionally, you can nest layouts to create complex and responsive UIs for your Android applications.







Bio

🚀 Passionate App Developer 🌐

👋 Hey there! I'm Deepak Kumar Pathak, a dedicated app developer with a knack for turning ideas into seamless, user-friendly experiences. My journey in the world of technology has been fuelled by a relentless curiosity and a love for creating innovative solutions.

🛠️ Skills:
- Mobile App Development (iOS & Android)
- Frontend Development (React Native, Flutter)
- Backend Development (Node.js, Express, Django)
- Database Design and Optimization
- UI/UX Design Principles


📚 Continuous Learner:
I believe in staying ahead in the fast-paced tech landscape. Currently exploring [current tech or framework you're learning], always looking for opportunities to grow and adapt.

🎓 Education:
BCA: Suresh Gyan Vihar Univerysity,Jaipur

📫 Contact:
Phone No: 8252204757
Feel free to connect with me for collaborations, discussions, or just to geek out about the latest tech trends. Let's build something awesome together! 🚀


📱 Social:
LinkedIn: https://www.linkedin.com/in/deepak-kumar-pathak-388089161/
Twitter: https://twitter.com/DangerG58997195
Instagram: https://www.instagram.com/dpathak001/
GitHub:  

ScreenShots:
       
          

Let's innovate, create, and make a positive impact through technology! 💻✨
