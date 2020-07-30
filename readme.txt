#######################
       usage
#######################

gcc "firmware-file-name.img"  
---keep the quotes---

*****IMPORTANT*****
It didn't work for me on my windows install for some reason. 
The checkbyte at the end was always wonky. 
It worked first try on my kali linux install though.  

#######################
       usage
#######################
*/this .c file will replace the header info of the firmware from open-wrt for the 
netgear_wndr3800 with the appropriate 128 byte header to be accepted by the 
netgear_wndr3800sw Surewest model. then it replaces the last byte with the new 
crc checkbyte.

*/this wont make a new file as is. it just patches the original. since the 
firmware is readily available on open-wrt's website i didn't think it was 
needed.

*/if you need help just ask me. I'm usually available.

*/GOOD LUCK HOPE THIS HELPS!!!