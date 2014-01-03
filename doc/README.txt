Basic instructions for setting up and running Byzantium:

Please read before starting Byzantium!

 * Download the .iso image: 
http://wiki.hacdc.org/index.php/Downloading_Byzantium
 * Burn the image to disk:
   * Insert a blank CD- or DVD-ROM in your burner.
   * Start your disk burning or creation utility and select the 'burn image 
     to disk' function.
   * When prompted, choose byzantium-v0.1a.iso
   * Burn the file to disk.
   * Examine the disk to ensure that it contains folders called /boot and 
     /porteus.  If it doesn't something went wrong.
 * Or, install to a formatted USB key:
   * Windows
     * Extract the contents of the Byzantium .iso image using 7zip, WinRAR, 
       .iso mastering software to the USB key.
     * If you are more familiar with .iso mastering software, use that to 
       copy the files out of the image onto the USB key.
     * If you prefer to use CD emulation software, mount the .iso in that and 
       copy the files that way.
     * On the USB key, run the script /boot/win_start_here.hta and follow the 
       directions.
   * Linux
     * Mount the .iso image to one of your /dev/loop devices
     * Alternatively, open the .iso image with your file manager of choice.
     * Copy all of the files onto a USB key (for now, I'll assume it's 
       mounted under /mnt/key).
     * cd /mnt/key/boot
     * sudo ./lin_start_here.sh
     * Follow the instructions on the screen.
 * Ensure that your computer will boot from the CD or DVD-ROM drive first.  
   If it will not, change the BIOS settings so that this will be the case.  Or, 
   hit the appropriate key on your keyboard during boot to open the boot device 
   selection menu and choose your CD or DVD-ROM drive.
 * Boot your computer from the Byzantium media.
 * login as guest with password guest
 * When the desktop appears, Firefox will start and give you the next step.
 * Connect some wireless devices (like another laptop or netbook) to your 
   mesh.  They need to be capable of ad-hoc wireless mode for this to work (for 
   now).
 * Have them connect to the client IP of your Byzantium node and experiment 
   with the services running on it.
 * Neighboring Byzantium nodes should find one another and automatically link 
   up so long as they're on the same wireless channel and ESSID.

Thanks to the Porteus Linux development team for the basic framework for this 
document.

