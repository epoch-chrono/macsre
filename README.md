# SRE Battle Station

SRE Battle Station - Mac (Apple Silicon and Intel-based), Linux (Ubuntu x86_64), and Windows (x86_64) installation and configuration via Ansible.

Focused on site reliability engineering automation and tools, as well as the ease of use for an engineer.

## Mac

### Apple Silicon (M1, M2 and M3)

#### Clean Installation

**ATTENTION**: <ins>This process will wipe out/erase all your data</ins>. [Run a **Time Machine** backup before anything else](https://support.apple.com/en-gb/104984)!

You'll also need a network/internet connection to activate and download macOS.

1. Shut down your Mac:
   1. Click on the Apple sign (top left corner of the screen);
   2. Click on **Shut down...**;
   3. Uncheck **Reopen windows when logging back in**;
   4. Click on **Shut Down**;
2. Wait until your Mac completely turns off;
3. Now, press and hold the power button until "*Loading startup options*" appears; 
4. Select **Options**, click **Continue**, then follow the onscreen instructions;
5. Select **Disk Utility**, click **Continue**;
6. On the next screen, follow these steps:
   1. On the left menu, section _Internal_, select **Macintosh HD**, the first one;
   2. On the top menu of the Disk Utility window, click on the **Erase** button;
   3. Keep the name as is, and be sure to select the _Format_ **APFS**;
   4. Confirm the operation by clicking on **Erase Mac...** and then agree by clicking on **Erase Mac and Restart**;
7. You'll see a progress bar, and your Mac will restart. Wait for the prompt to **Activate Mac**. Follow these steps:
   1. On the top right corner of the screen, click on the **Wi-Fi** icon menu, select your network and enter your password;
   2. Wait for the message _Your Mac is activated_ and click on **Exit to Recovery**;
   3. Back to the previous Recovery screen, click on **Reinstall macOS <release_here>** (on today's date, it would be **Sonoma**);
   4. Click on **Continue**, wait for the validation, and then click on the **Agree** twice;
   5. Select your **Macintosh HD** and click on **Continue**;
   6. The process will take about 60 minutes to finish, depending on your hardware setup, of course;
8. 
