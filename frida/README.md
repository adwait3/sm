open windows powershell and navigate to the directory containing your adb .
use 
```
.\adb shell
su
setenforce 0
cd data/local/tmp/frida-server-16.3.3-android-x86_64
./frida-server-16.3.3-android-x86_64 &
```

then open another terminal and use frida
