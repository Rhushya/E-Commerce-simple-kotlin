# E-Commerce Simple Kotlin 🛍

Shopping App is a fictional shopping application built with Kotlin and Jetpack Compose. To access the application, an account needs to be created. The main screen displays various products. Products can be filtered based on categories. In the search screen, you can search for any desired product. You can add your desired product to favorites and quickly access it from the favorites screen. In the profile screen, you can update your username, phone number, address, profile picture, and date of birth.

The application uses [Firebase Authentication](https://firebase.google.com/docs/auth) for user verification. Additionally, a phone number can be added. When adding a phone number, a verification code is send to the added phone number. After entering the received code in the application, the phone number gets associated with the account. User profile images are stored using [Firebase Storage](https://firebase.google.com/docs/storage). The user's address and date of birth information are stored using [Cloud Firestore](https://firebase.google.com/docs/firestore).

A new Firebase application has been created to store user addresses and date of birth information using Cloud Firestore. To learn how multiple Firebase applications are used within a project, [Configure multiple projects in your application.](https://firebase.google.com/docs/projects/multiprojects?hl=en#use_multiple_projects_in_your_application)

### <b>Setting up the second Firebase application</b> 🛠

Enter the required information in the local.properties file as specified in the provided link.

Creating the instance for the second Firebase application. (di/AppModule)
 
## Tech Stack 📚

* [Android Architecture Components](https://developer.android.com/topic/architecture)
    * [Navigation](https://developer.android.com/guide/navigation)
    * [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel)
    * [Repository](https://developer.android.com/topic/architecture/data-layer?hl=en)
* [Hilt](https://developer.android.com/training/dependency-injection/hilt-android)
* [Room](https://developer.android.com/training/data-storage/room)
* [Retrofit](https://github.com/square/retrofit)
* [Coil](https://github.com/coil-kt/coil)
* [Firebase Auth](https://firebase.google.com/docs/auth)
* [Firebase Storage](https://firebase.google.com/docs/storage?hl=en)
* [Firebase Firestore](https://firebase.google.com/docs/firestore?hl=en)
* [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging)
* [Image Cropper](https://github.com/mr0xf00/easycrop)

## Outputs 🖼

Screenshots will be available soon.

## Architecture 🏗
The app uses MVVM [Model-View-ViewModel] architecture to have a unidirectional flow of data, separation of concern, testability, and a lot more.

![mvvm](https://user-images.githubusercontent.com/73544434/197416569-d42a6bbe-126e-4776-9c8f-2791925f738c.png)

## API 📦
[Fake store API](https://fakestoreapi.com/)

## Developer 👨‍💻
**Rhushya**
- GitHub: [@Rhushya](https://github.com/Rhushya)
- Repository: [E-Commerce-simple-kotlin](https://github.com/Rhushya/E-Commerce-simple-kotlin)

