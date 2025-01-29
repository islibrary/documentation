# IS Library and Media Preservation Lab: Kinetta and DaVinci Resolve documentation

*Last updated: March 5, 2024*

## Overview
The Kinetta workflow documentation provides instructions for every stage of the film scanning process, including:

1. **Pre-scan inspection:** Examining the state and quality of the film, and taking note of technical damage or deterioration which may impact the scanning process.
2. **Loading film:** Winding film onto a core and properly threading it through the machine.
3. **Configuring settings:** Setting up the Kinetta software to properly capture and stabilize image information, and adjusting exposure to get a clear image.
4. **Capture process:** Using the Kinetta software to create a scanned, digital copy of the film for long-term file storage and preservation.
5. **Post-production:** Using DaVinci Resolve for color correction and AEO-Light for adjustments to optical sound.

The Kinetta in the IS Lab supports the following film formats: **8mm, Super 8, 16mm, 35mm.**

## Resources
[Overview of the Kinetta Archival Scanner](http://www.kinetta.com/overview.html)

A general overview and introduction to the Kinetta scanner, including supported formats, examples of film scans, and device specifications.

[The Kinetta Archival Scanner](https://archive.org/details/kinetta-desktop-cine-film-scanner/mode/2up)

Virtual pamphlet including information on the Kinetta’s technical specifications, how it works, and the long-term cost efficiencies of its use in an archival setting.

[Film Format Identification Guide](https://www.archives.gov/preservation/formats/motion-picture-film-identify-formats.html)

Informational site from the National Archives on identifying basic elements of film, such as gauges, negatives and positives, and soundtracks.

[Preserving Early Motion Picture History with the Kinetta Archival Scanner](http://kinetta.com/download/files/PaperPrintf2008forWeb.pdf)

Narrative article describing the use of the Kinetta scanner in archival settings, and how it has contributed to the preservation of cinema history.

[DaVinci Resolve Templates](https://motionarray.com/browse/davinci-resolve-templates/effects/?sort_by=most-popular&utm_source=bing&utm_medium=cpc&utm_campaign=626176449&utm_content=1151189655527101&utm_term=davinci%20resolve%20effects&keyword=davinci%20resolve%20effects&ad=&matchtype=e&device=c&msclkid=2def7a94d7a7151e95a51f566037cc3a)

An online library of color correction templates and color palettes which can be downloaded and imported into DaVinci Resolve.

[Guide to A-D Strips](https://filmcare.org/ad_strips)

An informational site on using A-D strips to identify vinegar syndrome and anticipate the preservation needs of impacted film.

[Extended Introduction to AEO Light](https://www.youtube.com/watch?v=KRG3nGpnBTA)

A YouTube guide to navigating the user interface of the AEO Light software (used for optical soundtrack extraction).

## Table of Contents

[IS Library and Media Preservation Lab: Kinetta and DaVinci Resolve documentation](#is-library-and-media-preservation-lab-kinetta-and-davinci-resolve-documentation)

[Overview](#overview)

[Resources](#resources)

[Table of Contents](#table-of-contents)

[Pre-scanning inspection and film scanning prep](#pre-scanning-inspection-and-film-scanning-prep)

> [Film Inspection Bench](#film-inspection-bench)

> [Characteristics to record during inspection](#characteristics-to-record-during-inspection)

> [Issues which may complicate the scanning process](#issues-which-may-complicate-the-scanning-process)

> [Winding film onto core prior to scanning](#winding-film-onto-core-prior-to-scanning)

[Kinetta Workflow](#kinetta-workflow)

> [Cleaning the Equipment](#cleaning-the-equipment)

> > [Cleaning the Film Gate Path:](#cleaning-the-film-gate-path)

> > [Cleaning the six blue Particle Transfer Rollers (PTRs):](#cleaning-the-six-blue-particle-transfer-rollers-ptrs)

> > [Cleaning the camera](#cleaning-the-camera)

> [Loading the film](#loading-the-film)

> [Scanning Prep](#scanning-prep)

> > [Load film onto the scanner](#load-film-onto-the-scanner)

> [Prep the Software and Hardware](#prep-the-software-and-hardware)

> > [Calibration Process](#calibration-process)

> [Record](#record)

> > [Monitor recording](#monitor-recording)

> > [Save the Recording](#save-the-recording)

> > [Check Capture Quality](#check-capture-quality)

[Post-production](#post-production)

> [DaVinci Resolve Workflow](#davinci-resolve-workflow)

> > [DaVinci Resolve Overview](#davinci-resolve-overview)

> > [Setting up a new project](#setting-up-a-new-project)

> > [Stabilize the film](#stabilize-the-film)

> > [Set sizing for the image](#set-sizing-for-the-image)

> > [Color correction](#color-correction)

> > [Save the Corrected Film](#save-the-corrected-film)

> > [Trimming and Splicing Footage (Editing Basics)](#trimming-and-splicing-footage-editing-basics)

> > [Adding Subtitles and Intertitles](#adding-subtitles-and-intertitles)

> > [Exporting access copies](#exporting-access-copies)

> [AEO Light Workflow](#aeo-light-workflow)

> > [AEO Light Overview](#aeo-light-overview)

> > [A Note on Optical Sound](#a-note-on-optical-sound)

> > [Convert files into DPX using DaVinci Resolve](#convert-files-into-dpx-using-davinci-resolve)

> > [Open DPX files in AEO Light](#open-dpx-files-in-aeo-light)

> > [Adjust the Soundtrack’s Legibility](#adjust-the-soundtracks-legibility)

> > [Preparing the Soundtrack Scan](#preparing-the-soundtrack-scan)

> > [Sample the audio track](#sample-the-audio-track)

> > [Extract the audio](#extract-the-audio)

> > [Adding Soundtrack in DaVinci Resolve](#adding-soundtrack-in-davinci-resolve)

[Troubleshooting](#troubleshooting)

[Appendix A: Film Format Identification](#appendix-a-film-format-identification)

[Appendix B: Key Commands for Resolve](#appendix-b-key-commands-for-resolve)

> [File](#file)

> [Timeline Navigation](#timeline-navigation)

> [Marking](#marking)

> [Playback](#playback)

> [Editing](#editing)

> [Effects](#effects)

[Appendix C: Identifying Edge Codes](#appendix-c-identifying-edge-codes)

> [8mm](#8mm)

> [16mm](#16mm)

[Appendix D: Information on Codecs](#appendix-d-information-on-codecs)

[Appendix E: Film Inspection Sheet](#appendix-e-film-inspection-sheet)

## Pre-scanning inspection and film scanning prep

Film must be inspected **before** scanning with the Kinetta. The condition of the film must be verified in order to consider the film safe to scan. This step prevents damage to the film and to the machine. Any necessary repairs and cleaning must also be performed before scanning the film. 

Film inspection provides useful information (metadata) about a film, such as film gauge, optical soundtrack, edge code, year of production, discoloration/deterioration, and unwanted artifacts. For help identifying the different formats (or gauges) of film, [refer to Appendix A](#appendix-a-film-format-identification). For additional film inspection guidelines, [refer to this PDF document](https://drive.google.com/file/d/1UcEQHfEAcSOon16FReVxUpHngD2v-M1S/view?pli=1).

Please note that if a given film is on a reel, **it must be wound onto a core** for scanning.

### Film Inspection Bench

The film bench in the IS Lab provides a dedicated space for film inspection, splicing, and recording various characteristics of film on an inspection sheet. The following tools are available for use at the inspection bench:

1. **Powder-free gloves:** to cover hands during inspection.
2. **Magnifying glass:** for close inspection of the image content and edge code.
3. **Rewind bench:** for efficiently winding through a film, winding it onto a core, cleaning film, finding and repairing broken or damaged segments, and attaching leader. 
4. **Split reels:** for loading film onto the rewind bench, located directly underneath the inspection bench. A split reel consists of two flat discs that “split” apart to accommodate the core. 
> * The lab has 16mm and 35mm split reels available.
> * 8mm film may be put onto a 16mm split reel.
5. **Cores:** a plastic cylinder used to store 35mm, 16mm, 70mm, and Super 8 film and can be found in 4", 3", 2", and 1" sizes.
6. **X-Acto Knife:** For trimming or splitting a film into segments.
7. **Tape:** For joining two segments in a splice.
8. **Guillotine:** for taping and sealing a splice between two segments of film.
9. **Edge code binders:** containing pages of symbols and their corresponding year(s) of production. Refer to [Appendix C](#appendix-c-identifying-edge-codes) for more information about edge codes.
10. **Film inspection sheet:** Fill out an inspection sheet with format characteristics and condition notes as the inspection is performed. See [Appendix E](#appendix-e-film-inspection-sheet) for IS Media Lab Film Inspection Sheet.

### Characteristics to record during inspection:

* **Type of film stock:** Kodachrome or Ektachrome. Visible on the edge of the film with a magnifying glass. 
* Damage to the edges or perforations.
* Presence of soundtracks along the edge of the film. 
* Identify the **base side** and the **emulsion side**. 
> * The **base side** will appear shinier than the emulsion. The surface will also look completely flat because it technically consists of a clear, plastic strip.
> * The **emulsion side** consists of a pigmented, chemical coating with the image information. It is duller than the base. If examined from the right angle the base can be identified by the raised texture of the pigment on the film. 
> * To identify which side is which on a given film, hold the film so that it catches the light. 
> * When using the Kinetta, the film should be **scanned with the emulsion side facing the camera.**
> * Scratches on the emulsion side (will appear white during scan).
> * Scratches on the base side (will appear black during scan).
* Extreme changes in brightness or film stock changes. 
* Weak splices. Bend and twist the splice to ensure its strength. Resplice with a fresh piece of the tape and the guillotine, as needed.
> * For brittle, older cement splices, add a tape splice on top to prevent snapping during transfer.
* **Edge code:** a combination of shapes or symbols indicating the year of the film’s production. Use the binders of Eastman-Kodak edge codes in the Lab to determine the film’s year of production.

### Issues which may complicate the scanning process:

* **Vinegar syndrome** is a symptom of aging acetate film, caused by the breakdown of the film's plastic base. Over time, acetate film releases a vapor which accelerates its own deterioration. Symptoms of vinegar syndrome include:
> * A strong or unpleasant vinegar-like odor
> * Shrinkage
> * Buckling
> * Use A-D strips, located in the left-hand drawer of the film bench, to determine the severity of vinegar syndrome. Refer to this site for help using A-D strips, determining the severity of vinegar syndrome for a film, and next steps for preservation.
* Warping.
* Shrunken film.
* Brittle texture.

**Important:** Please be aware that choosing to scan a film afflicted with these issues could result in significant and irreversible damage to said film. It is important to understand the preservation risks associated with degrading media.

Attach enough leader to allow for two turns around a core without the film’s image entering the scanner gate (about 6 feet). Attach the leader to the head and tail of the film. Refer to the winding instructions below.

### Winding film onto core prior to scanning

* **For examination on a rewind bench,** films must be wound onto a reel or core.
* **For scanning,** films must be wound onto a core.
* **For storage,** films are wound onto a core.
* **For exhibition and projection,** films on a core must be put onto a split-reel.

1. To wind a film onto a core, select the split reel (two flat discs that “split” apart) and the core that matches the film gauge. 
2. Screw shut the split reel with the cored film and mount it on the take-up side (the side with the film core).
3. If the leader is too short or damaged, it is necessary to add enough leader to wrap around the core three times. 
4. In transferring a film from a reel to a core, keep the film at an even tension. Be sure that the film edges stay aligned and that none protrude beyond the flat plane of the roll.

**Please note:** a correctly coiled film roll should be wound tightly enough so that it looks like a solid disc with even sides (as seen in the image below):

![film on core](https://github.com/user-attachments/assets/c4f8157b-611f-4f81-beab-fdbd98cfffd3)

## Kinetta Workflow

### Cleaning the Equipment
The Kinetta’s film gate path, the camera lens, and the six blue Particle Transfer Rollers (PTRs) all need to be cleaned before each film transfer. Cleaning supplies, like foam cleaning swabs and isopropyl alcohol, can be found in the gray cabinet labeled “Need Something?” located to the left of the Kinetta.

<img src="https://github.com/user-attachments/assets/c90c89dd-c059-4af1-95a8-4ecc73cefb0f" alt="foam cleaning swaps" width="150">

<img src="https://github.com/user-attachments/assets/6330fb71-4402-4238-99dc-7bbfccd163da" alt="isopropyl alcohol" width="150">

<img src="https://github.com/user-attachments/assets/74133897-f50e-44ff-905d-ec370505d0f3" alt="gloves" width="200">

#### Cleaning the Film Gate Path:
1. Unscrew the black film gate and lift it up to remove it from the scanner.

![kinetta picture](https://github.com/user-attachments/assets/005cc819-41e7-4fcb-b3eb-8d3a0895a7b3)

*The film gate must be lifted upward and removed from the Kinetta to be cleaned.*

2. To clean the film gate path, gently wipe with a foam swab soaked in isopropyl alcohol on the removable section of the film gate.
3. To clean the lightbox behind the film gate, use a dry foam swab to wipe away residual dust or debris from the small, glass window in the center of the gate. This ensures dust and debris will not feature in the scan as unwanted artifacts.

![kinetta picture 2](https://github.com/user-attachments/assets/e192c040-25a4-43f9-b62e-dba0c242b4d8)

*Film Path on the Removable Film Gate*

5. Screw the gate back into place when finished.

#### Cleaning the six blue Particle Transfer Rollers (PTRs):

1. Using a foam swab soaked with 99% isopropyl alcohol, spin the black piece with a finger to clean the rubber surface of the roller.

![kinetta 3](https://github.com/user-attachments/assets/c6fa3100-f4e3-4901-8f3f-a857cb536342)

*Clean blue PTRs using a swab soaked in alcohol.*

2. Please note that the capstan roller (seen in the image below located to the immediate right side of the film gate) **does not manually spin.** Open the Kinetta software and press the forward inching knob button to spin the capstan roller while holding the wet swab in place.

![kinetta 4](https://github.com/user-attachments/assets/2e288900-592d-4829-a8ca-9ef5ab8c2507)

*Capstan Roller*

<img src="https://github.com/user-attachments/assets/a66d5f1c-9ae6-4d1e-b1de-329599b58789" alt="kinetta screenshot" height="150">

*Kinetta software shortcut*

![kinettta screenshot](https://github.com/user-attachments/assets/ef980389-b52e-4389-9d6b-8453d7a9856e)

*Inching knobs*

#### Cleaning the camera
1. Remove the lens cap from the camera and set it on the table. Important note: the camera lens must be recovered after scanning.
2. Using a clean swab WITHOUT alcohol, or a microfiber cloth, carefully clean the camera's lens. Gentle, circular motions are recommended.

### Loading the film
1. **Wind film onto a core:** Once the leader has been attached, wind the film onto the proper core for the Kinetta.
> * For a 16mm/35mm film, wind the film onto an archival film core.
> * For 8mm film, put a 16mm split reel around a Kinetta 8mm reel. Please note that there are only two Kinetta-compatible 8mm reels in the lab. Alternatively, an 8mm film may be wound onto a 16mm core, which will sit flatter on the scanner.

![16_split_reel](https://github.com/user-attachments/assets/34bd033e-d10f-4f74-8d21-e7e1708a3b46)

![35_split_reel](https://github.com/user-attachments/assets/fb6a2054-a89a-4114-812c-6c2d74c0024e)

![kinetta_core](https://github.com/user-attachments/assets/ebd0a515-5e5e-4577-a7a1-f7065de37bdd)

*Different film gauges correspond to differently sized cores. Top to bottom: 16mm split reel and core, 35mm split reel and core, and a 16mm core on the Kinetta.*

![8_split_reel](https://github.com/user-attachments/assets/000bcf8d-d453-4f2c-8f32-d145710f0b15)

*8mm/Super8 split reel*

### Scanning Prep

1. **Power on the Kinetta Equipment:**
> * Power on the Kinetta computer tower, located underneath the Kinetta (power button in on the front right corner). Sign in with the UCLA Kinetta1 user credentials (located on monitor). 
> * Flick the red power switch located on the central back panel of the scanner and ensure that “I” is pressed down. Please note that the power switch **will remain illuminated when the Kinetta is off.**

![kinetta_power](https://github.com/user-attachments/assets/b92a69ba-5e1d-44bc-8054-7e765969abcf)

*Power Button on the back of the Kinetta, circled in blue.*

2. **Open the Kinetta software:**
> * Double click the Kinetta Software shortcut on the desktop (shown left).
> > * Click ‘Yes’ on the pop-up window asking whether to let the application make changes to the computer.
> > * Click ‘OK’ on the pop-up window asking to reload a previous calibration.

<img src="https://github.com/user-attachments/assets/a66d5f1c-9ae6-4d1e-b1de-329599b58789" alt="kinetta screenshot" height="150">
<img src="https://github.com/user-attachments/assets/8a07f220-2b5d-4646-ac17-f04b8615c8e6" alt="kinetta scanner ok window" height="150">

*(Left) Kinetta Shortcut Icon (Right) Calibration Pop-Up Window*

> * The Controls Panel and the Second Panel will open (this may require opening the Kinetta software a few times). 
> > * Do not change the configuration of the panels on the monitors.

![kinetta_desk](https://github.com/user-attachments/assets/5b2f1c3d-ded4-4818-83cd-f033e4d5d724)

*To toggle between the monitors, slide the cursor over the top left corner of the right monitor, and the top right corner of the left monitor. This process requires practice and patience.*

#### Load film onto the scanner

a. Thread the film through the blue PTR rollers on the Kinetta, using the small black arrow labels on the machine as a guide.
b. Make sure the film is flush against the gate, and under the metal bar. 
c. Identify the emulsion side (dull side) of the film. For assistance, refer to the image below. Ensure that the emulsion side is facing the camera. This step is very important, as it ensures the most accurate transfer of the image information printed on the film.


### Prep the Software and Hardware

#### Calibration Process

### Record

#### Monitor recording

#### Save the Recording

#### Check Capture Quality

## Post-production

### DaVinci Resolve Workflow

#### DaVinci Resolve Overview 

#### Setting up a new project

#### Stabilize the film

#### Set sizing for the image

#### Color correction

#### Save the Corrected Film

#### Trimming and Splicing Footage (Editing Basics)

#### Adding Subtitles and Intertitles

#### Exporting access copies

### AEO Light Workflow

#### AEO Light Overview

#### A Note on Optical Sound

#### Convert files into DPX using DaVinci Resolve

#### Open DPX files in AEO Light

#### Adjust the Soundtrack’s Legibility

#### Preparing the Soundtrack Scan

#### Sample the audio track 

#### Extract the Audio

#### Adding Soundtrack in DaVinci Resolve

## Troubleshooting

## Appendix A: Film Format Identification

## Appendix B: Key Commands for Resolve 

### File

### Timeline Navigation

### Marking

### Playback

### Editing

### Effects

## Appendix C: Identifying Edge Codes

### 8mm

### 16mm

## Appendix D: Information on Codecs

## Appendix E: Film Inspection Sheet
