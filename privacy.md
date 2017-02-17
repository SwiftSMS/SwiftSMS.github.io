# SwiftSMS Privacy Policy

Due to the nature of SwiftSMS the application must transmit some data from your device to the selected network operators website.  However we have taken great care to ensure that SwiftSMS will only ever transmit data which is absolutely required for the operation of the application and the data is always transmitted over TLS encrypted HTTPS connections.
The data which must be transmitted is,
* The phone number of the contacts which you are texting.
* The message which you are sending.
* Your username & password for the selected operator.

SwiftSMS will never transmit your data to any other parties.

## Explanation of permissions

* android.permission.INTERNET
  
  Required to connect to the Network Providers website when sending an SMS.
  
* android.permission.READ_CONTACTS

  Required to provide Contact Suggestions from your phones contacts list.
  
* android.permission.WRITE_SMS
  
  Required to enter a sent SMS into your sent messages.
  
* android.permission.VIBRATE
  
  Required to help notify of a SMS send failure.
  
* android.permission.READ_SMS
  
  Required to access the SMS database, only used for writing sent text messages.
