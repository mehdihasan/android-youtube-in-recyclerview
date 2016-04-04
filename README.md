# android_youTubeInRecyclerView
Showing and playing Youtube videos in RecyclerView.

1. First we need to get the SHA-1 fingerprint on your machine using java keytool. Execute the below command in cmd/terminal to get the SHA-1 fingerprint.

On Windows
keytool -list -v -keystore "%USERPROFILE%\.android\debug.keystore" -alias androiddebugkey -storepass android -keypass android

On Linux or Mac
keytool -list -v -keystore ~/.android/debug.keystore -alias androiddebugkey -storepass android -keypass android

2. Go to Google Developer Console and select or create a new project. (https://console.developers.google.com/)

3. turn the status ON for YouTube Data API v3.

4. On the left sidebar, select Credentials and Create new key under Public API acess.

5. When popup comes asking you to choose platform, select Android Key.

6. Paste the SHA-1 key and your project’s package name.

7. Click on create. Now you should see the API KEY on the dashboard.
