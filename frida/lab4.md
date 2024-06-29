the aplication after loading 

![image](https://github.com/adwait3/sm/assets/148553626/7c403e3b-d532-4e9a-901b-c0328222962b)

in jadx 

![image](https://github.com/adwait3/sm/assets/148553626/a6f005fe-c8df-4ed8-96a0-2a6de786a917)

solve script 

```
Java.perform(function() {

  var check = Java.use("com.ad2001.frida0x4.Check");
  var check_obj = check.$new(); 
  var res = check_obj.get_flag(1337); `
  console.log("FLAG " + res);

})
```

this gives us the flag 

![image](https://github.com/adwait3/sm/assets/148553626/87fce1fb-f54a-41ca-bf1c-b50843e55d1b)

