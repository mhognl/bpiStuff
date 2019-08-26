# bpiStuff
##Scripts for Banana Pi

### Banana Pi R1 SATA support
I've added script.fex for Banana Pi R1 SATA support. It does work with a 5V/2.1A adapter and a Toshiba 320GB HDD. It's tested in Armbian Stretch (upgraded from Jessie, no official support anymore). I put this script in /boot and converted it to bin with the command
  
  *fex2bin /boot/script.fex /boot/script.bin*
  
Then it worked, but one HDD wasn't working (Toshiba). Another HDD from Toshiba was working. I leave it on one night and it was running (45 Degrees in Celsius).
