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
> >[Required inspection](#required-inspection)
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
> > [Black Magic Switcher Routing: Composite](#black-magic-switcher-routing-composite)
> >
> > [Connecting to the camcorder (ask for lab staff assistance)](#connecting-to-the-camcorder-ask-for-lab-staff-assistance)
> >
> > [Connecting camcorder audio](#connecting-camcorder-audio)
> >
> > [Signal Flow for Auxiliary setup](#signal-flow-for-auxiliary-setup)
> >
> > [U-Matic Transfers](#u-matic-transfers)
> >
> > [U-matic specific actions](#u-matic-specific-actions)
> >
> > [U-Matic rewind lab cart](#u-matic-rewind-lab-cart)
> >
> > [Note on U-matic formats](#note-on-u-matic-formats)
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
> > [GUI Navigation](#gui-navigation)
> >
> > [Step-By-Step: GUI](#step-by-step-gui)
> >
> > [Command Line Interface](#command-line-interface)

[Appendix A: Video Rack Decks and Supported Media Formats](#appendix-a-video-rack-decks-and-supported-media-formats)
> [IS lab equipment supported format and identification chart](#is-lab-equipment-supported-format-and-identification-chart)
> 
> [Format Comparisons](#format-comparisons)
> 
> [Timeline of Video Formats](#timeline-of-video-formats)
>

[Appendix B: Equipment Legend](#appendix-b-equipment-legend)
> [Video Rack A and B](#video-rack-a-and-b)
>
> [Lab Cart](#lab-cart)

[Appendix C: Magnetic Tape Head Cleaning Guide](#appendix-c-magnetic-tape-head-cleaning-guide)
> [U-matic Deck Head Cleaning](#u-matic-deck-head-cleaning)
>
> [Resources](#resources)
>
> [Workflow: VCR head cleaning](#workflow-vcr-head-cleaning)
> > 
> >[Remove outer shell of deck](#remove-outer-shell-of-deck)
>
> >[Clean interior hardware](#clean-interior-hardware)

[Appendix D: Monitor maintenance](#appendix-d-monitor-maintenance)
> [Resources and Definitions](#resources-and-definitions)
> >
> > [Guidelines and rules](#guidelines-and-rules)

[Appendix E: RF Scope Monitoring](#appendix-e-rf-scope-monitoring)
> [VHS Transfers](#vhs-transfers)

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

### Black Magic Switcher Routing: Composite

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

1. **It is mandatory that U-matic tapes are baked before playback in the video rack. Tapes must be baked for 48 hours in the Thermocenter oven** (located in the far right corner of the lab, next to the record cleaning machine). For detailed instructions on how to take apart and bake your tape, please see [Appendix E](#appendix-e). Please factor in the time needed to bake your tape when scheduling your appointment for a U-matic transfer in the Media Lab.

**IMPORTANT NOTE**: Rewinds are **NOT allowed on the U-matic BVU-950**, pictured at the top of the following page, because there is a significant risk that it will cause damage to this expensive machine. **You may rewind your U-matic tape using the Sony VO-5850**. Refer to the table below for info on the U-matic rewind lab cart, located across from the Video Racks.

### U-Matic rewind lab cart
<img src="https://github.com/user-attachments/assets/21f7b33a-6916-4fd8-92c3-ba1f24e6a51a" alt="umatic cart" height="500">

Number | Deck Shorthand | Deck Make/Model | Supported Media Formats
:--- | :--- | :--- | :--- 
1 | Color Monitor | JVC TM-A130SU | 
1 | Waveform Monitor | Compuvideo | 
2 | U-matic Rewind Deck | Sony V0-5850 | U-matic Tape

### Note on U-matic formats

The U-Matic Videocassette Recorder (VCR) plays analog 3 ⁄ 4-inch magnetic tape cassettes, a high-quality video and audio recording typically seen in the 1980s. There are three variants of U-matic tape: 
> 1. **Low-Band** is the original U-Matic format.
> 2. **Hi-Band** features increased frequency carriers which deliver superior picture quality.
> 3. **SP** is a further enhanced variation, which uses chrome tape for better video response and lower noise.

**Playback Deck Sony BVU-950:**

<img src="https://github.com/user-attachments/assets/96f2f2b1-ba00-484c-ac14-ce074f73d5e3" alt="umatic 1" height="400">

U-matic Playback Deck (do not rewind).

**Rewind Deck Sony VO-5850 (on Lab Cart across from video rack):**

<img src="https://github.com/user-attachments/assets/ac276be4-ae24-499e-b470-90b2bd4f1ffc" alt="umatic 2" height="400">

The U-matic Rewind Deck prevents the playback machine from being damaged.

## Digitization

### Vrecord workflow

The IS Media Preservation Lab's video rack workflow uses Vrecord for all video tape transfers. Vrecord is an open-source software designed to capture video signals and turn them into digital files. Vrecord is maintained by the Association of Moving Image Archivists (AMIA) Open Source working group.

Vrecord is pre-installed on the video transfer station computer in the Media Lab and runs via command-line. For comprehensive documentation, updates, and troubleshooting resources on the Vrecord software, refer to the [AMIA Open Source GitHub repository for Vrecord](https://github.com/amiaopensource/vrecord).

This section will:
   * Provide step-by-step instructions for video capture using Vrecord, including: 1) setting up Vrecord prior to capture, 2) the capture and monitoring transfer process, 3) post-digitization file access, and 4) file storage and management guidelines 
   * Outline specific settings and options for your transfer in the Vrecord GUI
   * Explain how to monitor the video signal before digitization using the Waveform monitor in the video rack and on the post-digitization end using Vrecord’s scopes in the passthrough and record windows
   * Provide instructions for setting the NTSC broadcast range and how to adjust the time-based correction (TBC) to ensure  the video signal is within range. 

### Launch Vrecord in terminal

Launch Vrecord in terminal
1. Open Terminal, type **vrecord -e**, then hit enter on the keyboard.

<img src="https://github.com/user-attachments/assets/e48a18ab-e6aa-45c3-abae-970963b18952" alt="terminal" height="200">

> a. Terminal should look like this:

<img src="https://github.com/user-attachments/assets/12b87395-de23-45f3-b46c-136b511752bd" alt="terminal2" height="300">

*Vrecord Terminal*

### Configuring Vrecord settings

1. At this stage, the Vrecord graphical user interface (GUI) has launched and appears on your screen. Confirm the following default configurations listed below are set for your video tape prior to transferring:
> a. Input utility - ffmpeg
>
> b. Video input - SDI
>
> c. Audio input - SDI Embedded Audio
>
> d. Audio Channel Mapping - 1 Stereo Track (from channels 1 & 2)
> > i. Note: this may be adjusted depending on your tape. Visit [Vrecord github documentation settings](https://github.com/amiaopensource/vrecord/blob/main/Resources/Documentation/settings.md) for further instructions.

<img src="https://github.com/user-attachments/assets/ddb22a6d-6f4b-4355-b3c7-8a82ee7e5fa5" alt="vrecord" height="400">

*Vrecord’s graphical user interface (GUI), containing various settings for the digitization process.*

> e. On the second line of the Vrecord GUI, set your desired video file type and codec. For example, FFVI Version 3 and Matroska file, 4 slice count with FLAC audio are suitable choices.
> > i. Note: Certain codecs are incompatible with each other and errors may appear in the “Errors & Warnings” box. Some selections may require additional fields on this line. For example, Matroska has the option to embed digitization logs on the left side. Additionally, FFV1 version 3 lets you choose the slice count (the higher the slice count the more data and the larger the file).
> >
> > ii. [AMIA’s analog digitization documentation](https://github.com/amiaopensource/vrecord/blob/main/Resources/Documentation/analog_digitization.md) has more info about these selections as well as file specifications standard used by archives.
>
> f. On the line below, “Playback Options” lets you choose how you monitor your transfer in the record and passthrough windows. The settings can be different for the playback and record windows.

<img src="https://github.com/user-attachments/assets/4013b0ed-1ace-40f7-8654-25c32cf80023" alt="terminal3" height="300">

*IS Lab recommends the settings seen above for video digitization.*

> > i. “Unfiltered” will only display the playback image. 
> >
> > ii. The “audio+video” option (shown below) is the most commonly used setting, and shows a fairly comprehensive view of video monitoring tools, including range pixels, waveform monitor, vectorscope, and audio scopes in the top left corner. Refer to the [video views section](https://github.com/amiaopensource/vrecord/blob/main/Resources/Documentation/settings.md#video-views) of the Vrecord documentation for more info.

<img src="https://github.com/user-attachments/assets/b0eb663f-4f05-4a9a-a577-89e6189b1f5e" alt="vrecord2" height="400">

*The Vrecord passthrough window allows one to monitor the video playback prior to digitization*

> g. “Frame MD5s” prompts the software to generate a checksum for every frame of the capture. A checksum is a unique identifier for digital files which guarantees fixity, or the integrity of the information. This is recommended and highly useful for preservation. More info about checksums can be found [here](http://dericed.com/papers/reconsidering-the-checksum-for-audiovisual-preservation/).
>
> h. For the QCTools XML?, Vrecord can create an XML file accompanying the transfer that contains a measurement of characteristics of the video signal (such as luminance, color saturation, audio levels, etc. This is also recommended for preservation.
>
> i. In the last line of the window, set your file destination, file name, and name of the person digitizing. If applicable, set the record time, which will automate Vrecord’s termination of your capture.
> > **i. Vrecord will not let you record if there is no file name.**

### Monitor the Signal

Follow the format specific workflow and ensure that you have the signal from your deck routed to the Mac video transfer station correctly.

1. Press “play” on your deck and then hit the “Passthrough” button on the bottom of the Vrecord GUI to open the signal monitoring window.

<img src="https://github.com/user-attachments/assets/2aa6e930-2ca8-4523-9fd1-85b6653251ff" alt="vrecord3" height="75">

*The Record and Passthrough buttons on the Vrecord GUI*

   * The Passthrough window like the one shown above will open with your video capture shown in the top center of the window.

2. Once you have the passthrough window open, the whole station should look like this:

<img src="https://github.com/user-attachments/assets/ec0f73c0-0284-402f-9a52-4e3af4998c6b" alt="audio transfer station" height="300">

*An ideal setup for the Video Transfer Station setup*

3. Signal should be coming from the deck through the Pre-Digitization Monitor (on the left in the video rack).
   * The signal should appear on the waveform monitor (below pre dig mon1).
   * The signal should also show up on post dig monitor 2 on the right. Finally, your signal should make it through to Vrecord. You should hear the audio of the tape coming through the two Roland speakers behind the computer monitor.

<img src="https://github.com/user-attachments/assets/cf8f39ef-4f01-49c0-a901-01b5f6144dc5" alt="scope" height="300">

*The yellow lines above indicate the NTSC broadcast range. Information must fall within this range to be captured*

4. Check the waveform monitor to ensure the signal is within the broadcast range (space between the two yellow lines seen above).
   * The face of the waveform monitor shows the luminance IREs of the video signal passing through. This is a measurement of the brightness of the signal.
   * For NTSC, the broadcast standard used in the U.S, the upper limit is 100 IRE and the lower border of broadcast range is 7.5 IRE (indicated by the red dotted line on the waveform monitor.) If the signal is above or below the line, then it is out of range and cut off.
   * Vrecord has a digital waveform monitor on the passthrough window.

5. Get the signal in range.
   * Use the “Video Level” and “Chroma Level” knobs on the TBC to bring the signal into the NTSC broadcast range.

<img src="https://github.com/user-attachments/assets/c441c106-e9e5-4fed-ae4c-dd7a751374f5" alt="tbc" height="200">

*“Video” and “Set Up” knobs on the TBC*

   * Start with the knobs in the neutral position (the place where they softly click. This might not be the exact center).
   * Use the “Video Level” and “Chroma Level” knobs on the TBC to adjust the signal to bring into NTSC broadcast range. 
>   1. The “Video” control adjusts the luma, or the brightest part of the waveform. It changes the amplitude of the wave (squishes or stretches it).
>
>   2. The “Chroma Level” knob boosts black in the video signal  (moves the entire thing up or down).
>
>   3. **Do not touch the other two knobs on the TBC.**
   * Fast forward to a part of the tape with content. Try to use a shot with both pure black or white to make your adjustments.
   * The signal is lower in the above photo but some of the waveform is below the 7.5 IRE so it is a bit too low. Adjust the “Set Up” knob to move the bottom of the waveform into range.
   * Vrecord has overlays visible in the passthrough window that also will indicate when the signal is out of NTSC broadcast range. Vrecord will color out of range values as yellow pixels in the digital monitor.

<img src="https://github.com/user-attachments/assets/40fbda70-79a6-4fc6-b9c8-3e49b1351d09" alt="vrecord12" height="300">

*Out of range values will turn yellow in the digital monitor in Vrecord.*

   * In the above photo, the lowest luminance values in the frame are below 7.5IRE, as indicated by Vrecord’s yellow coloration of those pixels.
   * In range signal on the waveform monitor should look like the image below:

<img src="https://github.com/user-attachments/assets/96560b98-e808-40d7-8e00-802f1fd0982a" alt="scope2" height="300">

*Waveform Monitor Safe Broadcast Range*

   * When the Waveform is in range on the Vrecord passthrough window, it will look like the image below.

<img src="https://github.com/user-attachments/assets/5109e325-511f-4b33-9fd4-d42f4dd8bb4b" alt="vrecord13" height="300">

*Optimal Waveform in Vrecord*

6. Monitor the video signal through several different scenes or camera angle changes to ensure it remains in range. Light levels in difference shots may be different and could cause the signal to go out of range.
   * Set the TBC so the signal stays in range through as much of the tape as possible. If it is impossible to keep the signal in range through the different parts of the tape, you will have to break the transfer up into pieces.

#### Perform a Test Capture

> a. Hit “esc” or “q” to exit the passthrough window and return to the Vrecord GUI.
> > i. You can press the up arrow in the terminal and it will type the last command you gave it
>
> b. Check your file settings to see that they are what you wanted.
>
> c. You might want to name your capture “test capture” or words to that effect.
>
> d. Press the “record” button and Vrecord will send you back to the terminal.

<img src="https://github.com/user-attachments/assets/5ec75fc9-821f-42b0-b550-1e85a1babf78" alt="terminal4" height="300">

*The command line terminal is used to launch Vrecord and to begin the process of video digitization*

7. When you see the window above, press “enter” to start recording.

<img src="https://github.com/user-attachments/assets/08aac511-8328-453f-be7a-b90179af3000" alt="vrecord14" height="300">

*The window above appears during the digitization process*

8. Capture the signal for ten seconds. Press “esc” or “q” to finish recording.

<img src="https://github.com/user-attachments/assets/003671f2-50b4-4b3d-9c0f-78f0331f286c" alt="vrecord15" height="300">

*The terminal will appear once the recording is complete*

9. Vrecord will send you back to the terminal when you stop recording.
10. Press “Stop” on the deck you are using.
11. Navigate to the location you designated in Vrecord and playback your file (it might look like this image below). Double click to play. You may have to “command +click” and select “Open with…”and choose “VLC Media Player” to playback your file.

<img src="https://github.com/user-attachments/assets/7bd8d37b-086f-4ece-b99a-02916667342c" alt="file" height="250">

*The test capture can be played back with VLC Media Player*

### Rewind

* Once you have successfully set the TBC for your capture, put your tape in the designated rewind deck (if the lab has one for your format).
* Rewind to the beginning. The start of the tape might be before the 00:00 mark in the negatives.

### Set Final Recording Settings in Vrecord

* Return to the Vrecord GUI and double [check your file settings again](#configuring-vrecord-settings).
> i. Rename the file if needed.
* Once everything is set up, press the “record” button in the GUI and then “enter” on the keyboard. 
* Press “Play” on the deck and monitor the capture while it’s playing.
* Play tape til the deck stops. Hit “esc” or “q”
* Navigate to your folder where the file was saved. Test the playback of the file by double clicking.
* Leave the terminal window open. If Vrecord is producing a QCTools report, this can take upwards of half an hour to generate. This is the percentage number shown at the end of the transfer.

## One-Inch Open Reel Tape Digitization
1-inch Type C is an open reel analog helical scan video tape used for professional video and broadcast television. This guide outlines the steps for transferring an 1-inch open reel tape using the **Sony BVH 2000 Videocorder.**

This video format is open reel meaning the tape is not protected by a plastic cassette shell unlike many formats. When using one inch tape, it’s important to avoid touching the surface of the tape. It’s recommended that gloves are worn when threading tape onto the deck. 

**Resources:** [BVH2000 Manual Download](https://www.manualslib.com/manual/1741663/Sony-Bvh-2000.html)

![bvh1](https://github.com/user-attachments/assets/168ec447-b313-4e43-9f87-a8a339a3738e)

![bvh2](https://github.com/user-attachments/assets/3ca62d41-cca5-4e88-910d-6853644b4b16)

*Sony BVH-2000 machine (top) and its user interface (bottom)*

### BVH2000 signal flow

The BVH-2000 has a slightly unique signal flow to the other decks in the video rack. It has a dedicated time base corrector, rf scope, vectorscope. The signal from the 1” tape machine deck is digitized by a dedicated Aja analog to digital mini converter, the same model as the one used for the composite patch bay. The signal only needs to be routed on the Black Magic 20 x20 digital switcher. The signal will not play through the CRT monitors in the video rack or the waveform monitor. 

![bvh3](https://github.com/user-attachments/assets/71f1544c-50b8-49dc-aaa8-a4f046924756)

*Routing the signal flow for 1” video tape on the Black Magic switcher.* 

### Threading the BVH-2000 VTR

1. Threading the tape on the BVH works much like the Kinetta or an open reel audio deck. Tension must be applied to the takeup reel side to keep the tape in position.
2. The signal is recorded on the shiny side of the tape (opposite of film and audio). Usually broadcast tapes are recorded heads out and with the base side facing out. Usually broadcast tapes will have labels on the reels for identification. If wound correctly, the side with the labels should face out when on the supply side.
3. Threading on the machine should be performed with powder free gloves to avoid unnecessary touching of the tape. 
4. Place the tape reel lining up the teeth with the notches on the hubs of the VTR. 
5. The tape should come off the outside of the supply reel and mirror that by joining up with the outside of the takeup reel.

![bvh4](https://github.com/user-attachments/assets/26ed30ec-2ee9-4917-b881-408f0135bc33)

*Tape threading diagram with the line indicating the path of the tape.*

6. Look at the arrows on the BVH for guidance on how to thread the tape. The tape should go around the drum. 

### Turning on the BVH-2000

1. Many power switches must be activated to turn on the BVH-2000. Look for the pieces of white tape next to the switches to turn on the unit and the accompanying monitors and equipment.
2. Start with the main power switch. This is located in the bottom cabinet on the right side. Do not turn on the switch mark service. 
3. Then turn on the time base corrector. The metal box to the left of the main power switch in the bottom cabinet is the TBC. Flip the black switch.
4. Then turn on the VTR itself. This switch can be found on the floor next to the VTR on the left side. 

### Playing the tape on the BVH-2000
1. Once tape is in position. Press the “Play” button. The head will begin to spin rapidly and the reels will advance the tape. 
2. Make sure the CRT monitor, vectorscope and RF monitor are turned on to see the signal.
3. If the tape is moving for a while, do not worry. Many 1” Tapes are professional broadcast tapes recorded with lots of empty tape at the head and tail. 
4. Usually the 1” tapes have bars and tone recorded at the beginning. 
5. When the bars and tone begin playing, use them to make sure the signal is in range. 
6. The tone should play at 0dB. Look at the level meters for the right and left channel located above the play button and below the video drum.
7. Once the signal has been determined to be in range.
8. Follow instructions in the [Digitization](#digitization) section of this document. During playback and monitoring, the signal will not play through the CRT monitors in the video rack or the waveform monitor. 


### Rewinding the Tape
1. To rewind. Press “Stop.”
2. Remove the cover from the drum/tape path area. 
3. Press “shuttle.”
4. Carefully turn the black wheel counterclockwise to begin rewinding the tape. Start slow and watch the tape carefully so it does not get stuck on any of the parts. 
5. Turn the wheel further counterclockwise to speed up the reels. The audio head will tilt down and away from the tape. 

## Post-Digitization 

The following list provides recommendations for file management and storage, as well as considerations for digital preservation:

1. After the digitization process, transfer your file(s) to the server.
> a. This process might take a few hours for large files, please be patient and check on progress often.
2. After transferring your file(s) onto the server, delete them off the desktop. 
> a. Do not delete other peoples files and speak with media lab staff if there are any unknown files that need to be deleted.
>
> b. As per Media Lab policy, **all files on the desktop will be deleted at the end of each Friday**. This practice helps maintain a clean and efficient workspace. 

### Rewind Deck

Please use the Samsung DVD/VHS deck, located on top of Video Rack A, for all VHS Rewinds.

## DVRescue Workflow (Data Migration)

DVRescue is an open source, free software, dedicated to developing procedures and tools that will support migrating data from DV tapes into digital files suitable for long-term preservation. 

### DVRescue Resources

* Documentation by MiPoPS on [DV Rescue](https://mipops.github.io/dvrescue/index.html)

### GUI Navigation

How to capture a DV video tape using DVRescue.
1. In the “Capture” tab from the left-hand menu, you will see a large box in the center of the screen showing your capture window:

![dvrescue1](https://github.com/user-attachments/assets/a101590f-37ac-47b6-b70f-c0a187b62e5b)

DV Rescue Navigation Menu
> a. if you do not have a deck connected or if the deck is off, the message “No DV Deck Connected” will display on your screen.
>
> b. If the deck is successfully connected, the make and model of your DV deck should appear above the capture playback window. If you have more than one deck connected, multiple players will appear.

2. Once you have specified a file location and name for your capture, the file name will also appear in the upper right hand corner of the corresponding deck being used to capture it.
3. The player buttons below the capture window can control the deck, and the icon to the right of the player buttons indicates the current status of the deck.
4. Counters underneath the player buttons track video by frame number, timecode, and the actual record time that has elapsed.
5. The graph underneath the counters tracks frames with error concealment for audio and video. If you hover your cursor over the graph, a tooltip will display the running total of frames containing errors.

### Step-By-Step: GUI

1. In the DVRescue GUI, select “Capture” from the list on the left hand side. If you do not have a deck connected or if the deck is off, you will see the following message.
2. Turn on your DV deck. The make and model of the deck should appear above the capture playback window.
3. If you have more than one deck connected, multiple players will appear in the Capture tab. Please select the one you want to use by clicking on the name of the deck.
4. If your deck has a Remote/Local setting, make sure it is set to “Remote” before initiating the capture.
> a. Please note that some decks are known to have different behavior. See the DV Deck Guide for deck-specific information.
5. You can use the player buttons to control the deck and preview the content on the tape.
6. When ready, click the record button to initiate the transfer.
7. A pop-up window will open. Here you can navigate to the location where you would like to save the files created during capture, including the video file itself and all of the logs. Click the name listed in the field for the “output directory” and then select the directory.
8. Type in the tape identifier as the file name and click OK.
9. Deck control will automatically start recording the tape. While it records, you can preview the video in the GUI player.
> a. Feel free to start more than one recording at the same time. You can monitor all of your simultaneous recordings.
>
> b. When DVcapture encounters an error, it will automatically rewind and try to capture the frames containing errors (more than once if needed; if unable to capture full frames, after 3 attempts, it will move on) to the next portion of the tape.
10. When the recording ends or the deck reaches the end of the tape, DVRescue will stop capturing and automatically initiate rewinding the tape. If you would like to end the capture before the end of the tape or if there is a large chunk of recorded-over blank space, click “Stop” to end the capture. (DVRescue will continue to register blank tape as content if there is timecode or recording time left over from erasing or recording over previous content)
11. Once you are done capturing files, you can immediately click on the “Analysis” tab to perform quality control on the files. All of the files captured during your current session will be populated in the list in the Analysis tab. Please see the DV analysis documentation for instructions and tips for reviewing DV files.

### Command Line Interface

All of these flags and options can also be viewed by typing dvrescue -h into the command line window.

* **--capture** = Launch capture.
> * Is the default if no --cmd option is provided.
>
> * Usable only if input is a device.

* **--in-control** = Include an integrated command line input for controlling the input.
> * Usable only if input is a device.

* **--list_devices** = List detected devices and their indices.
* **--statusl** = Provide the status (playing, stop...) of the input.
> * By default device://0 is used.
>
> * Usable only if input is a device.

* **--cmd [value]** = Send a command to the input.
> * By default device://0 is used.
>
> * Usable only if input is a device.
>
> * Value may be:
> > * play = Set speed to 1.0 and mode to play.
> >
> > * srew = Set speed to -1.0 and mode to play.
> >
> > * stop = Set speed to 0.0 and mode to no-play.
> >
> > * rew = Set speed to -2.0 and mode to play.
> >
> > * ff = Set speed to 2.0 and mode to play.

* **--mode [value]** = Send a command to the input with the specified mode.
> * By default device://0 is used.
>
> * By default value is n if speed is 0 else p.
>
> * Usable only if input is a device.
>
> * Value may be:
> > * n = Set mode to no-play.
> >
> > * p = Set mode to play.

* **--speed [value]** = Send a command to the input with the specified speed (float).
> * By default device://0 is used.
>
> * By default value is 0 if mode is no-play else 1.
>
> * Usable only if input is a device.

* **--rewind-count [value]** = Automatically rewind to last good frame and capture again, value times.
> * Usable only if input is a device.

* **--rewind** = Same as --rewind-count 1
* **--rewind-basename** [value] = Base name of files storing buggy frames per take
> * Default is the output file name.

# Appendix A: Video Rack Decks and Supported Media Formats 

## IS lab equipment supported format and identification chart

The images shown below depict various Media Formats. In each row, the media format corresponds to a particular deck, or playback machine. Once you have identified your media format, find the deck shorthand. This acronym has its own label on the Audio Rack, and will allow you to more quickly identify the location of the deck on the audio rack. Please note that some media formats are supported by multiple decks.

Format | Image | Deck Shorthand | Deck Model # | Description of Media Format
:--- | :---: | :--- | :--- | :---
**VHS** | ![appendixa1](https://github.com/user-attachments/assets/756e8711-b035-4d86-a397-1da71ff64158) | **VHS1, VHS2** | Sony SLV-675HF, Sony SLV-AX10 | 
**SVHS** | ![appendixa2](https://github.com/user-attachments/assets/3e2523ca-b51c-47a1-a90e-4aae495380af) | **SVHS** | Panasonic AG-7750 |VHS and SVHS look the same. Players are upwardly compatible, meaning SVHS players can play VHS, not the other way around.
SVHS has a higher video quality than VHS
**U-matic** | ![appendixa3](https://github.com/user-attachments/assets/dab723e2-324b-4678-a85b-721cb0aaaa82) | **UMA** | Sony BVU-950
(UMA) | U-matic is a ¾ inch type of VCR cassette made by Sony. U-matic tapes need to be baked before playing. This prevents damage to the machine. Cassette size: Small (7¼" × 4⅝" × 1⅕"), Large, or full-sized, (8⅝" × 5⅜" × 1⅕") 
**Hi8** | ![appendixa4](https://github.com/user-attachments/assets/28ddc7dc-d72f-453f-9d18-e06b8a236d96) | **Hi8** | Sony EVO-9800A | Hi8 is a video format made by Sony. It supports a digital audio track. This format was created as an improvement over Video8 and VHS.  
**Betamax (Beta)** | ![appendixa5](https://github.com/user-attachments/assets/9e7ef173-4936-4739-b21c-f296c7d34cce) | **SBM** | Sony SL-HF2000 | Ubiquitous half inch video tape format rival to VHS made by Sony. Cassette size: 6⅛" × 3¾" × 1".
**Betacam** | ![appendixa6](https://github.com/user-attachments/assets/740fa7c2-061a-4cfd-adc5-82d15f42f54a) | **DGB1, DGB2** | Sony DVW-A500, Sony J30-SDI | Half-inch magnetic video cassette tape used for the Sony Betacam line of video recording devices. Cassette size: 6¾" × 4⅜" × 1⅕".
**Betacam SP** | ![appendixa7](https://github.com/user-attachments/assets/a87e92db-3913-4c64-83f6-79c7da027421) | **DGB1, DGB2** | Sony DVW-A500, Sony J30-SDI | Half-inch magnetic video cassette tape used for the Sony Betacam line of video recording devices. Like SVHS, Betacam SP was invented to provide superior performance compared to its predecessor.
**DigitalBetacam (Digibeta)** | ![appendixa8](https://github.com/user-attachments/assets/e975bc29-0ca8-47e4-8fa6-34515b5acc82) |  **DGB1, DGB2** | Sony DVW-A500, Sony J30-SDI | 

## Format Comparisons

**VHS vs.SVHS vs. D-VHS**

![formcomp1](https://github.com/user-attachments/assets/142cfccf-f75f-4f85-a231-ef7e38b44738)

![formcomp1_5](https://github.com/user-attachments/assets/a047a1d7-dfdd-436a-8870-169b84775f89)

VHS is an analog video cassette format widely used for home video recording and playback. S-VHS is an improved version of VHS, offering higher video quality and enhanced resolution. D-VHS, on the other hand, is a digital version of VHS, providing superior image quality and supporting digital audio. 

VHS, S-VHS, and D-VHS can be distinguished by the screw positions on the back of the tape. D-VHS and S-VHS both have a screw, where VHS does not.

S-VHS tapes are usually identifiable by the “S-VHS” logo, typically seen on the front of the tape housing (see above).

**VHS vs VHS-C**

![formcomp2](https://github.com/user-attachments/assets/0d4daaad-c139-43d7-aac4-25f9ee5d43b8)

VHS-C is another magnetic video tape format not to be confused with VHS tapes. The VHS-C tapes are smaller and were typically used in camcorders and are a common home video format. VHS-C tapes cannot be played in any of the VHS decks in the video rack without an adapter. A VHS-C tape alongside a regular sized VHS adapter is shown below. 

**DVCAM vs. miniDV**

![formcomp3](https://github.com/user-attachments/assets/a3fe7c87-b1e2-4176-8119-5a3d0743c992)

**miniDV**:
Panasonic HD1200A (DV1);
Sony DSR-1500A (DV2)

**DVCAM**:
Sony DSR-1500A (DV1)

* Panasonic requires DVCAM adapter

**SVHS/VHS vs. Hi8 vs. VHSC vs. miniDV**

![formcomp4](https://github.com/user-attachments/assets/2f72b742-d9a1-40cb-9fb7-8f1303df5529)

VHSC not supported (adapter needed). See above for decks which support the other three formats.

**U-matic vs. VHS vs. Betacam**

![formcomp5](https://github.com/user-attachments/assets/eb7ea299-eefb-46b5-b5cd-89bf15649824)

**U-matic vs. DigitBeta**

![formcomp6](https://github.com/user-attachments/assets/25fddf2a-45d6-4b68-a5ff-715c986ed355)

## Timeline of Video Formats

Format | Year Invented | Year Commercially Available | Obsolescence
:--- | :--- | :--- | :--- 
**VHS** | 1976 | In the 50s and 60s, magnetic tape recordings were very expensive and only used by professionals. It was not used domestically until the mid-70s, after the birth of VHS. | Last video release: 2006 Last VHS player: 2016
**SVHS** | 1987 | 1987. SVHS offered better luminance and resolution than VHS. | Same as above 
**U-matic** | 1969 | 1971. U-matic was one of the first video formats to contain tape within a cassette. | 2000
**DVCAM** | 1996 | 1996 | Present. Widely used in professional settings.
**HDCAM** | 1997 | Present | Sony still makes HDCAM stock as of 2025.
**DVCPRO** | 1995 | Present | Still in use but not widely used. 
**miniDV** | 1995 | 1995 | 2009 
**Hi8** | 1989 | 1989 | 2007
**Laserdisc** | 1972 | 1978 | 2001
**Betamax (Beta)** | 1975 | 1975- late 1980s. It was widely available in consumer, industrial and educational environments during this time period so lots of Beta tapes still exist. Despite it’s superior signal quality, Betamax lost out to VHS in the format war and Beta is obsolete today. | 1990s
**Betacam** | 1982 | Present | While Betacam tapes are no longer being manufactured, Betacam SX and Digibeta decks are still being produced which have backwards compatibility to Betacam.
**Betacam SP** | 1986 | Present | Same as above 
**Digital Betacam (DigiBeta)** | 1993 | Present | Decks and tapes are still in production but it’s difficult to know how much longer this will happen.

# Appendix B: Equipment Legend

Please see the following page for the legend. Refer to the [Equipment Legend Photoshop files](https://drive.google.com/drive/folders/1u7acSQs9-b63z31hMhXAP25H53Qokiz1?usp=drive_link).

## Video Rack A and B 

![Appendixb1](https://github.com/user-attachments/assets/76480f50-72e3-4372-a58f-03c0d3ed78e9)

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

## Lab Cart

<img src="https://github.com/user-attachments/assets/21f7b33a-6916-4fd8-92c3-ba1f24e6a51a" alt="umatic cart" height="500">

Number | Deck Shorthand | Deck Make/Model | Supported Media Formats
:--- | :--- | :--- | :--- 
1 | Color Monitor | JVC TM-A130SU | 
1 | Waveform Monitor | Compuvideo | 
2 | U-matic Rewind Deck | Sony V0-5850 | U-matic Tape


# Appendix C: Magnetic Tape Head Cleaning Guide

Tape heads require regular maintenance and cleaning to ensure optimal signal quality and successful transfers of magnetic media to digital formats. Particles from magnetic media build up on recording and playback heads and need to be cleaned using paper, lint-free swabs, and isopropyl alcohol. This guide provides instructions on how to clean the record and playback heads of VCRs and audio cassette players.

**Pre-cleaning instructions: Do not attempt to clean the heads without an IS lab staff member present.** Before beginning your transfer project, contact a lab staff member to confirm the heads have been recently cleaned. If transferring more than a couple of tapes, plan to work with lab staff and clean the heads throughout your project to ensure optimal signal quality.

## U-matic Deck Head Cleaning

1. Head cleaning is only to be performed by lab staff. Please find a staff member and they can help you to clean the U-matic heads. 
2. Ensure the deck is turned off.
3. Pull the U-matic deck drawer out of the video rack. Lift the cover off the deck (the screws should be taped to the top of the cover. It should be left unscrewed). 

![AppendixC1](https://github.com/user-attachments/assets/60393db9-c90e-4ee4-87f3-f6173a0e732d)

*U-matic deck with cover (cover screws taped to the top of the cover).*

![AppendixC2](https://github.com/user-attachments/assets/9bf469d8-1195-4754-ae47-a55e032c4d7d)

*U-matic deck with cover removed.*

4. Carefully lift the panel above the main cavity in the deck to expose the drum.

![AppendixC3](https://github.com/user-attachments/assets/c8533577-0488-4e96-aa05-21973e38a730)

*The green circuit board must be gently lifted to access the drum.*

![AppendixC4](https://github.com/user-attachments/assets/b017fd0a-38ed-4538-8c4f-af7ff9f80e7c)

*Removing the roof of the U-matic player provides access to the drum of the machine. Located around the drum are the video heads, which interpret information on the Videotape. The heads are periodically cleaned to ensure an accurate and smooth video transfer.*

5. Use cut strips of paper to clean the heads. Soak the paper strips with 99% isopropyl alcohol. Gently rotate the drum so that heads pass under the alcohol soaked swab.
> a. This may take a while as dirt gradually becomes saturated by the alcohol. Monitor the color of the swabs as it may take multiple passes to get dirt out.
>
> b. When swabs are covered in dirt, grab a fresh swab.
>
> c. Never move the head cleaner vertically against the video heads.
>
> d. Never touch the heads with hard objects.
>
> c. Don’t touch heads while they are in motion. 

6. Clean all stationary tape guides and surfaces with which the tape comes into contact.
> a. Keeping in mind the rule of thumb: clean plastic or rubber parts with water and metal parts with alcohol. 
7. To Push the shelf back into the rack, unlock the drawer using the switches on the tracks of the drawer.

![AppendixC5](https://github.com/user-attachments/assets/0e192356-1b83-487e-88a0-57707b7229ac)

*When sliding the U-matic player back into place, the switches on either side of the metal track need to be pressed down for the rack to slide back.*

## Resources

[VCR Head Cleaning Video](https://www.youtube.com/watch?v=5ClXrffkN3M)
* Using a swab/shammy
[VCR Head Cleaning Video](https://www.youtube.com/watch?v=Ew1T8p3wYXE)
* Using paper

## Workflow: VCR head cleaning

Do not attempt to clean heads without a lab staff member.

Gather cleaning supplies:
* 99% Isopropyl alcohol
* Printer paper
* Lint-free swabs

### Remove outer shell of deck

1. Ensure the deck is unplugged.
2. Unscrew screws on upper shell of the deck. Screw location and quantities will vary depending on the VCR.
3. Place screws onto a piece of tape and place in a secure place to ensure they don’t get lost. 
4. Once all screws have been removed, pull backward on the outer shell and place to the side.

### Clean interior hardware

1. Secure your cleaning materials: Locate the 99% isopropyl alcohol and the bag of foam swabs from the gray cabinet labeled “Need Something?” in the Media Preservation Lab. Cut or rip a sheet of printer paper into small scraps about 1-2 inches long.
2. Generously saturate the foam swab with isopropyl alcohol.
3. Locate the shiny, cylindrical drum of the machine. Do not touch the side of the drum directly with your finger (the oils can ruin subsequent transfers). 
4. Inspect the drum. Towards the bottom of the drum is a line of small, rectangular indentations. Inside each indentation is a line of copper pins. These are known as the heads, which gather dirt and dust over time. Inspection with a flashlight may aid their identification.
5. Using the foam swab, apply moderate pressure to the side of the drum along the line of heads, keeping the swab still. At the same time, use your index finger on the top of the drum to spin it in a circle. Your index finger may only touch the top of the drum, not the side.
6. Continue this process for a few minutes. Dust and dirt will gather on the swab.
7. Repeat this process with the paper. Generously soak a scrap of paper with isopropyl and press it to the side of the drum, along the line of heads. Rotate the top of the drum with your index finger. You should feel the heads passing under the paper. This will ensure the most thorough cleaning of the heads. You should see dust and/or dirt gathering on the paper scrap.
8. Repeat this process multiple times, starting with the swab and continuing with the paper.

# Appendix D: Monitor maintenance

Video monitors are used to display elements in the video system. These units are essentially high-quality TV receivers with special inputs and modifications that permit them to accept video and sound signals through the appropriate VTR, camera, and audio connectors. Monitor/receivers can reproduce both sound and picture, commonly referred to as a TV Monitor or just Monitor.

![AppendixD1](https://github.com/user-attachments/assets/db06bf96-313e-4906-aa4f-7bd13646937b)

*Right to left: Ikegami TM10-17RA (pre-digitization monitor) and Ikegami TM9-1D (post-digitization monitor).* 

![AppendixD2](https://github.com/user-attachments/assets/9e12e1ba-021e-4962-969a-4f48c945fa16)

*Pre-Digital Ikegami [TM10-17RA](https://crtdatabase.com/crts/ikegami/ikegami-tm10-17ra) High resolution 9” broadcast monitor with a 450 TVL shadow mask tube. It displays visible scan lines in 240p. It accepts composite, S-Video, RGB, and component video signals, and has a single speaker for audio.*

![AppendixD3](https://github.com/user-attachments/assets/fef455b2-28cc-4de1-b442-c71f04023148)

Ikegami [TM9-1D](https://crtdatabase.com/crts/ikegami/ikegami-tm9-1d) Portable 9" broadcast monitor with a low TVL slot mask tube, dual composite inputs, and a built-in SDI input card.

## Resources and Definitions

[The Video Guide on TV Monitors and Video Projectors](https://cool.culturalheritage.org/videopreservation/vid_guide/8/8.html)

[Adjusting the Waveform and CRT Monitors (1)](https://docs.google.com/document/d/1V0Oy_nvFDwxHlRTdb6wcAakqQPfynfun/edit?usp=sharing&ouid=100964043909374250980&rtpof=true&sd=true)

[Adjusting Your CRT's Color](https://crtdatabase.com/faq/crt-color-adjustment)

[List of CRTs](https://crtdatabase.com/)

Dropout:  A term used with analog videotape recorders.  A brief signal loss caused by a tape head clog, defect in the tape, or debris that causes an increase in the head-to-tape spacing. Missing magnetic material can also cause a dropout. A video dropout generally appears as a white spot or streak on the video monitor. When several video dropouts occur per frame, the TV monitor will appear snowy. The frequent appearance of dropouts on playback is an indication that the tape or recorder is contaminated with debris and/or that the tape binder is deteriorating. 

### Guidelines and rules

* Ensure monitors are turned off after use to avoid degraded picture quality. 
* When transporting monitors, two people are needed. Take a photo of how cables were plugged in to have a record for your own convenience. Remove cables from the monitor. Two people lift the monitor onto a wheeled cart. Do not carry monitors longer than placing it on the cart. Gather cords needed.

![AppendixD4](https://github.com/user-attachments/assets/1331fcae-f9e4-4306-be46-a91c6008a99f)

*Example of how to plug in a Post-Digital Monitor (left) and Pre-Digital Monitor (right)*

# Appendix E: RF Scope Monitoring

RF scope: The RF monitor is a useful monitoring tool for seeing if the U-matic playback heads are misaligned, which is a common problem the format faces. This step allows obtaining the highest level of signal from the tape, by aligning the heads with the video track.

1. Turn on the RF scope and refer to the image below to confirm that all the settings are correct.

2. Play the tape for a bit and use the tracking and skew knobs to adjust the RF scope signal for optimal adjustments. Refer to document for more information on what the scope should look like: [RF, A Scope for Video Preservation](http://erikpiil.com/2014/07/14/rf-a-scope-for-video-preservation.html)

![AppendixE1](https://github.com/user-attachments/assets/54990f88-a4da-49b1-969d-bac420dfa25d)

*RF Signal Scope*

3. Once this is done, queue the tape for playback and begin your transfer through VRecord. 

## VHS Transfers

The lab has three playback decks for VHS transfers to be completed (refer to Appendix B for equipment legend). There are two Sony consumer level decks, the SLV-AX10 (VHS 2) and SLF-675HF (VHS1), and one professional deck, the Panasonic SVHS deck AG-7750 (SVHS). 

![AppendixE2](https://github.com/user-attachments/assets/f8c8293a-25d1-4aaa-857d-17f7d1dde5d3)

![AppendixE3](https://github.com/user-attachments/assets/9b054ac4-0786-4050-85cb-212165e3ec36)

This guide outlines the setup for transferring VHS tapes using the IS Lab video rack, covering tape inspection, format identification, and compatibility with IS Lab equipment. It specifies recommended VHS playback decks for projects and provides instructions on setting up the video rack for signal capture to the computer.

![AppendixE4](https://github.com/user-attachments/assets/fcc78e78-34be-4cb3-a819-baef65e0624e)

*Video Rack Power-On Order*

1. Turn on the three power supplies for Video Rack A and B. Find the little red buttons underneath a plastic flap, located on the left of each CyberPower deck.

![AppendixE5](https://github.com/user-attachments/assets/860f6512-04f7-4929-9382-190fd288b061)

![AppendixE6](https://github.com/user-attachments/assets/19eeb4ed-afa6-4d88-a788-15f2e7478896)

*Video Rack A and B Power Supply Buttons*

2. Turn on the two Shinybow switchers, which allow the signal running to the monitors and waveform monitor to be toggled.

![AppendixE7](https://github.com/user-attachments/assets/52bcee07-b0f2-4a3c-9c9c-30f795dc02fc)

*Two Shinybow Switchers Power Buttons*

3. Turn on the Time Base Corrector (gray piece of equipment below the Waveform monitor.)

![AppendixE8](https://github.com/user-attachments/assets/989c4d2a-ee78-46c7-9661-0ed9ecb6f6c7)

*Time Base Corrector (TBC) Power Button*

4. Turn on the Waveform Monitor (the off-white object located above the TBC). Power button is in the bottom left corner.

![AppendixE9](https://github.com/user-attachments/assets/c6c8c3ee-d65c-41d4-b32d-65f20c7c2472)

*Waveform Monitor Power Button.*

5. Turn on the Pre-digitization and Post-digitization CRT Monitors (the two TVs). Power buttons are located on the bottom left and right corners of each monitor, respectively. **Do not leave these monitors on for a prolonged period of time, unless you are transferring a tape. As soon as you are finished with your transfer, please turn these monitors off to prevent them from burning out.**

![AppendixE10](https://github.com/user-attachments/assets/9278558a-04d3-4b2a-bc7f-e9101037ae8e)

*Monitor Power Buttons*

6. Select the deck you are using and turn it on. The U-matic is shown below as number 10; the two VHS players are shown side by side; the SVHS player is shown at the bottom.)

![AppendixE11](https://github.com/user-attachments/assets/421c9921-a54d-487e-af1e-048ada118715)

*U-matic Player power button*

![AppendixE12](https://github.com/user-attachments/assets/40ba76db-e5de-4390-9c4c-27d1fa40502a)

![AppendixE13](https://github.com/user-attachments/assets/1faf938a-92c3-4ce3-b3ea-7ab76bb29f10)

*2 VHS Players power buttons*

![AppendixE14](https://github.com/user-attachments/assets/92869350-8036-4ae5-8f40-b24dd3302d00)

*SVHS Player Power Button*

Audio PatchBay Routing for three VHS decks are shown below. 

![AppendixE15](https://github.com/user-attachments/assets/f7fa14dd-663b-40dc-8a73-3e3c05e17a75)

![AppendixE16](https://github.com/user-attachments/assets/d2ef5d08-40c7-4be6-b3b9-a509a710f59a)

![AppendixE17](https://github.com/user-attachments/assets/5ace4fdf-8d15-4645-9ced-c84c08e995d4)


