the chal one apk looked like this when running 


![image](https://github.com/adwait3/sm/assets/148553626/dae446fd-fc6e-488e-b40b-7ed77dd0fdb2)



first i used 

``` frida-ps -U```
to get the process list 


![image](https://github.com/adwait3/sm/assets/148553626/b4d3aa5c-22cc-49df-88bd-a9c47599727b)


then i used 
``` frida-ps -Uai```
 to get 

 
 ![image](https://github.com/adwait3/sm/assets/148553626/966ab8e9-d4bd-471f-9538-c0ef9500326d)


then i used jadx to see the source code of the application 


![image](https://github.com/adwait3/sm/assets/148553626/56fef988-625d-460d-b3b4-bc865e7edb61)

there was a function called chcek and i thought i found the flag but it was encrypted 


![image](https://github.com/adwait3/sm/assets/148553626/61e421de-e5e0-4547-979f-9c9b2aaee34f)

i used jadx to hook the method 

![image](https://github.com/adwait3/sm/assets/148553626/91e63598-f057-42f7-9509-c2017b4e0c10)

now 5 will be passed to check so we will get the desired output as 14 and we can pass that in the application

![image](https://github.com/adwait3/sm/assets/148553626/4d39654e-2b5f-44fc-bc3b-b8a80f9fba0f)

