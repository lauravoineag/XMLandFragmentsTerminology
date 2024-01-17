# XML and Fragments Terminology

[Source](https://developer.android.com/codelabs/build-your-first-android-app-kotlin#0![image](https://github.com/lauravoineag/XMLandFragmentsTerminology/assets/77536595/185065b8-2840-4703-bdd2-4390dd4877bd)
)
[Source 2](https://developer.android.com/codelabs/basic-android-kotlin-training-xml-layouts?hl=es-419#2)

## XML 
XML stands for eXtensible Markup Language, which is a way of describing data using a text-based document. 
The UI of an Android app is compiled as a hierarchy containing components (widgets) and the on-screen layouts of those components. Keep in mind that these layouts are UI components themselves.
<img width="640" alt="image" src="https://github.com/lauravoineag/XMLandFragmentsTerminology/assets/77536595/fbec8915-ac04-41f1-8fe2-cc220c4021c8">
<img width="814" alt="image" src="https://github.com/lauravoineag/XMLandFragmentsTerminology/assets/77536595/c90a83bb-af75-4417-9d75-775ec7cba1d9">


## Fragment
Each visible fragment in an Android app has a layout that defines the user interface for the fragment. Android Studio has a layout editor where you can create and define layouts.

<img width="665" alt="image" src="https://github.com/lauravoineag/XMLandFragmentsTerminology/assets/77536595/3e46e32e-afdc-4813-800d-ba75e9a0f34c">
<img width="665" alt="image" src="https://github.com/lauravoineag/XMLandFragmentsTerminology/assets/77536595/d79bde9c-c4f5-4ab1-bd68-9996ba469bb7">

## Fragment Views and Constraints

<img width="632" alt="image" src="https://github.com/lauravoineag/XMLandFragmentsTerminology/assets/77536595/6df81bc3-f02c-4361-a9a1-7c2dd7078ec7">

<img width="606" alt="image" src="https://github.com/lauravoineag/XMLandFragmentsTerminology/assets/77536595/95356d26-66a8-4572-9568-f23d3a05b488">


## Fragment Colours:
<img width="665" alt="image" src="https://github.com/lauravoineag/XMLandFragmentsTerminology/assets/77536595/2c2c8ddf-4eb8-4e54-a1b1-7a75260bc98c">

**com.example.myfirstapp** (or the domain name you have specified): This folder contains the Kotlin source code files for your app.

**com.example.myfirstapp (androidTest)**: This folder is where you would put your instrumented tests, which are tests that run on an Android device. It starts out with a skeleton test file.

**com.example.myfirstapp (test)**: This folder is where you would put your unit tests. Unit tests don't need an Android device to run. It starts out with a skeleton unit test file. 3. Expand the res folder. This folder contains all the resources for your app, including images, layout files, strings, icons, and styling. It includes these subfolders:

**drawable**: All your app's images will be stored in this folder.

**layout**: This folder contains the UI layout files for your activities. Currently, your app has one activity that has a layout file called activity_main.xml. It also contains content_main.xml, fragment_first.xml, and fragment_second.xml.

**menu**: This folder contains XML files describing any menus in your app.

**mipmap**: This folder contains the launcher icons for your app.

navigation: This folder contains the navigation graph, which tells Android Studio how to navigate between different parts of your application.
**values**: Contains resources, such as strings and colors, used in your app.

![image](https://github.com/lauravoineag/XMLandFragmentsTerminology/assets/77536595/8d313112-17ed-4580-9b25-1a43b05d702e)

When you run the app you see a floating action button with an email icon. If you tap that button, you'll see it has been set up to briefly show a message at the bottom of the screen. 
This message space is called a snackbar, and it's one of several ways to notify users of your app with brief information.


<img width="631" alt="image" src="https://github.com/lauravoineag/XMLandFragmentsTerminology/assets/77536595/a6d71284-59ff-4d9c-8f96-66fe584ba56a">

