MobileTriage
============

A prototype of an Android app that provides digital forensic tools capabilities. 

Files required for both installation and source code are available under Releases.

Installation guidance:

1. Download and copy the MobileTriage.apk file into the Android device.
2. Modify Android settings to allow installation of application not from Google Play, by going into Settings - Security - and tick the Unknown Sources - Allow installation of apps from sources other than the Play store.
3. Browse to where the .apk file is copied using a file manager, and select the MobileTriage.apk file and follow the instructions.
4. At this stage, the Unknown Sources option can be unticked to maintain device security features.
5. Create a folder manually to store the carved files results --> /storage/sdcard0/Documents/FAT32Output/ (this can be modified in the source code in one of the global variables)
6. An example dataset of Evidence001.dd - 50mb can also be downloaded for testing, this file contains few JPEG picture files wtih EXIF data, some of them were deleted and intentionally corrupted.
7. Confirm that MobileTriage app icon appears in the Android device.

Source code build and compilation guidance:

1. Download and install the complete Android SDK for any platforms (Windows, Mac and Linux) at http://developer.android.com/sdk/index.html
2. Confirm that Eclipse is installed and the default Workspace folder is created.
2. Download and extract the MobileTriage.zip into the Workspace folder that is created after the SDK installation.
3. Expand the tree branch for MobileTriage on the left hand side of the Eclipse Package Explorer.
4. Select Project -- Build All to rebuild the package.
5. Click the Run or Play icon to build and compile the source code after any modifications.

