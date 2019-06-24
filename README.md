# PaPer_DJ-PS3-Hacks

PS3 Hacks, Info & Tools (CFW & PS3HEN for SuperSlims & nonCFW models)
-------------------------------------------------------------

* PS3HEN PS3 Exploit for SuperSlims & nonCFW models
  > https://www.psx-place.com/threads/ps3hen-a-homebrew-enabler-more-for-superslim-all-noncfw-ps3-consoles.23817/
  > https://www.psx-place.com/threads/update-ps3hen-v2-1-1-view-latest-changes-to-the-ps3-exploit-for-superslims-noncfw-models.23955/
  > https://www.psx-place.com/threads/tutorial-ps3hen-the-great-ps3-hen-all-in-one-guide.24369/

* PS3 REBUG CUSTOM FIRMWARE (CFW)
  > https://rebug.me/

* PS3 HOMEBREW RESOURCES
  > https://store.brewology.com/homebrew.php?lang=&orderby=Release%20Date
  
  > https://ps3.brewology.com/

* PS3 REDDIT RESOURCES
  > https://www.reddit.com/r/ps3hacks/

* PSX-PLACE RESOURCES
  > https://www.psx-place.com/tags/ps3-hacks/

* PSX HACKS RESOURCES
  > https://www.psxhax.com/forums/ps3-cfw-and-hacks.45/
  
* PS3 HACK 4.82_OFW TO 4.82_CFW
  > https://www.psx-place.com/threads/ps3xploit-tools-v2-0-improved-flash-writers-dumpers-even-easier-to-install-cfw-on-4-82-ofw.16139/
  
* PS3 HACK 4.84_HFW TO 4.84_CFW
  > https://www.psx-place.com/threads/update-ps3-hfw-hybrid-firmware-4-84-2-ps3xploit-han-flash-tools-restored-for-4-84-ofw-users.23094/
  
  > http://ps3xploit.com/hfw/release/ps3_tools-v3.0-HAN484_HFW_release_PS3XPloit.zip
  
  > https://www.psx-place.com/threads/ps3xploit-4-84-hfw-flash-writer-idps-flash-dumpers-v2-0-1-now-install-cfw-from-4-84.23123/
  
* PS3 HACK HFW NON DOWNGRADEABLE MODELS (3K - 4K)
  > https://www.psx-place.com/threads/update-ps3hen-v2-2-2-view-latest-changes-to-the-ps3-exploit-for-superslims-noncfw-models.23955/
  
* PS3Xploit.com website (hosting of exploits)
  > http://ps3xploit.com/

* PS3 WIKI INFO (MODELS)
  > https://www.psdevwiki.com/ps3/SKU_Models

* CARGAR ISOS MEDIANTE SERVIDOR SMB a través de LAN
  > https://www.youtube.com/watch?v=m7H8z6fUgL0
  
--------------------------------------------------------------------------

* PS3 HACK 4.82 OFW INFO

PS3 OFW 4.82 NAND/NOR FLASH WRITER v2.0
***** IMPORTANT DETAILS BELOW -- AVOIDING A BRICK *****
​
WARNING: USE ONLY THE PROVIDED flash_482.hex AS IS. DON'T PATCH IT OR MODIFY IT OR YOU WILL BRICK *****
Verify flash_482.hex file on a flash drive and in the selected USB slot!
flash_482.hex MD5: d05be52f8d21700052fbd1fc0174acae
DO NOT USE ON CFW (Custom Firmware) (Only Supports OFW)
DO NOT USE ON PS3 Models 3xxx/4xxx (aka late Slim or Superslim models), you would brick those consoles.
ON SLIM 2xxx Consoles, always use MinVerChck PUP to ensure that the minimum installable firmware version is < 3.60, if ever the minimum version is >3.56, using the flash writer would partially brick your console!
USE ONLY ON 4.82 OFW

IMPORTANT NOTES:
It's essential not to flood the browser memory with junk before running the exploit. The reason for this is that due to ps3 javascript core memory usage limitations we are scanning several times a small range of browser memory (a few Mb) to find some essential data in RAM, if the memory is flooded due to previous browsing then the range to scan becomes much larger & the probabilities that our data is found in the smaller range decrease dramatically..
So in short, never use the browser or use a homepage you cancel before running the exploit!
It is recommended to set your homepage temporarily to the exploit page you wish to use to ensure there is no memory flooding messing with the exploit initialization stage.

Steps:
For best results with flash writer, here are the recommended steps.
Install OFW 4.82 twice on the console you wish to flash to avoid the potential corruption error during CFW installation.
Open the browser & browse to the ps3xploit.com website, go to the page of the exploit you need. Set the current page as browser homepage. Don't launch the exploit initialization. Close the browser.
Open the browser. The exploit page will load automatically. Choose your path option.
Press the exploit initialization button & wait until initialization succeeds. If it fails, follow the refresh/reload instructions on screen.
Trigger the exploit by pressing the patch button.
On success, load the ps3xploit.com flash dumper, dump the flash memory & validate it with py checker tool. Do NOT restart the console if ever the validation tool gives you errors/warnings on both ros0 & ros1 or you risk to partially brick your console. Report your problem instead.
When you are satisfied with the dump validation, restart your console & install a 4.82 CFW.

--------------------------------------------------------------------

* PS3 4.84 HFW INFO
  > https://www.psx-place.com/threads/ps3xploit-4-84-hfw-flash-writer-idps-flash-dumpers-v2-0-1-now-install-cfw-from-4-84.23123/
  
PS3Xploit 4.84 HFW NOR/NAND Flash Writer + IDPS/Flash Dumpers (v2.0.1)​

Flash Writer (v2.0.1):
NAND
http://ps3xploit.com/hfw/writer/index_nand.html
HDD Version - http://ps3xploit.com/hfw/writer/index_nand_hdd.html
NOR
http://ps3xploit.com/hfw/writer/index_nor.html
HDD Version - http://ps3xploit.com/hfw/writer/index_nor_hdd.html

Supported Firmware
Support 4.84 HFW Firmware ONLY - DO NOT USE ON ANY OTHER FIRMWARE VERSION OR ON CFW YOU WILL BRICK YOUR CONSOLE
Supported Models
Supports Phat Models Axx/Bxx/Cxx/Exx/Gxx/Hxx/Jxx/Kxx/Lxx/Mxx/Pxx/Qxx
Supports Slim Models Cech-20xx and 21xx
Support with some CECH 25xx models, to be sure your console must have a minver of 3.56 (a factory installed firmware 3.56 and lower) to know for sure you can run the minverchk.pup to avoid bricking (semi) this model.

!!! WARNINGS !!! 
CAUTION: MISHANDLED FIRMWARE FLASHING CAN LEAD TO A BRICK - USE AT YOUR OWN RISK!!! 
DO NOT USE THIS ON CECH-3xxx/4xxx OR YOU WILL BRICK YOUR CONSOLE!!!
DO NOT POWER OFF THE CONSOLE ONCE STARTED. IT MAY RESULT IN A BRICK! 
MAKE SURE TO USE AN UNMODIFIED & MD5 CHECKED "flash_484.hex" FILE ON USB DEVICE!* 
THE MD5 OF "flash_484.hex" MUST BE: AB2B3A2E23FA731301260F5702FC4101 
SOME PS3's HAVE BOARDS SWAPPED (a.k.a. refurbished either by Sony or Sketchy local modders). Checking the minverchk.pup should be highest priority - via @Joonie 
"fish.hex"(v1) or "flash_482.hex" or "flash_484.hex" are not interchangeable with 4.84 and vice versa only use the flash_XXX.hex of that version or you will brick your console,


Release ZIP: http://ps3xploit.com/hfw/release/NOR_NAND_writer_release_2.0.1_PS3Xploit.zip
flash_484.hex- MD5: AB2B3A2E23FA731301260F5702FC4101​

Dumpers (v2.0.1):
IDPS Dumper
http://ps3xploit.com/hfw/dumper/index_idps.html
NAND Dumper
http://ps3xploit.com/hfw/dumper/index_nand.html
HDD version http://ps3xploit.com/hfw/dumper/index_nand_hdd.html
NOR Dumper
http://ps3xploit.com/hfw/dumper/index_nor.html
HDD version: http://ps3xploit.com/hfw/dumper/index_nor_hdd.html

Supported Firmware
Supports OFW/CFW/HFW CEX Firmware versions 4.10 to 4.84
Supports OFW and CFW DEX Firmware version 4.81 /4.82 /4.84
Supports SuperSlim Models
Supported Models
Supports Phat Models Axx/Bxx/Cxx/Exx/Gxx/Hxx/Jxx/Kxx/Lxx/Mxx/Pxx/Qxx
Support Slim Models 2xxx/3xxx

Release ZIP: http://ps3xploit.com/hfw/release/NOR_NAND_IDPS_dumper_release_2.0.1_PS3Xploit.zip​

-------------------------------------------------------

Using the Flash Writer (for CFW Compatible models only)

Supports Phat Models Cech-Axx/Bxx/Cxx/Exx/Gxx/Hxx/Jxx/Kxx/Lxx/Mxx/Pxx/Qxx
Supports Slim Models Cech-20xx and 21xx
Support with some CECH 25xx models, to be sure your console must have a minver of 3.56 (a factory installed firmware 3.56 and lower) to know for sure you can run the minverchk.pup to avoid(semi) bricking this model.

WARNING: USE THE PROVIDED flash_484.hex/flash_484.jpg AS IS.
***** DON'T PATCH IT OR MODIFY IT OR YOU WILL BRICK *****​

DO NOT USE ON CFW (Custom Firmware) (Only Supports HFW)
DO NOT USE ON PS3 Models 3xxx/4xxx (aka SuperSlims / Late Slim models) you will brick those console.
USE ONLY ON 4.84 HFW
Verify flash_484.hex file on a flash drive and in the selected usb/card port.
Make sure to use TRIANGLE and save flash.jpg to HDD first (if using HDD option!)
flash_484.hex/flash_484.jpg MD5: AB2B3A2E23FA731301260F5702FC4101

For best results with the flash writer, here are the recommended steps.

Install HFW 4.84 twice on the console you wish to flash to avoid the potential corruption error during CFW installation.
Depending on which option you choose, and model of your ps3. Go to ps3xploit.com select "Flash writer" --> 4.84 HFW --> Flash from XXX (depend that you are following USB or HDD method) --> NAND or NOR depending on your console model.
* A.) Is your console a NOR or NAND? Find out here
Set the current page as browser homepage. Don't launch the exploit initialization. Close the browser.
Open the PS3 browser once again. The exploit page will load automatically (if set to homepage correctly). Choose your path for hex file if you are following USB method or download the flash_484.jpg file if you use the hdd edition.
Press the exploit initialization button & wait until initialization succeeds. If it fails, follow the refresh/reload instructions on screen.
Trigger the exploit.
On success, load the ps3xploit.com dumper, dump the flash memory & check it with py checker tool. Don't restart if ever the validation tool gives you errors/warnings in both ros0 & ros1 or risk a partial brick.
Restart your console & install a 4.84 CFW.

Usage Tips:
Try using a LAN connection or a solid WiFi connection during exploitation. A weak signal can cause problems.
If the exploit takes more than 5 minutes to work, reload page, browser, or restart console and tryS again.
If you are using a LAN connection and experience network issues, make sure all cables to router are in working order.
PS3Xploit FAQ: http://ps3xploit.com/help/faq.html

---------------------------------------------------------------

* PS3Xploit.com website (hosting of exploits)
  > http://ps3xploit.com/
  


