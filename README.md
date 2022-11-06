# chopin-miui13-flasher
MIUI 13 fastboot firmware flasher for POCO X3 GT / REDMI NOTE 10 PRO 5G  
  
HOW TO USE:  
-Extract and copy Android Platform Tools to same directory with *.bat file  
-Create \images\ folder
-Open fastboot rom file with Winrar (or alternate) and copy all contents of the images folder to created images folder  
-Double click to run *.bat file and follow instructions  
  
NOTES:   
-Only works MIUI 13.x roms  
-Device should be bootloader unlocked  
-You can download Android Platform Tools from: https://developer.android.com/studio/releases/platform-tools  
-Predefined setup will wipe your userdata. To prevent this add "::" to before "fastboot flash userdata images\userdata.img" command  
