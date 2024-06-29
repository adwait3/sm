![image](https://github.com/adwait3/sm/assets/148553626/27e5ee0a-32df-4d85-9398-3455d3d05f7c)after loading the apk we see

![image](https://github.com/adwait3/sm/assets/148553626/9cd2cabe-209f-42ea-ac5f-caeea41d60ee)


we find a method get flag and open it 

![image](https://github.com/adwait3/sm/assets/148553626/3dbefc38-1a7f-4992-b275-caea331251d0)


we can also find our package name 

``` com.ad2001.frida0x2 ```

frida script 

```

Java.perform(function() {

    var a = Java.use("com.ad2001.frida0x2.MainActivity");
    a.get_flag(4919); 

})
```

```
 frida -U -f com.ad2001.frida0x2 -l ./simple.js

```
![image](https://github.com/adwait3/sm/assets/148553626/696c17f3-9b8d-4c56-ab0a-98591d6e1b77)

