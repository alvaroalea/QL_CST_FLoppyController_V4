# QL_CST_FLoppyController_V4

A clone of the CST's Floppy Disk Interface for Sinclair QL 
(PCB version 4, ROM version 1.18)

### WARNING: Use good components!

During testing we found that bulk unknow 2N2222 transistor seen to work, but have hard compatibility problems with other boards.  
(hard in the way that kill the other cards)

Using a wellknow source transistor eliminate the incompatibility and work correctly with other passthrough boards. Be aware if you use a external or internal RAM expansion, a Qbide with passtrough or a backplane that allow several board,  

### The Board

This board is the last version of the CST Floppy Disk Interface, there are two main diferences with version 3
* The ROM is scrambled, so read directly from the chip do not provide usefull information.
* It have a more efficient use of the ROM space, and up to 14Kb are used by the ROM, while previous version only have 8Kb of ROM.
* The ROM now support ramdisk 

It use the standar stugart conector, so a plain cable can have up to 2 disk drives, that shall be correctly configured as DS0 and DS1.

It use a WD1770 disc controller, and is expected that will be compatible with WD1772 (not checked), WD1773 is not compatible.

Thanks to Derek_Stewart and techy of qlforum.co.uk for providing the pictures that allow me to capture the schema.

A interactive bill of materials is available here:

https://alvaroalea.github.io/QL_CST_FLoppyController_V4/ibom.html

![My image](qdisk_v4F.png) 

![My image](qdisk_v4B.png) 

