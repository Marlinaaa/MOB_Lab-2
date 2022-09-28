# MOB_Lab-2
# 2.1
1. What changes are made when you add a second Activity to your app by choosing File > New > Activity and an Activity template? Choose one:
->**The second Activity is added as a Java class, the XML layout file is created, and the AndroidManifest.xml file is changed to declare a second Activity.**


2. What happens if you remove the android:parentActivityName and the <meta-data> elements from the second Activity declaration in the AndroidManifest.xml file? Choose one:
->**The second Activity no longer appears when you try to start it with an explicit Intent.**

  
3. Which constructor method do you use to create a new explicit Intent? Choose one:
->**new Intent(Context context, Class<?> class)**


4. In the HelloToast app homework, how do you add the current value of the count to the Intent? Choose one:
->**As an Intent action**


5. In the HelloToast app homework, how do you display the current count in the second "Hello" Activity? Choose one:

Get the Intent that the Activity was launched with.
Get the current count value out of the Intent.
Update the TextView for the count.
->**All of the above.**


**#2.2**

1. If you run the homework app before implementing onSaveInstanceState(), what happens if you rotate the device? Choose one:
-> **The counter is reset to 0, and the EditText no longer contains the text you entered.**


2. What Activity lifecycle methods are called when a device-configuration change (such as rotation) occurs? Choose one:
-> **Android shuts down your Activity by calling onPause(), onStop(), and onDestroy(), and then starts it over again, calling onCreate(), onStart(), and onResume().**


3. When in the Activity lifecycle is onSaveInstanceState() called? Choose one:
-> **onSaveInstanceState() is called before the onStop() method.**


4. Which Activity lifecycle methods are best to use for saving data before the Activity is finished or destroyed? Choose one:
-> **onPause() or onStop()**

**#2.3**

1. Which constructor method do you use to create an implicit Intent to launch a camera app?
-> **new Intent(String action)**


2. When you create an implicit Intent object, which of the following is true?

Don't specify the specific Activity or other component to launch.
Add an Intent action or Intent categories (or both).
Resolve the Intent with the system before calling startActivity() or startActivityforResult().
-> **All of the above.**


3. Which Intent action do you use to take a picture with a camera app?
-> **Intent takePicture = new Intent(MediaStore.ACTION_IMAGE_CAPTURE);**
