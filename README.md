PayPal-iOS-SDK-Sample-Swift
===========================

A sample implementation of the PayPal iOS SDK in Swift
Before using this app one must install the pod for paypal iOS SDK inorder to access the header files.
To install pod to this project

1. open your terminal change the path to the path where the project is located
2. Type pod init
3. Type pod -a Xcode Podfile
Then a pod file will be opened with a txt file uncomment the platform insert

pod "PayPal-iOS-SDK"

Note: if you are using Xcode 6.2 you need to install older version of the sdk so do this instead

pod "PayPal-iOS-SDK" "~>2.10.2"

Then save and close this file and go back to the reminal type

pod install

Warning:
----
There might be still some issues running this sample due to the beta nature of both iOS 8 and Xcode 6 at the moment.
