<h1 align="center">
    <br>
    TikTok Flutter
</h1>
<h4 align="center">
 Clone of TikTok with Flutter and Firebase.
</h4>

<br/>
-TikTok UI                                 
-Swipe Videos                                                            
-Dynamic Video Data Source                                                                  
-User Data (Name, Image)  
-Animations(Image rotation)  

## Libraries
-video_player.   
-cloud_firestore:  
-cached_network_image

## Installation

1.-Clone or download this repository 

```bash
git clone https://github.com/LinSays/Tiktok-builtby-Flutter.git
```

2.-Config your Firebase instance and insert the google-service.json in android/app/ or ios/Runner

3.-Config flutter project : 

```bash
flutter pub get
```

## Database

The app obtains the data from Firestore and Firebase Storage.

You can upload your videos to Firebase Storage or any site you want, you only need the link of the source, then configure the archive lib/data/demo_data.dart with the list of your videos, this data going to be automatically saved in your Firestore instance.

## TODO

-Likes.   
-Comments.   
-System of User (Register, Login, Profile Screen).   
-Upload Videos from the app


## Changelog

19/06/2020 
- Realtime Database To Firestore
- caroulsel_slider To PageView 

21/06/2020
- Bloc Pattern
- VideoManager
- Performace Improvements.

22/07/2020
- Change Bloc to Locator with GetIt 
- Solved problems with iOS 
- Better UI
- Screens Added
- Clean Code
- Videos from file
- Performace Improvements.

