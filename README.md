___
Thank you for  @mattytrog form gbatemp.net . this project is base of SX gear and mattytrog's code.
___
# sd_bin_reload_RCM-X86  
 this is a project to reload any payload.bin form the SD card.
 
you just need to do this :

* find your dongle Version and download the "SD_bin_reload" directory.   
   [RCM-X86 version](https://github.com/euclala/RCM-X86)
* update your RCM-X86 dongle by the  .UF2  (form  "SD_bin_reload" ).     
* copy the "x86.load" to the SD card root  directory  (form "SD_bin_reload" )
* payload.bin  (any .bin files like: hekate_ctcaer_4.2.bin, ReiNX.bin,TXos.bin,RajNX.bin,)  
  copy it to the SD card root  directory, and rename it to "payload.bin"  
* done

after doing that  you SD card directory will like this:
  ![sd root directory](https://github.com/euclala/sd_bin_reload_RCM-X86/blob/master/jpg/sd_root.jpg)

___
# sd_bin_reload_RCM-X86  
 本项目可以通过重载功能,重新引导存放在你的switch SD卡上的任意payload.bin文件.  
 通过本功能你可以避免反复修改注入器的固件.
 
步骤:

* 找到你的注入器版本,进入目录"SD_bin_reload".  
  [RCM-X86 version](https://github.com/euclala/RCM-X86)
*  使用UF2文件升级的的注入器 (文件位于  "SD_bin_reload"内 ).     
*  复制"x86.load" 到你swithc的SD储存卡根目录   (文件位于  "SD_bin_reload"内 ).
*  payload.bin  (任何网上下载的payload.bin都可以,比如大气,rei,raj,等等)  
   复制到SD储存卡根目录,并且把名字改成 "payload.bin"
*  完成,插入注入器即可引导SD卡上的bin文件

完成上面操作时,你的SD储存卡应该是类似下面这个图:
  ![sd root directory](https://github.com/euclala/sd_bin_reload_RCM-X86/blob/master/jpg/sd_root.jpg)
