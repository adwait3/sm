![image](https://github.com/adwait3/sm/assets/148553626/012cd282-4b98-4d68-8392-1a97c6864513)the chal starts like this 

![image](https://github.com/adwait3/sm/assets/148553626/72f04ce7-c012-4c8f-b712-cb3edc4088d7)


using jadx 

![image](https://github.com/adwait3/sm/assets/148553626/c404a823-99df-4312-8f02-9223e20d4a0c)


we find an interesting class check 

![image](https://github.com/adwait3/sm/assets/148553626/18fc3d7f-5d32-4c28-8fc9-029a142c8c9c)


solve script 
```
Java.perform(function (){

    var a = Java.use("com.ad2001.frida0x3.Checker");
    a.code.value = 512;

})
```

using this we get the flag 

![Uploading image.png…]()


