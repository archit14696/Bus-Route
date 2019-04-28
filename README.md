# Bus-Route
An app to find the bus transit route according to source and destination.
# Getting Started
Clone or download the project in your system. 


### Prerequisites
Android Studio

### Installation Steps
* Before installing Android SDK, you need to install Java Development Kit (JDK).
* For Windows, Goto "Android Developer" @ https://developer.android.com/index.html ⇒ Select "Get Android Studio" ⇒ "Download Android Studio 3.x.x for Windows (683MB)", e.g., android-studio-ide-171.xxxxxxx-windows.exe.
  Run the downloaded installer ⇒ In "Choose Components", select "Android Studio" and "Android Virtual Device". ⇒ Follow the on-screen instruction and accept the defaults to complete the installation.
* For Mac OS X, Goto "Android Developer" @ https://developer.android.com/index.html ⇒ Select "Get Android Studio" ⇒ "Download Android Studio 3.x.x for Mac (738MB)", e.g., android-studio-ide-171.xxxxxxx-mac.dmg.
Launch the downloaded ".dmg" installation file. Select "Custom" (instead of "Standard"), under the SDK Components Setup, select ALL, including "Performance (Intel HAXM)" and "Android Virtual Device (731MB)".
Drag and drop Android Studio into the "Applications" folder.


### Running the application

* Import the file downloaded from github in the android studio.
* Build the project from the menu bar.
* Set the desired virtual device having API>24 from the AVD Manager from tools or select the device connected via USB by turning the USB debugging on.
* Run the application while the APK is installed in your device.


### Steps to use the application
* Press the GO button
* After the loading of the map and your location long click the map to set the start location. A green marker appears which shows the start point
* Long click on another location on the map to set the red marker to set the destination point
* The transit route is shown using the polyline
