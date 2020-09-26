# FCM-PushNotification-Using-Device-Tokens

### Description
  You can Send FCM Push Notifications using Device Tokens which you get from your Database.

### Usage of the above project App
  * In the beginning of the app you have login using Your Email & Password credentials for Authentication in Firebase.
  * After that it Stores an Unique User Id for you in Firebase-Realtime database along with the Your Device Token.(Like the below Image Shown).
  * In the App you have to enter any one of the user Id & Any Title & Any Message.
  * And then press the send button.
  * Now the backend Functions get that userId's Token from the firebase and Send Notification to that Token(Device).
