# SysCache

How to package " android.content.pm package " inside aidl folder ?

Android Studio

    1.  Right click on your project New > Folder > AIDL Folder
    2.  Press Finish
    3.  Right click on aidl folder New > Package
    4.  Insert android.content.pm and press OK
    5.  Download IPackageStatsObserver.aidl
    6.  Copy the aidl file inside the android.content.pm package
    7.  Build > Rebuild Project
    
Eclipse

   1. Right click on src folder New > Package
   2. Insert android.content.pm
   3. Press Finish
   4. Download IPackageStatsObserver.aidl
   5. Copy the aidl file inside the android.content.pm package
   6. Select class where totalCacheSize is then Source > Organize Imports
   
How to add  Add android-processes-1.0.9.aar file
   1. Add a .aar file in my libs folder.
   2. Use "New Module" option under File menu.
   3. Import the .aar file.
   4. Build gradle and compile the project.
