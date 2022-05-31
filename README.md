# Let-s Begin - Vulnerable APK

This apk was built to practice some of the vulnerabilities on the Android Platform. 

## Getting started

As a part of Optiv's Source Zero Con., I have built this APK which we are going to present as a workshop in the conference 

## Tools You Need During the Workshop
    - Android Debug Bridge (adb)
    - keytool (to create a self signed certifcates)
    - jarsiger (to sign the apk)
    - apktool (to decompile/recompile) apk
    - d2j-dex2jar (Converts your apk to jar)
    - JD-GUI (Loads the JAR file and allow you the read the decompiled source code)
    - You can either use the actual android device to load the app or genymotion as well. 

## APK Details

The APK contains one basic terminal which you can use the run the underline Android OS commands if you're installing it on any rooted device. 
The next activity of APK loads a vulnerabilities such as you're allowed to run JS to triggered Cross-Site Scripting OR using a vulnerable SQL Injection payload you can extract the DB information.

## Author

Vandan Pathak - Senior Security Consultant, Optiv Canada Inc.
