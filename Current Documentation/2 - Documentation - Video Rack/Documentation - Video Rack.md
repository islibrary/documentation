# IS Library and Media Preservation Lab: Video rack workflow documentation

*Last updated: March 7, 2024*

## Overview

The video rack workflow documentation is a comprehensive guide for utilizing the video rack in the Information Studies Media Preservation Lab (or IS Lab for short). This guide includes workflow instructions for using Vrecord, the transfer software, and [all decks](#appendix-b) in the video rack.

1. **Pre-digitization**: selecting the correct deck for your project, cleaning and preparing media for optimal transfer, and establishing a signal path prior to transfer.
2. **Digitization**: workflow for converting analog data to digital formats using vrecord.
3. **Post-digitization**: directions for file management and storage, and considerations for digital preservation.

The IS Lab video rack supports the following formats:

VHS, S-VHS, D-VHS, miniDV, Beta, Betacam, Betacam SP, Digibeta, Hi8, 
U-Matic, Laserdisc, & DVCAM

## Resources

### General
[UCLA Media Archival Studies Research Guide](https://guides.library.ucla.edu/mas)

Resources for media preservation from the UCLA Library intended for students in the Media Archival Studies program.

[AMIA Homebrew Documentation](https://github.com/amiaopensource/homebrew-amiaos)

GitHub repository for instructional guides and troubleshooting for AMIA’s Homebrew software.

[Vrecord Documentation](https://github.com/amiaopensource/vrecord)

GitHub repository for instructional guides on using the vrecord video capture software.

[AV Artifact Atlas](https://www.avartifactatlas.com/)

The AV Artifact Atlas is for use in the identification and definition of the technical issues and anomalies that can afflict audio and video signals.

### Format Identification Resources
[University of Illinois’ Preservation Self Assessment Program](https://psap.library.illinois.edu/collection-id-guide/videotape)

Timeline of format obsolescence and collection of images to help with the identification of each video format.

[Video Formation Identification Guide](https://cool.culturalheritage.org/videopreservation/vid_id/index.html)

This site is produced for archivists, librarians, curators and conservators who want to identify the videotapes in their collections. Clicking the date ranges at the left will load thumbnail images of the prominent videotape formats and a short essay on the formats for the particular time period.

[Texas Commission For the Arts Video Assessment and Identification Guide](https://www.arts.texas.gov/wp-content/uploads/2012/04/video.pdf)

Video format identification guide. It also covers proper storage and risks for specific video formats. It explains how to perform a tape inspection and what to look for.

[U-matic Palsite](https://umatic.palsite.com/tapes.html#:~:text=The%20different%20series%20tapes%20are,include%20Maxell%2C%203M%20and%20Ampex)

A website which provides information about the U-matic video format, including a table of formats, gallery, glossary, and lore.

## Table of Contents

[Overview](#overview)

[Resources](#resources)
> [General](#general)
>
> [Format Identification Resources](#format-identification-resources)

[Table of Contents](#table-of-contents)

[Rules and Guidelines](#rules-and-guidelines)

[Video Rack Workflow](#video-rack-workflow)
> [Pre-digitization Workflow](#pre-digitization-workflow)
> > [Identifying video format and choosing the correct deck](#identifying-video-format-and-choosing-the-correct-deck)
> > 
> >[Required inspection](#requireed-inspection)
> > 
> > > [Inspection Workflow](#inspection-workflow)
> > > 
> > > [Rewinding tapes prior to transfer](#rewinding-tapes-prior-to-transfer)
> > 
> > [Turning on the Equipment](#turning-on-the-equipment)
> >
> > [Setting the Signal Path](#setting-the-signal-path)
> >
> > [S-Video Signal Paths](#s-video-signal-paths)
> >
> > [Configurations for S-Video](#configurations-for-s-video)
> >
> > [Using Internal TBCs](#using-internal-tbcs)
> >
> > [Black Magic Switcher Routing - Composite](#black-magic-switcher-routing-composite)
> >
> > [Connecting to the camcorder (ask for lab staff assistance)](#connecting-to-the-camcorder-ask-for-lab-staff-assistance)
> >
> > [Connecting camcorder audio](#connecting-camcorder-audio)
> >
> > [Signal Flow for Auxiliary setup](#signal-flow-for-auxiliary-setup)
> >
> > [U-Matic Transfers](#umatic-transfers)
> >
> > [U-matic specific actions](#umatic-specific-actions)
> >
> > [U-Matic rewind lab cart](#umatic-rewind-lab-cart)
> >
> > [Note on U-matic formats](#note-on-umatic-formats)
> >
> [Digitization](#digitization)
> > [Vrecord workflow](#vrecord-workflow)
> >
> > [Launch Vrecord in terminal](#launch-vrecord-in-terminal)
> >
> > [Configuring Vrecord settings](#configuring-vrecord-settings)
> >
> > [Monitor the Signal](#monitor-the-signal)
> > > [Perform a Test Capture](#perform-a-test-capture)
> > 
> > [Rewind](#rewind)
> > 
> > [Set Final Recording Settings in Vrecord](#set-final-recording-settings-in-vrecord)
> >
> [One-Inch Open Reel Tape Digitization](#one-inch-open-reel-tape-digitization)
> >
> > [BVH2000 signal flow](#bvh2000-signal-flow)
> >
> > [Threading the BVH-2000 VTR](#threading-the-bvh-2000-vtr)
> >
> > [Turning on the BVH-2000](#turning-on-the-bvh-2000)
> >
> > [Playing the tape on the BVH-2000](#playing-the-tape-on-the-bvh-2000)
> >
> > [Rewinding the Tape](#rewinding-the-tape)
> >
> [Post-Digitization](#post-digitization)
> >
> > [Rewind Deck](#rewind-deck)
> >
> [DVRescue Workflow (Data Migration)](#dvrescue-workflow-data-migration)
> >
> > [DVRescue Resources](#dvrescue-resources)
> >
> > [GUI Navigation](#GUI-Navigation)
> >
> > [Step-By-Step: GUI](#step-by-step--gui)
> >
> > [Command Line Interface](#command-line-interface)

[Appendix A: Video Rack Decks and Supported Media Formats](#appendix-a--video-rack-decks-and-supported-media-formats)
> [IS lab equipment supported format and identification chart](#is-lab-equipment-supported-format-and-identification-chart)
> 
> [Format Comparisons](#format-comparisons)
> 
> [Timeline of Video Formats](#timeline-of-video-formats)
>

[Appendix B: Equipment Legend](#appendix-b--equipment-legend)
> [Video Rack A and B](#video-rack-a-and-b)
>
> [Lab Cart](#lab-cart)

[Appendix C: Magnetic Tape Head Cleaning Guide](#appendix-c--magnetic-tape-head-cleaning-guide)
> [U-matic Deck Head Cleaning](#umatic-deck-head-cleaning)
>
> [Resources](#resources)
>
> [Workflow — VCR head cleaning](#workflow-vcr-head-cleaning)
> > 
> >[Remove outer shell of deck](#remove-outer-shell-of-deck)
>
> >[Clean interior hardware](#clean-interior-hardware)

[Appendix D: Monitor maintenance](#appendix-d--monitor-maitenance)
> [Resources and Definitions](#resources-and-definitions)
> >
> > [Guidelines and rules](#guidelines-and-rules)

## Rules and Guidelines
Please contact an IS Lab Staff team member for any and all questions about the guidelines listed below.

1. Leave all food and drinks outside of the lab on the designated table in Zone A of the library.
2. **<ins>DO NOT REWIND</ins> tapes in the following transfer decks: U-Matic, Hi8, SVHS, VHS1, and VHS2. Only use the designated “rewind decks,”** as listed in the equipment key, for rewinding your tapes prior to transfer. This is essential to protecting the longevity of our vintage equipment. 
3. Do not clean any deck’s video or audio heads. Please ask a staff member for assistance. 
4. If any equipment or software stops working or breaks during transfer, immediately contact an IS Lab staff team member for assistance.
5. Turn off monitors in the rack when not in use, to prevent screen burn.
6. Copy files to the appropriate IS Lab server folder or to your personal storage device after transferring. Do not leave files on the transfer computer’s hard drive or desktop—all files are deleted from the computer at the end of each week. 
7. All tapes need to be inspected before using any deck to ensure it is safe to transfer. If you have any questions about the quality of your tape, ask an IS Lab staff member.
8. If you have not previously used one of the decks or it is your first time performing a specific transfer, please reach out to a member of the IS Lab Staff for assistance.
9. If you are lacking materials in order to complete your projects (e.g. gloves, alcohol, etc.), please inform a member of the IS Lab Staff so that they may place an inventory request. This helps to ensure that there will be enough materials for everyone.

## Video Rack Workflow

### Pre-digitization Workflow

#### Identifying video format and choosing the correct deck

Prior to digitization, it’s necessary to identify the correct deck for media format transfers. Use this section to identify your media, choose the correct deck, prepare media prior to transfer, and ensure the protection of equipment while working with the video rack transfer station.

Refer to [Appendix A](#appendix-a--video-rack-decks-and-supported-media-formats) for a list of video formats resources section to identify the formats of the tapes for digitization

After identifying formats and decks for digitization, contact a lab staff team member to ensure all heads are clean prior to media transfer.


#### Required inspection

A thorough inspection of the tape should be performed before transfer to ensure there is no mold, dirt, or excessive damage to the tape. Tapes with any of these issues cannot be transferred in the IS Lab. Failure to inspect tapes could result in damage to the decks and tape. 

It’s important to pop off or enable recording protection tabs on cassettes so media is not accidentally erased.

##### Inspection Workflow

If there are any questions about the condition of the tape(s), **err on the side of caution and do not attempt playback at the IS Lab**. Lab staff is available to assist you in determining whether or not a tape is fit for playback.

For cassettes only: It’s important to pop off or enable recording protection tabs to ensure that the media is not accidentally erased. Below are two examples of video formats and their recording protection tabs in both positions.

**Examples of Protective Tabs on Video Formats**

Format | Safe Mode | Rec Mode 
:--- | :---: | :---: 
**Hi8** | ![Inspection1](https://github.com/user-attachments/assets/5f53a0e2-0044-481c-a168-0ed733cd7e95) | ![Inspection2](https://github.com/user-attachments/assets/5624ef21-81db-469f-a33f-1f7b91931ba1)
**VHS** | ![Inspection3](https://github.com/user-attachments/assets/f297ca6c-d547-4145-ad5f-930c4713e36c) | ![Inspection4](https://github.com/user-attachments/assets/1f9f59b6-e69c-4829-822f-aba217bb40da)


1. Inspect a videotape only with clean and dry hands. Gloves and face masks may also be worn, because of the risk of contact to mold and dust. Gloves should be worn when inspecting any non-cassette formats (1 inch, 2 inch, ½ inch). Work on a clean, dry surface. 
2. **Check for mold on the exterior**: Before picking the tape up, check for signs of mold. There are many signs of mold; small white and brown strands or filaments have been reported as signs of mold on video tape. If mold is suspected, the tape should be isolated and cannot be transferred in the lab. 

3. **Check for mechanical damage**: Use a finger or pen to remove the anti-static guard and inspect the surface of the tape. Check for wrinkles, creases, and stretched tape, which may indicate mechanical damage to the tape. Do not play back a tape showing any of these signs of mechanical damage in the lab. 

![Inspection5](https://github.com/user-attachments/assets/cb5b0175-6f41-4da0-950f-dd492444021b)

*Crinkled or snapped tapes cannot be played back in decks.* 

4. **Examine the tape pack**: Pick up the tape and examine the tape pack by holding it at a 45-degree angle. Look at the edges and check for signs of dirt, mold, or debris. White or brown powder on the edges of the tape pack could indicate binder deterioration. If you see powder on the edges of tape, do not transfer it in the IS Lab. The tape pack should be tight and even. Do not play a tape in a lab machine if there are extreme tape pack issues, as this may cause damage to the decks.

5. **Tape odors**: Do not bring your nose to the tape; wave a hand and waft the smell towards your face. Note any strong smells emanating from the tape. Odors can indicate mold or dirt on the tape. Additionally, older acetate tapes could exhibit vinegar syndrome and would give off a distinct vinegar aroma (this is rare for video). 

##### Rewinding tapes prior to transfer

For transfers with **VHS, Hi8, and U-matic, only use the designated rewind decks**. Do not rewind tapes in the playback decks to prevent damage to equipment.

### Turning on the Equipment

![TurningOn1](https://github.com/user-attachments/assets/c474a6c1-6f6f-4059-b824-03f370a775bf)
<img width="172" alt="TurningOn2" src="https://github.com/user-attachments/assets/33fed123-f368-4899-b0af-835b637a31b0" />

Number | Deck Shorthand | Deck Make/Model | Supported Media Formats
:--- | :--- | :--- | :--- 
1 | VHS 1 **(NO rewinds)** | Sony SLV-675HF | VHS
1 | VHS 2 **(NO Rewinds)** | Sony SLV-AX10 | VHS; LP
2 | SVHS | Panasonic AG-7750 | SVHS; VHS
3 | Hi-8 **(NO rewinds)** | Sony EVO-9800A | Hi8 Video
4 | VCR, DVD (rewinds) | Samsung | VCR; DVD
5 | LZR | Pioneer LD-V8000 | LaserDisc 
6 | SBM | Sony SL-HF2000 | Betamax; SuperBetaHifi
7 | DGB 1 | Sony DVW-A500 | Digital Betacam; Betacam; Betacam SP; Betacam SX; MPEG IMX
7 | DGB 2 | Sony J30-SDI | Digital Betacam; Betacam; Betacam SP; Betacam SX; MPEG IMX
8 | UMA **(NO rewinds)** | Sony BVU-950 | U-matic Tape
9 | DV1 | Sony DSR-1500A Panasonic AJ-HD1200A | MiniDV; DV(medium and large); DVCPRO (not LP); DVCAM(not LP)
9 | DV2 | Sony DSR-1500A | DVCPRO; DVCPRO50; DVCPRO50P; DVCPRO HD; DVCPRO HD-LP; DVCPRO formatted tapes on ¼ consumer DV and DVCAM tapes. 
9 | DVC | Panasonic VTR10 | DVCPro50
10 | TBC | For.A FA-300 | 
11 | BM-SWR | Blackmagic Smart Videohub 20x20 | 
12 | MON1-SWR | Ikegami TM10-17RA | 
12 | MON2-SWR | Ikegami TM9-1D | 
13 | RF Scope | Tektronix 1710-J | 
14 | Hi-8 (rewinds) | Sony EVO-9800A | Hi8; Video 8
15 | WAV | Compuvideo | 
16 | MON1-SWR | Shinybow Switcher SB 5440-BNC | 
17 | CPB | Composite Patchbay | 
18 | SVPB | S-Video Patchbay | 
19 | APB | Audio Patchbay | 
20 | 1-inch C-format VTR | Sony BVH-2000 | 1" open reel, C-format 240 Volt power supply

The following instructions and images illustrate how each piece of equipment on the Video Racks should be powered on. Please follow the order of the numbered steps below.

![TurningOn3](https://github.com/user-attachments/assets/8775ff50-dafa-4dee-96a1-cbdce5db9590)

1. **Turn on the three power supplies** for Video Rack A and B. Find the little red buttons underneath a plastic flap, located on the left of each CyberPower deck.

2. **Turn on the Shinybow switcher**, which allows the signal running to the monitors and waveform monitor to be toggled.

3. **Turn on the Time Base Corrector** (gray piece of equipment below the Waveform monitor.)
   
4. **Turn on the Waveform Monitor** (the off-white object located above the TBC). Power button is in the bottom left corner.

5. **Turn on the Pre-digitization and Post-digitization CRT Monitors** (the two TVs). Power buttons are located on the bottom left and right corners of each monitor, respectively. **DO NOT LEAVE THESE MONITORS ON FOR A PROLONGED PERIOD OF TIME, unless you are transferring a tape. As soon as you are finished with your transfer, please turn these monitors off to prevent them from burning out**.
   
6. Select the deck you are using and turn it on:
   > a. **VHS decks**: Power Button is on the left side of each deck.
   >
   > b. **SVHS deck**: Power Button is on the bottom left of the deck.
   >
   > c. **U-matic deck**: Power Button is on the top right of the deck.

### Setting the Signal Path

A signal is picture or audio information, encoded either magnetically, in a continuous analog signal, or using discrete pulse code modulation, in a digital signal. To transfer this signal to a computer, a playback device reads the tape, converting analog signals to digital. The digital signal is then transmitted to the computer through an interface like Blackmagic.

**A signal path** is the route in which a particular signal from a tape travels through a chain of equipment. Please use this step-by-step guide to set the signal path on the Video Transfer Racks (refer to [Appendix B](#appendix-b--equipment-legend) for equipment legend).

1. **Configure the composite patch bay**: This piece of equipment has several inputs, which are each labeled according to the deck from which it receives the video signal. Following the labels on the patch bay, ensure that the leftmost cable is connected to the input which corresponds to the video deck you are using. In the example shown below, the leftmost cable is receiving the video input from the SVHS player. The other three cables should be plugged into the outputs labeled: **TO For.A TBC, FROM TBC**, and **OUT TO COMPS AJA**, as shown below. This ensures that your signal will be registered by the video transfer software.

![SignalPath1](https://github.com/user-attachments/assets/c75c89db-aa5b-47b7-a338-13f64db6468a)

*Setting the Signal Path on the Video Rack*

### S-Video Signal Paths

Please note that the signal paths for **Hi8, SVHS, and DGB2** run through the **S-Video Patchbay (SVPB)** and not the Composite Patchbay (CPB). Refer to the diagram below, which illustrates the differences between **S-Video** and **Composite** signal paths:

![Svideo1](https://github.com/user-attachments/assets/73cd6965-80b0-4e38-a498-7f54034c5b55)

### Configurations for S-Video

1. If the settings on the For.A TBC are not already exposed, **flip the top edge down** to reveal its settings. In the bottom right corner of the device, flip the silver switch from COMP to Y/C. This ensures that the video signal will be retrieved from the SVPB. See the image below for reference:

![Svideo2](https://github.com/user-attachments/assets/7671ba5b-2568-4842-81cc-dcf545fbf2e4)

2. On the Pre-Dig Monitor, push in the button labeled Channel B (this sets it to Y/C).
3. Route the audio and video patchbays accordingly:
> a. Run Y&C cables on the SVPB for video by plugging them underneath the chosen deck.
>
> b. Run the left and right cables on Audio Patch Bay by plugging them underneath the chosen deck (use S-VIDEO output).

4. On the Black Magic Switcher (BM-SWR), click the SRC button. Scroll by turning the black wheel until S-Video appears on the screen under Source. Press the TAKE button to confirm S-VIDEO as the Source.
5. On the Black Magic Switcher (BM-SWR), click the DEST button. Scroll by turning the black wheel until ‘Mac’ appears on the screen underneath Destination. Press the TAKE button to confirm.

### Using Internal TBCs

There are certain decks which contain a built-in TBC, or time-based corrector (a device which syncs and stabilizes AV content). These decks can bypass the For.A TBC on the rack and can use their built-in TBC instead. For more information on how to toggle between internal TBCs and the For.A TBC on the rack, please refer to the chart below:

![Svideo3](https://github.com/user-attachments/assets/44173af1-95c2-4311-9fd6-462413200bd6)


Decks with a direct output to the BlackMagic Switcher (BM-SWR) include:
* Composite: Button #1 on BM-SWR
* S-Video: #2

BM-SWR outputs to the Post-Dig Monitor & Mac tower include:
* DGB1 to BM-SWR - #3
* DGB2 to BM-SWR - #4
* DVC to BM-SWR - #5
* DV1 to BM-SWR - #6
* BVH 2000 - #7

### Black Magic Switcher Routing - Composite

![Composite1](https://github.com/user-attachments/assets/eb94af9c-afa1-4a86-be15-f23db7e92417)

*The source and destination settings for the Blackmagic switcher are displayed on the mini screen.*

The Black Magic Switcher is a device that routes the digitized signal to the Mac. 

The source or “SRC” should be set to CPB (composite patchbay). The output or “DEST” should be set to “Mac”. The mini screen on the right side of the switcher displays these settings, as shown in the image below.

If either of these are not set, select either “SRC” or “DEST” with the black toggle wheel on the right side of the switcher, to find the appropriate input/output.

![Composite2](https://github.com/user-attachments/assets/e0f08625-e5cb-43c8-9b5c-41d2a2dc7ce4)

*Turning the wheel to the right of the mini screen toggles the source and destination settings on the Blackmagic Switcher.*

Once you have selected the input/output, hit the “take” button below “SRC” and “DEST”. 
(Note: if you are using the BVH-2000, DVC, DV2 or SDI output on DGB2, you will need to adjust “SRC” to the appropriate input).

Carefully load the tape, perpendicular into the deck, without forcing it. Please ensure that you are inserting the correct side of the tape into the deck, as well.

![Composite3](https://github.com/user-attachments/assets/c658ad34-44ae-492e-a764-d8b5b2e4ad57)

![Composite4](https://github.com/user-attachments/assets/2ec6947e-be96-408d-8432-86c127242187)

*Insert VHS tapes gently with the correct edge facing the deck (this edge is indicated on the tape).*

Press “Play” on the deck you are using. 

### Auxiliary VHS, Digital8 and VHS-C camcorder Connection

Some formats such as VHS-C or Digital8 are not supported in the current setup of the video rack. However, the video rack allows for camcorders to be hooked into the signal flow via s-video or composite connection. Use the input in the s-video or composite patch bays marked “aux” to avoid confusion and set the rest of the signal flow up as if it were a normal video deck in the rack. This section explains how to connect a camcorder into the video rack using an auxiliary connection. While cable formats may differ slightly based on the camcorder, the general information will remain true. Ask Lab Staff to help you find the proper cables to connect a camcorder. 

![Camcorder1](https://github.com/user-attachments/assets/e9b46129-114e-4f00-a183-47c7a760a6ad)

*Camcorder connected to the system via composite patch bay.*

### Connecting to the camcorder (ask for lab staff assistance)

1. Many camcorders have 3.5mm(⅛”) cable output that handles, video and stereo audio. It looks identical to standard, ⅛” stereo audio cable but it often breaks out into three RCA connections coded white and red for audio and yellow for video. 
2. To connect the video signal from the camcorder into the rack, a regular BNC cable will be needed along with a F-BNC to F-RCA adapter (pictured below). 

![Camcorder2](https://github.com/user-attachments/assets/5b0a672e-836b-4d1e-97b9-034af2ab3c86)

*The labeled bag that the ⅛” camcorder cord lives in. It’s found in the video and audio cables black crate in the black metal cabinet.*

![Camcorder3](https://github.com/user-attachments/assets/640b17cb-85d8-42b8-b527-1956e2c20126)

*The cable with ⅛” end and the triple RCA split.*

![Camcorder4](https://github.com/user-attachments/assets/9be975ed-c7fe-4913-8d5e-152ee97d5e37)

*BNC to RCA adapter.*

3. Connect the 3.5mm side into the camcorder. 
4. Connect the yellow, RCA video end of the cable plugged into the camcorder into the FRCA end of the adapter.
5. Connect one end of the BNC cable into the other end of the BNC-RCA adapter.

![Camcorder5](https://github.com/user-attachments/assets/ca2d7468-f119-4853-98f7-090753ece18f)

*BNC connection to the adapter shown on the left side. Yellow, RCA video connection connects to the adapter on the right.*

6. Connect the other end of the BNC cable into the back side of the composite video patch bay, behind the output label “Aux”. This can be tricky. Ensure that the end of the cable has twisted to secure the connection. It may be helpful to use a BNC removal tool to turn the cable because it could be too tight for finger access.

![Camcorder6](https://github.com/user-attachments/assets/24c698df-7a22-4e33-9e27-477e92860729)

*The ⅛” connection to the camcorder. The cord separates the signal into the two audio tracks and the video track.*

![Camcorder7](https://github.com/user-attachments/assets/e4e73c1d-472b-4468-91fb-4d5df7ce6794)

*Connection between the RCA video, RCA-BNC adapter and BNC cable.*

![Camcorder8](https://github.com/user-attachments/assets/a84facca-a59e-431a-89f6-60fd84e875c0)

*View from back side of the composite patch bay with the camcorder BNC video signal connected to input 13 or “Aux.”*

![Camcorder9](https://github.com/user-attachments/assets/b69f11b0-8b68-490c-ae12-bfe18637c053)

*BNC removal tool.*

### Connecting camcorder audio

1. RCA audio carries an unbalanced signal meaning they are susceptible to electromagnetic interference. To avoid this, the RCA audio signal will be routed through an direct input box which converts the signal to a balanced audio connection via a three pinned XLR output connection.
> a. In this case, use the blue, TwinMatch HD Dual stereo interface box. Located next to the waveform monitor.

2. Connect the two RCA audio cables from the camcorder into the TwinMatch “Unbal Inputs” matching the color of the RCA cable to the input jack of the TwinMatch. 

![Camcorder10](https://github.com/user-attachments/assets/dad29ab1-497f-4852-b43b-2c44cc54d4d1)

3. Ask lab staff to secure two FXLR to M1/4” TRS cables to connect the DI box into the audio patch bay.

![Camcorder11](https://github.com/user-attachments/assets/466b8731-f98c-4362-a0f4-b453beda4e7c)

*Two FXLR to MTRS1/4” cables.*

4. Connect the two FXLR cables into the XLR outputs of the TwinMatch that correspond to the input that the RCA audio from the camcorders are connected to (It should be input 1 or 2). Remember, audio connections are stereo pairs so one Right and Left channel constitute 1 whole input. 

![Camcorder12](https://github.com/user-attachments/assets/6a0977a5-5b8b-4aa6-8bff-1c0d93ef4f28)

*FXLR connected to XLR output on TwinMatch.*

5. Once the XLR ends of the cables are connected, connect the ¼”TRS side of the cable into the back side of the audio patchbay behind the “Aux” output (number 13). 
> a. Remember to match the right and left channel cables with the proper input on the audio patch bay. Left side goes in the top row and right goes into the bottom row.

![Camcorder13](https://github.com/user-attachments/assets/d55c92f5-dc62-4b34-8a8f-f677e00a644a)

*The XLR-TRS ¼” cable connected to the audio patch bay.*

![Camcorder14](https://github.com/user-attachments/assets/50f4c8fa-de14-454a-abea-ea3d5fdcc8e0)

*Connect the ¼” TRS connections to the back side of the audio patch bay. View from the underside of the patch bay.*

### Signal Flow for Auxiliary setup

1. Once the audio and video from camcorder have been hooked into the video rack. Route the signal as normal from the aux inputs on the patch bays.

![Camcorder15](https://github.com/user-attachments/assets/b76d4724-ddbe-424f-bcad-f5a984ccc0f2)

*Route patch bays as normal but treat the aux connection as a playback deck in the video rack.*

For video capture, go to the [Digitization](#digitization) section of this document and follow the steps.

### U-Matic Transfers

This guide outlines the steps for transferring a U-matic tape using the IS Lab video rack, covering pre-transfer requirements like tape disassembly, reassembly for baking, and cleaning playback deck heads. The document details the recommended U-matic playback and rewind decks and describes how to set up the video rack to get a signal from the U-matic playback deck to the computer for capture.

### U-matic specific actions

1. **It is mandatory that U-matic tapes are baked before playback in the video rack. Tapes must be baked for 48 hours in the Thermocenter oven** (located in the far right corner of the lab, next to the record cleaning machine). For detailed instructions on how to take apart and bake your tape, please see [Appendix E](). Please factor in the time needed to bake your tape when scheduling your appointment for a U-matic transfer in the Media Lab.

**IMPORTANT NOTE**: Rewinds are **NOT allowed on the U-matic BVU-950**, pictured at the top of the following page, because there is a significant risk that it will cause damage to this expensive machine. **You may rewind your U-matic tape using the Sony VO-5850**. Refer to the table below for info on the U-matic rewind lab cart, located across from the Video Racks.

### U-Matic rewind lab cart
![umatic cart](https://github.com/user-attachments/assets/21f7b33a-6916-4fd8-92c3-ba1f24e6a51a)


### Note on U-matic formats

The U-Matic Videocassette Recorder (VCR) plays analog 3 ⁄ 4-inch magnetic tape cassettes, a high-quality video and audio recording typically seen in the 1980s. There are three variants of U-matic tape: 
> 1. **Low-Band** is the original U-Matic format.
> 2. **Hi-Band** features increased frequency carriers which deliver superior picture quality.
> 3. **SP** is a further enhanced variation, which uses chrome tape for better video response and lower noise.

**Playback Deck Sony BVU-950:**
![umatic 1](https://github.com/user-attachments/assets/96f2f2b1-ba00-484c-ac14-ce074f73d5e3)
U-matic Playback Deck (do not rewind).

**Rewind Deck Sony VO-5850 (on Lab Cart across from video rack):**
![umatic 2](https://github.com/user-attachments/assets/ac276be4-ae24-499e-b470-90b2bd4f1ffc)
The U-matic Rewind Deck prevents the playback machine from being damaged.

## Digitization

### Vrecord workflow

### Launch Vrecord in terminal

### Configuring Vrecord settings

### Monitor the Signal

#### Perform a Test Capture

### Rewind

### Set Final Recording Settings in Vrecord

## One-Inch Open Reel Tape Digitization

### BVH2000 signal flow

### Threading the BVH-2000 VTR

### Turning on the BVH-2000

### Playing the tape on the BVH-2000

### Rewinding the Tape

## Post-Digitization 

### Rewind Deck

## DVRescue Workflow (Data Migration)

### DVRescue Resources

### GUI Navigation

### Step-By-Step: GUI

### Command Line Interface


# Appendix A: Video Rack Decks and Supported Media Formats 

## IS lab equipment supported format and identification chart](#is-lab-equipment-supported-format-and-identification-chart)

## Format Comparisons

## Timeline of Video Formats


# Appendix B: Equipment Legend

## Video Rack A and B 

## Lab Cart #lab-cart


# Appendix C: Magnetic Tape Head Cleaning Guide

## U-matic Deck Head Cleaning

## Resources

## Workflow — VCR head cleaning

### Remove outer shell of deck

### Clean interior hardware


# Appendix D: Monitor maintenance

## Resources and Definitions

### Guidelines and rules guidelines-and-rules
