# Don't Update In the system or ur device will bootloop in recovery mode with a dynamic circle animation.
For [Samsung Smart Switch](https://apps.microsoft.com/detail/9nh4f7j77cpd)
```SWITCH
Simply click Update and wait, device will automatically reboot
```
For [HadesFirm](https://github.com/corsicanu/hadesFirm) & [Odin v3](https://www.odinflash.com/download) 

![image](https://github.com/C-F0x/yet-another-gts10pwifi-tutorial/blob/master/slot.png)
```ODIN
use HadesFirm to download ur firmware
Plug in the cable than long press power button, once screen shuts down, long press vol+ & vol- till Odin Mode.
u can rename *.tar.md5 to *.tar skip MD5 Check.

BL-->BL
AP-->AP
CP-->CP (null for non-sim device)
CSC-->HOME CSC
USERDATA --> NULL

p.s. flash as common if u need a brand new system 
than Start flash.

```
Once device reboot, boot it into Odin Mode again to flash any img on ur demand.

# DON'T BOOT INTO SYSTEM DIRECTLY OR YOU MAY LOST UR DATA

## if u have modified the data partition, e.g multidisabler, modify it again. 


