# bpiStuff
## Scripts for Banana Pi

### Banana Pi R1 SATA support
I've added script.fex for Banana Pi R1 SATA support. It does work with a 5V/2.1A adapter and a Toshiba 320GB HDD. It's tested in Armbian Stretch (upgraded from Jessie, no official support anymore). I put this script in /boot and converted it to bin with the command
  
  *fex2bin /boot/script.fex /boot/script.bin*
  
Then it worked, but one HDD wasn't working (Toshiba). Another HDD from Toshiba was working. I leave it on one night and it was running (45 Degrees in Celsius).

You can download the script with the following:
  
  *wget https://raw.githubusercontent.com/mhognl/bpiStuff/master/R1/script.fex*
  

### Banana Pi R1 custom interfaces without swconfig and changes to hostapd.conf
I did research on the web and I've put together a custom interface without swconfig. You can change it to your likes.
Download it with this:
  
  *wget https://raw.githubusercontent.com/mhognl/bpiStuff/master/R1/interfaces*
  
