Enhanced-SEEK
=============

The implementation is based on SEEK-for-Android (Secure Element Evaluation Kit for the Android platform) located at https://code.google.com/p/seek-for-android/

Here is the list of enhancements we have made:

  - Improved getAPPCerts() in AccessController.java
  - Implemented Retrieve-All-Rules
  - Fixed synchronization issue when multiple threads attempt to access ARA-M at the same time
