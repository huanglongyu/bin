# Purpose
To improve work efficiency.  
BTW those cmds are all used for android developer.  

# Preparation
Configure those scripts into the environment variables

# How to use
## rebootfake :
just type this cmd, and the process named system server will be killed.

##push :
First, make sure u a at the top of the workspace which stored ur source code  

Second,use mm/mmm to compile ur target  

Third, just type cmd : "push out/........"  

if u pushed framework taget, will occure reboot automatically to make ur taget work.  

It also works for Android5.0

##unpackimg :
* mkdir newDir && cd new Dir  
* unpackimg full-path.img  

output :  
* the dir named basename of img
* the back up full-path.img
* the img after use simg2img

BTW : this do not support for recovery/boot.img and needs root permission

##killTarget :
killTarget systemui/settings

