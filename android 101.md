# main points 
>1. apk file contains a .dex file, which contains binary Dalvik bytecode. Smali is an assembly language that runs on Dalvik VM, which is Android's JVM.
>2. dalvik's bytecode, registers are always 32 bits, and can hold any type of value. 2 registers are used to hold 64 bit types (Long and Double).
>3. number of registers are stored in methods. a method has 2 arguments, and 5 registers (v0-v4), the arguments would be placed into the last 2 registers - v3 and v4.
>4. learned about adb and how to use it on vm and use a phone via usb debugging.

### application structure 
```
AndroidManifest.xml: the manifest file in binary XML format.

classes.dex: application code compiled in the dex format.

resources.arsc: file containing precompiled application resources, in binary XML.

res/: folder containing resources not compiled into resources.arsc

assets/: optional folder containing applications assets, which can be retrieved by AssetManager.

lib/: optional folder containing compiled code - i.e. native code libraries.

META-INF/: folder containing the MANIFEST.MF file, which stores meta data about the contents of the JAR. which sometimes will be store in a folder named original.The signature of the APK is also stored in this folder.
```


# answers


## task 4

What is the package name of the Black Hat Europe?

```com.swapcard.apps.android.blackhat```


## task 5 

Tool for convert dex file to smali code?

```d2j-dex2smali```

Which is the option for build apps with apktool?

```b```

What is the apk path of Black Hat Europe?

```/data/app/com.swapcard.apps.android.blackhat-1/base.apk```


Command for extract apk of Back Hat Europe?

`adb pull /data/app/com.swapcard.apps.android.blackhat-1/base.apk`


## task 6

What is the name of the firebase instance in the app Black Hat Europe?

```swapcard-android-app-2014 ```

Android-InsecureBankv2 debug realease, check this and what activity is not Protected.

```com.android.insecurebankv2.ChangePassword```

what is the malicious permissions in the app Android-InsecureBankv2?

```android.permission.SEND_SMS```

