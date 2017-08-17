# learn-cordova

Install dependencies manually
If you choose not to install one or more dependencies with the extension, you can install them later manually.

You can install the dependencies in any order, except for Java. You must install and configure Java before you install the Android SDK. Read the following information and use these links to install dependencies manually.

Joyent Node.js

We recommend installing the x86 version of Node.js. Before installing this software, read about safely installing Node.js.

Google Chrome

Git Command Line Tools

When you install Git command line tools, select the option that adds Git to your command prompt path.

Caution: Git command line tools 1.9.5 are installed by default. Unexpected failures may occur if you install a version prior to 1.9.0.
Apache Ant

Download and extract Ant to a location like C:/ant-1.x.x
Set the ANT_HOME environment variable to point to the preceding location.
Add %ANT_HOME%\bin to the system path.
Note: If you need to set this environment variable manually, see Override system environment variables.
32-bit Oracle Java 7

Set the JAVA_HOME environment variable to C:/Program Files/Java/jdk1.7.0_55
Add this to the system path: %JAVA_HOME%\bin
To avoid out of memory issues, set a *JAVA_OPTIONS environment variable with at least -Xmx512M in it.
Note: If you need to set this environment variable manually, see Override system environment variables.
Android SDK with the following SDK packages:

Android SDK Tools (latest version) * Android SDK Platform-tools (latest version)
Android SDK Build-tools (19.1, 19.0.3, and 21)
Android 5.0 (API level 21) with the following packages:

SDK Platform
If you want to use the Google Android Emulator to emulate a 5.0.x device:
ARM EABI v7a System Image
Intel x86 Atom System Image
Google APIs (x86 System Image)
Google APIs (ARM System Image)
If you want to use Cordova 5.0.0 or later:
Android 5.1.x (API level 22) with the following packages: SDK platform
The following illustration shows the minimum required packages in the Android SDK Manager.

Cordova_SDK_Android_Packages
Set the ADT_HOME environment variable to the SDK installation location.

Add this to the system path: %ADT_HOME%\tools;%ADT_HOME%\platform-tools

If you need to set this environment variable manually, see Override system environment variables.

Tip: If you install the Android SDK to its default location on Windows, it gets installed to C:\Program Files (x86)\Android\android-sdk.
If you want to use the Google Android Emulator to emulate a 5.1.x device:

ARM EABI v7a System Image
Intel x86 Atom System Image
Google APIs (x86 System Image)
Google APIs (ARM System Image)
Apple iTunes (x86, x64)
WebSocket4Net (required if you’re developing your app on Windows 7)
Download WebSocket4Net(0.9).Binaries.zip from CodePlex.
Unzip the binaries and then unblock net45\Release\WebSocket4Net.dll. To unblock the DLL, open the file Properties for the DLL and choose Unblock in the General tab (at the bottom of the dialog box).
After you unblock the DLL, copy net45\Release\WebSocket4Net.dll into the %ProgramFiles(x86)%\Microsoft Visual Studio 14.0\Common7\IDE\CommonExtensions\Microsoft\WebClient\Diagnostics\ToolWindows folder on your computer.
