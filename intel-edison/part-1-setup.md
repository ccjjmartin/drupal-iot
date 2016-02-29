#### Part 1: Setup the Intel Edison Board

##### General Information on the board:
https://software.intel.com/en-us/iot/hardware/edison

##### Getting started guide:
- https://software.intel.com/en-us/iot/library/edison-getting-started

##### Downloads:
https://software.intel.com/en-us/iot/hardware/edison/downloads

##### Setup the edison:
- The installer was broken as of writing this readme
- Because my board didn't have enough space.  The latest version 
was Intel Edison® Board Firmware Software Release 2.1.  This release
requries 1.06GB of space but if you right click on the mounted volume
named Edison you might see like me that you only have 805MB of space.
The solution was to download the Release 2.0 Yocto* complete image.
- I also reformated my partition using the following command:
- WARNING: The next command if used wrong can wipe your computer.
- WARNING: This is a destructive command adjust this command (XXX) for your disk number found by using `diskutil list`
- Then with your disk ("Edison") reformat with `diskutil partitionDisk /dev/diskXXX 1 MBRFormat "MS-DOS FAT16" "EDISON" 805M`
- See manual install steps for macs at the next URL:
- http://www.intel.com/content/www/us/en/support/boards-and-kits/000005801.html
- The manual forgets also to tell you after you do the manual copy of the files to restart the edison
- After the restart you can then connect to the serial port
- Connecting via serial: https://software.intel.com/en-us/get-started-edison-osx-step3
 
##### IDEs:
- Arduino: https://www.arduino.cc/en/Main/Software
- Intel IoT IDE: https://software.intel.com/sites/landingpage/iotdk/osx-development-kit.html

##### Sources:
- Blog on FAT-16 partition: http://www.liquidx.net/blog/2007/05/26/format-partition-as-fat16-on-mac-osx/

