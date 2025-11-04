<h1>writing a first activity in android studio</h1>

Android app content is split into activities. Each activity is like a webpage that displays a discrete section of the entire app. They can be linked together and this way users can navigate around your app. Activities exist as a layout file along side associated scripts that control interaction.

STEP1:
Setup and launch android studio. See this guide on setting it up.

STEP2:
Set up a new project. Go to File->new ->new project in the option screen that follows choose no activity. Give the project a name, and designate a package name, save location and SDK that matches the device you are using for debugging and language as Java.

STEP3:
Wait for the gradle to compile the files, then go to new->activity->Empty activity Give it a name and match the package name from the previous step.

STEP4:
edit the layout file for activity. This will change the content of your activity found at app->res->layout you can find out more about layouts from here

STEP5:
Add the new activity to the Android Manifest file. the code template looks like this:

<code><activity
android:name=".createAccountActivity"</code>
android:label="@string/app_name"</code>
android:exported="true"></code>
</activity></code>

STEP6:
Add any interactions (buttons, images, animations etc) from the java class folder asociated with the activity look in app->java->PACKAGE_NAME and find the correct package. make sure to ihave the following import structure…

<code>import android.app.Activity;</code>


STEP7:
Launch the app. Press the play button at the top of the screen and as long as the device is attached, it should be targetted with the app and run on the device.

<hr>

TASK1:
Create a hello world android app using your own activity.
