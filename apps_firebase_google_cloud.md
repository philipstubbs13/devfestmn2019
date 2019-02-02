# Build and scale mobile apps with Firebase and Google Cloud

* Presenter
  * Doug Stevenson
  * February 2, 2019
  * @CodingDoug
* bit.ly/what-is-firebase
* Firebase Authentication
  * Restrict who can read and write what data.
  * Give each user a personal space to work with.
  * Perform audit trails of user activity.
* Cloud Firestore
  * Cloud store, nosql, realtime database.
  * Collection - organizationl tool, contains documents.
  * Each document needs a unique id.
  * Each document has fields on it.
  * Massively scalable
  * Queries scale with the size of the result set.
* Cloud Storage for Firebase
  * Exabyte scale
    * 1 with 18 zeros after it (1 x 10^18)
    * 1 million terabytes
  * Secure
  * Robust
* Cloud Speech API
* Cloud Translation API
* Cloud Functions
  * Deploy code that responds to events.
  * Fully managed node.js environment.
  * Auto scales up and down, pay only for use
  * Secure
  * Cloud Functions Trigger
    * HTTP endpoint
    * Google Cloud Storage
  * Additional Firebase Triggers
    * Firestore
    * Authentication
    * Crashlytics
    * Remote Config
    * Realtime Database
    * Google Analtyics
  * <https://devfest-mn-demo.firebaseapp.com/>
  * <https://github.com/CodingDoug/universal-translator>