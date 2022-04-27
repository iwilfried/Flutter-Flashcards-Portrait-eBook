## Set-Up 

?> What’s Flutter?  

<p>Developed by Google, Flutter is a mobile app SDK, which allows developers to develop high-quality native interfaces for iOS, Android, Web, macOS, and Linux devices using a single codebase. It allows developers to write a code once and use it on different software devices.</p> 

Flutter is a free and open-source framework. The amazing features of Flutter enhance the mobile app development experiences.

Therefore, Flutter is the best choice for every startup.


### Minimum Requirements

- Operating Systems: Windows 7 SP1 or later (64-bit)
- Disk Space: At least 400 MB.
- Tools: Flutter depends on these tools being available in your environment.
- Windows PowerShell 5.0 or newer (this is pre-installed with Windows 10)
- Git For Windows

### Installing Chocolatey

?> On windows, the easiest way to install Flutter is via the package manager <strong>Chocolatey</strong>.  
<p>With PowerShell, you must ensure Get-ExecutionPolicy is not Restricted.</br>
Run the following command in Windows Powershell</p>

```
C:\>Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

<p>If you don't see any errors, you are ready to use Chocolatey!</p>

> C:\> **choco**

<pre><i>Chocolatey v1.1.0    
Please run 'choco -?' or 'choco <command> -?' for help menu.</i></pre></br> 

`With Chocolatey on your machine, you simply have to run:`


> C:\> **choco install flutter**

<br>

<div align=center>
<img src="./img/Flutter.png"/>
</div>
</br>


> C:\> **flutter doctor**  

<p>With the execution of this command, it will check your environment and display the Flutter installation status. Find out the below results for any additional applications you are required to install or further tasks to complement.</p>

    
### Develop for Android Devices  
Download the Android Studio and install it.   

This installs the latest version of  

-  Android SDK, 
-  Android SDK Platform-Tools, 
-  and Android SDK Build-Tools,   
  
  which are essential while developing a Flutter app for the Android system.

### Set Up SDK Manager

Open Android Studio > More Actions> SDK Manager >   

<div align=left>
<img width="480" src="./img/sdkmanager.png"/>
</div>

Check out you have the latest SDK Platform 

<div align=left>
<img width="480" src="./img/sdkplatform.png"/>
</div>  

check the neccessary tools  

<div align=left>
<img width="480" src="./img/sdktools.png"/>
</div>  

### Create Virtual Device

Open Android Studio > More Actions> SDK Manager >   

<div align=left>
<img width="480" src="./img/VDM.png"/>
</div>  

Select a device where you want to simulate your app on...  

<div align=left>
<img width="480" src="./img/DD.png"/>
</div>  

If you do a final check and get all ticks  

> C:\> **flutter doctor**  

Doctor summary (to see all details, run flutter doctor -v):
[√] Flutter (Channel stable, 2.10.5, on Microsoft Windows [Version 10.0.22000.613], locale de-DE)
[√] Android toolchain - develop for Android devices (Android SDK version 32.1.0-rc1)
[√] Chrome - develop for the web
[√] Visual Studio - develop for Windows (Visual Studio Community 2022 17.1.0)
[√] Android Studio (version 2021.1)
[√] VS Code (version 1.66.2)
[√] Connected device (3 available)
[√] HTTP Host Availability

• No issues found!


Tadda! Now, you are one step closer to becoming a Flutter developer.  

Good luck in your development journey!

## Create App

1. Inside your VS Code editor, invoke View > Command Palette. Type “flutter”, and select the Flutter: New Project. Then select Application and give it location.
    
    ![image](https://user-images.githubusercontent.com/42006848/165591439-950dae60-1984-4fad-b650-e7165fce20a9.png)
    
2. After selecting the project location, give your application a name and press `Enter`
    
    ![image](https://user-images.githubusercontent.com/42006848/165591559-8f93a641-ac2c-480e-bc0c-9a0b498e49d8.png)
    
The above steps create a Flutter project directory that contains a simple demo app.

## VS Code Set-Up

- Install Flutter VS Code extension which adds support for effectively editing, refactoring, running, and reloading Flutter mobile apps. It depends on (and will automatically install) the Dart extension for support for the Dart programming language.

![image](https://user-images.githubusercontent.com/42006848/165592755-f63c8b55-efe5-4093-a9ab-0f719a91e902.png)

