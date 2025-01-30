# IS Library and Media Preservation Lab: Optical media preservation
## Overview
The optical media preservation workflow documentation is a guide for performing disc imaging, media extraction, and preservation of optical media on the Digital Preservation Suite computer in the IS Media Preservation Lab. The workflow provides instructions for using [FTK Imager](https://www.exterro.com/digital-forensics-software/ftk-imager), [Exact Audio Copy (EAC)](https://www.exactaudiocopy.de/), and [BWF MetaEdit](https://mediaarea.net/BWFMetaEdit).
## Resources
[A Comprehensive Guide to FTK Imager](https://www.hackingarticles.in/comprehensive-guide-on-ftk-imager/)

[Know Your Digital Storage Media](https://lib.utsa.edu/knowyourmedia/index.html)

A helpful website featuring the most common formats of digital media storage, with diagrams and explanations of each format.

[Proposed Optical Media Imaging Workflows for Fales Library & Special Collections](https://archive.nyu.edu/bitstream/2451/43876/2/Appendix%20A%3A%20Disc%20imaging%20and%20copying.pdf)

[ISOBuster documentation](https://www.isobuster.com/help/)

[Exact Audio Copy - FAQ](http://www.exactaudiocopy.de/en/index.php/support/faq/)

## Disc imaging, audio extraction, and metadata creation workflow
### Getting Started
This section covers turning on the computer, logging in, inserting a disc, and creating project folders.
1. Turn on the computer and login:
   > a. Turn on the computer by pressing the ON button the tower located on the floor on the right-hand side of the computer station.

   > b. Login to the islab user using the credentials provided below the monitor.
2. Connect the media player or external disc drive of your choice to the computer. Player 1 (F:) is preferred due to the newer model of this player. However, in the case that Player 1 (F:) has trouble reading your disc, you may restart the workflow using Player 2 (D:) as a backup.
   > a. The location for Player 1 is (F:) DVD RW AD725

   > b. The location for Player 2 is (D:) DVD RW ND3540
3. If needed, clean your record with a microfiber cloth from the record cleaning kit (gray box located to the right of the PHONO record player on the back wall, and labeled ‘Audio Maintenance’).
4. On your selected player, use  the eject button to insert your disc, located on the lower right-hand side of the device. Please use the eject button to close the player instead of pushing the tray.
5. Create a project folder within the disc image folder, located on the desktop.
   > a. Inside of that folder, add two more folders labeled:
   
   > b. **"Imaged Discs”** and **“Extracted Audio"**
   
   > c. Guidelines: Create additional folders for the project as needed. Use a consistent naming convention for all of the files.

 ## Creating a disc image using FTKImager
 1. Double click the AccessData FTK Imager shortcut:

![unnamed](https://github.com/user-attachments/assets/4910ecf2-86ce-4085-ba77-438ead57c97e)

2. The program will ask you: "Do you want this program to make changes to the computer?” Select Yes.
3. At the top left of the window, click File, then Create Disk Image. 
4. In the Create Image dialog box, choose Logical Drive, then click Next.
![unnamed (1)](https://github.com/user-attachments/assets/0708d59b-e5f8-4e3e-9052-5b0475a97035)

5. In the Select Drive dialog box, choose your disc drive from the dropdown:
  > a. For Player 1, select F:\

  > b. For Player 2, select D:\

  > c. Click the Finish button to verify the drive selection. This is the source drive that you will be imaging.

 ![unnamed (2)](https://github.com/user-attachments/assets/ca406922-8f29-4b1c-b151-0bd2495a4850)

6. In the "Create Image" dialog box, select Add, then click Browse.
  > a. Select the folder “Imaged Discs,” located on the islab-install desktop.

  > b. In the Image Filename box, Name your file and **specify the file extension as .iso.**

  > c. Click Finish.
![unnamed (1)](https://github.com/user-attachments/assets/133615dc-0633-4dab-883c-e3d425aa28da)
7. In the "Create Image" dialog box:
  > a. **Check** the box for “Verify images after they are created”

  > b. **Uncheck** the box for “Create Directory Listings…”. (Leaving the box checked creates an unneeded CSV file that you will just end up deleting later.)

![unnamed (3)](https://github.com/user-attachments/assets/1e414121-cf04-40c5-a63a-0a6bb9abcf84)

8. Click Start to begin imaging.
  > a. A new dialog box with a green progress bar will appear. Please be patient as the disc completes the imaging process.
9. The image is complete once Status: (above the green bar) reads: ‘Image created successfully.’
10. Press Close at the bottom of the dialog box.
11. Check to make sure that the program exported three files to the 'Imaged Discs' folder:
  > a. a CUE file

  > b. a Text document

  > c. a Disc Image file
12. Once finished, eject the disk from the player and close the program.

## Extract files using Exact Audio Copy (EAC)

1. Insert optical disc into drive. 
2. Launch Exact Audio Copy (EAC) by double-clicking the Desktop shortcut icon.
3. In the top left corner of the program, select the appropriate disc drive from the dropdown menu.

![unnamed (4)](https://github.com/user-attachments/assets/0c16a5f1-186a-4c50-bc9c-2b61de21ff5e)

![unnamed (5)](https://github.com/user-attachments/assets/a54578a5-8612-419a-965c-b29ce4890e23)

4. Set up Secure Mode & Extract Audio:
  > a. Press F10 -or- navigate to EAC in the dropdown menu, and select Drive Options.

  > b. An informational popup will appear. Press OK.
 ![unnamed (6)](https://github.com/user-attachments/assets/f4195f3f-ff04-4f3c-96fb-07e49dc69b26)

  > c. **Check** the buble for ‘Secure mode with following drive features,’ then **check** the bubble for ‘Drive is capable of retrieving C2 error information.'
![unnamed (7)](https://github.com/user-attachments/assets/3bdfa88a-eb79-47a8-a947-00c6f404f8ce)
  > d. **Check** the box for ‘Detect Read Features…’ at the bottom left of the menu.

  > e. In the Analyzing window, **testing will automatically commence** and may take several minutes.  
![unnamed (8)](https://github.com/user-attachments/assets/b9b2c0b2-723f-4c33-86f1-c64284b9e502)

  > f. Testing is complete once the boxes labeled ‘Caching,’ ‘Accurate Stream,’ and ‘C2 Error Info’ **are each filled with a ‘Yes’ or ‘No’** response. Once you see three responses in these fields, select **Apply.** 
![unnamed (9)](https://github.com/user-attachments/assets/bcefdf92-d6fa-45a6-85ff-5bfce1e5931f)

  > g. Select **Yes** and then **OK** in the following menus.

  > h. There should be a list of audio extractions on the screen. Double click on each extraction’s name to rename them.

5. Detect gaps:
  > a. Select the Action menu (top left of the screen).
  > b. Scroll to 'Detect Gaps' and **check** the option for ‘Append gaps to previous track.' (Once EAC detects these gaps, which represent important timing information, it will preserve them in the disk image.)
 
![unnamed (10)](https://github.com/user-attachments/assets/c3b8fd25-3ad6-4d1a-ad4f-fff933c30015)

6. Save the disc tracks as .wav recordings:
  > a. Click the "WAV" icon on the left-hand side of the screen to begin extracting the audio.
![unnamed (11)](https://github.com/user-attachments/assets/008b4643-70a5-4439-be78-117400f10807)

  > b. When the new dialog box pops up, ensure that the file ends in .wav and specify the destination as the ‘Extracted audio’ folder. Then press Save. Copying may take a moment.

![unnamed](https://github.com/user-attachments/assets/acedbb39-6a54-47c3-af6b-c2c49bffe18a) ![unnamed (1)](https://github.com/user-attachments/assets/fbfd0b8c-ede6-4202-8be6-1140c27bd894)

  > c. Once copying is complete, the speakers make an audible beep. Click “OK."

  > d. Carefully review the error and status report page to see the quality of the digital capture. If excessive errors are reported on tracks, it may be necessary to rip the disc again. For example, if a track gets below 99% it might be worth taking the disc out, cleaning it, and repeating the rip to see if EAC can make improvements.

  > e. Click Create Log on the Status and Error Messages dialog box that appears and save the generated .log file to the same location — bar the extension, have the file name identical to the .wav file. Press OK.

  ![unnamed (2)](https://github.com/user-attachments/assets/987b5baf-0824-4f1e-a5eb-1a39f6b9fc2c) ![unnamed (3)](https://github.com/user-attachments/assets/aa2cc59b-64d4-446a-9fa1-db8d38154262)

![unnamed (4)](https://github.com/user-attachments/assets/a0de4dfb-72f3-4820-995d-6b95a880e551) ![unnamed (5)](https://github.com/user-attachments/assets/f0d2d2f0-fe7e-42df-9b8e-cfbca1cc2500)

  > f. Navigate to the folder where the audio was extracted to check any reported errors. Verify the correct number of wav files and the log file created by EAC.
  > g. Quality control by playback should be performed in all cases. Check tracks carefully by playing them back in VLC Media Player. If the sound is satisfactory and EAC reported no errors, the capture is complete.

     
