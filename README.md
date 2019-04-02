# Coral Dev Board Google Edge TPU - Beginner Tutorial  
 
 > **Note:** This tutorial uses VirtualBox linux.  

## Components require:

 1. [Coral Dev Board](https://coral.withgoogle.com/products/dev-board/) (quad Cortex-A53, Cortex-M4F)   
 2. Linux computer  
 3. 1 USB-A to USB-microB  
 4. 2 USB-A to USB-c cables  
 4. Ethernet cable (Optional)  
  
## Getting started:

If you are using it for first time and haven't yet set up `Mendel System Image` then follow this [link](https://coral.withgoogle.com/tutorials/devboard/)  

 > **Note:** If you are using Linux on Virtual machine than while following steps provided in above link you may encounter error in `screen /dev/ttyUSB0 115200` . to get rid of that error you have to install [minicom](http://processors.wiki.ti.com/index.php/Setting_up_Minicom_in_Ubuntu) and follow steps. Replace `/dev/ttyS0` to `/dev/ttyUSB0`.  

## Access GPIO in `Kernel Space`:

![alt text](http://linuxgizmos.com/files/google_coral_devboard_pinout.jpg "Dev Board GPIO pinout")

