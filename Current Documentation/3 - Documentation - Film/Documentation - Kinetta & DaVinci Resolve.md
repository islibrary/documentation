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

![LoadFilm1](https://github.com/user-attachments/assets/ac6e90e8-0924-4ae7-b702-cb1ffb91c3b5)

*Diagram differentiating the emulsion and base sides of film.*

a. The film may be loaded with the sprockets facing any direction. There is no specific requirement for how the film should be oriented when loading. Add the correct film gauge core to the opposite platter. For 8mm or Super8, use the special “Amphex” Kinetta-compatible core. Be sure to mirror the thread pattern of the film on both sides of the scanner.

![LoadFilm2](https://github.com/user-attachments/assets/747bc4e9-7e4d-4df5-87e2-a16710a29023)

*Examples of how to thread film based on the tandem switch configuration. Numbers under tension control will fluctuate; these are the numbers that were displayed during the screenshot.*

A. Set the tension:
a. Setting the tension is an important step which ensures the film is secure and properly scanned by the machine. Flip the Tandem switches on the Kinetta.
b. Ensure that the arrows in the Tension Control section are facing **the same direction** as the threaded film. See the images above for reference.

![LoadFilm3](https://github.com/user-attachments/assets/8706a57c-6380-4d65-806e-c6f92d8a42e8)

*Tandem Switches*

### Prep the Software and Hardware

![LoadFilm4](https://github.com/user-attachments/assets/91293be2-dafb-4e55-add1-4e85f5255aea)

*The Kinetta software’s graphical user interface (GUI).*

1. **Check the software settings**:
   > a. Film Format: Set to the correct gauge of the film.
   > 
   > b. Film Speed: This is the frames per second (FPS) for the motor, not the file. The recording file generated will have an agnostic frame rate, and the FPS will be set later in DaVinci Resolve.
   > > i. FPS may be slowed for films with significant damage; it is not recommended to go over 18 fps.

2. **Apply tension to the film**:
  > a. Once the film is threaded properly and the tenison controls are set to apply force in the correct direction, press the “load” button on the Kinetta software. This will add force to the platters, keeping the film tense, so that the scanner can shuttle the film with the control of the software. Force should be applied in the same direction that the film was loaded.
  > 
  > b. If the load is successful, the scanner will gather film tension and the “Load” button will change to read “Unload” in the software.
  >
  > c. If the load is unsuccessful, the scanner will loosen film on platters and the “Load” button will still read “Load.”
  >
  > d. If necessary, attempt re-loading by checking that take-up directions are correct and repeating the previous steps. If it still does     not load, restart the Kinetta software.

3. **Frame the camera lens for the film**:
  > a. Increase light levels by pressing the ‘White’ button. Raise the white light slider up until the preview monitor changes from dark to light.

 ![LoadFilm5](https://github.com/user-attachments/assets/88631070-d9dd-4f6a-b866-de2b067064f0)

 *Light Level Controls in the Kinetta software*

 4. **Center the image**:
   > a. Using the green inching knobs, circled below, vertically center the image in the left monitor of the Kinetta Station.

   ![LoadFilm6](https://github.com/user-attachments/assets/c1403e81-cece-4ee3-ae2b-be2b1dce7cec)

  *Use the inching knobs to center the image and precisely advance through the film.*

  5. **Adjust the camera**:
     > a. Turn the black screw behind the camera to adjust the focus. This will move the camera further or closer from the film. Do not attempt to change focus using the lens.
     >
     > b. Turn the silver knob, shown below and to the right, to center the image. This will move the camera to the right or left.

![LoadFilm7](https://github.com/user-attachments/assets/12c195e4-5bb8-418d-8b57-989ece9b30b5)

![LoadFilm8](https://github.com/user-attachments/assets/e06ac125-c757-453a-9fc8-7f190580f1dc)

*Use the lens carriage knob, left, to adjust focus. Use the silver knob, right, to center the image.*

#### Calibration Process

If the film gate has been changed or the camera has moved, please follow the steps listed below: 

1. Remove the film from the gate (Please place it somewhere non-obstructive on the scanner so it does not get lost).
2. Unscrew the gate and remove it from the sensor carriage.
3. Hit the “calibrate” button on the Kinetta software.
4. A message will pop up that says “please ensure the gate is clean and empty.” Wipe the sensor with a dry foam swab to ensure that dust or smudges will not feature in the film scan. Do not wipe the sensor with cloth or fingers, as these methods may leave residue.
5. Press “Ok” in the window.
6. Calibration actions will initiate after a few seconds of visual inactivity. Calibration may take several minutes.
7. If calibration is successful, the button will change from “Cal Off” to “Cal On”. Waveforms will form a straight, white line, and the preview monitor will appear uniformly gray.
8. If calibration is unsuccessful, the preview monitor may display quadrants, gradients, non-gray color, an error message reading “specified argument was out of the range of valid values,” or the monitor will display film with incorrect values.
> a. Select “Ok” to recalibrate and retry the calibration steps.
>
> b. If re-calibration is also unsuccessful, turn off the scanner and turn it on again. Then reboot the software.
>
> c. Replace the film gate on the sensor carriage and rethread film on the scanner.
>
> d. Using the inching knobs, located above the red stop button, to advance the film to an image and then stop.
>
> e. Scroll with the mouse wheel to zoom in and out of the image. Focus on the grain of the film rather than the image. Do not use the film perforations as a reference for focus.
> > i. Reset the zoom by clicking the mouse wheel.

![Calibration1](https://github.com/user-attachments/assets/463f4987-f97a-42e6-859a-c6b86acfde5d)

*An image in focus. The grain is visible and should give your image a sandy texture.*

![Calibration2](https://github.com/user-attachments/assets/ac7c1285-6c55-4fda-83d3-f37c07903b97)

*An image out of focus.*

> f. Advance the film in the direction of your scan to make any focus adjustments.

 9. **Frame the image**:
> a. In the center row of the software window, click the **White** button in the Light Source panel on the far left.
>
> b. Click the Preview button so that it reads Preview On.
>
> c. Use the crawl arrows (pictured below) to make focus adjustments, as needed.
>
> d. Horizontally center the image, as much as possible, retaining full view of the black margins.
>
> e. Aspire to have two entire perforations visible. One sprocket is still permissible.

10. **Set the Reference Region**:
> a. Specify the reference region by simultaneously holding down CTRL and the LEFT mouse button. Drag the cursor over the perforations to create a column, as shown on the following page. The column may be narrow. **Ensure the column does not touch nor exceed** the rounded edges. This ensures the program will be able to easily stabilize the image.

![Calibration3](https://github.com/user-attachments/assets/b4ae2e5e-1353-490f-a0f5-cbd9c429f754)

*Ensure that the reference region (circled) neither touches nor exceeds the rounded corners of the perforations.*

> b. This process may take a couple of tries. Some tips: Release the CTRL button in between tries, hold down the mouse button, and make sure you are moving the mouse **horizontally, left to right**.
>
> c. For film with two rows of perforations, the reference region may be set on either side of the film.
>
> d. For horizontal stabilization, draw the region from the middle of the perforation to the outer edge of the film.
>
> e. On the left side of the monitor, a black line representing the reference region will appear (shown below). The line should be solid through the middle, as shown in the image affixed here:

![Calibration4](https://github.com/user-attachments/assets/4a61f123-4aec-4b81-a96c-412c05575bfb)

*How the lower left viewing window will look once the reference region is set.*

> f. Select the “Set Reference Region” button while the film is still and centered in the gate. The button will say “Reset Reference Region.”
>
> g. Select ‘Stabilize.’
>
> h. Continue advancing the film to check for stabilization issues.
>
> i. If the image is rolling vertically in the preview monitor, ensure that the correct film format and FPS are both selected. Check the tension controls, and unload and load again if the problem persists. Ensure that the film is flush to the gate as it passes through.

11. **Set Exposure Settings**:
> a. Select the correct settings in the “Film Type” window:

![Calibration5](https://github.com/user-attachments/assets/7b635f0f-1b71-4d59-ab00-947560279b07)

*Film Type Window*

> b. Turn the Zebras on in the top bar of the window (under “Overlays”). This is a useful (and optional) tool that will display the overexposed areas of the image.

![Calibration6](https://github.com/user-attachments/assets/94bd89f2-ade7-465e-81e5-223a4f0790f2)

> c. Select an exposure preset to get initial settings (Color Controls>Presets). These presets can be thought of as a general guide, and should not be used as the only indication of the image’s final exposure.

![Calibration7](https://github.com/user-attachments/assets/841b7490-4205-4b49-96e9-25ebfdfe955e)

*How to Navigate to Color Presets*

> d. During playback, monitor the waveform to confirm that the highlights are not clipping (loss of information). Keep the waveform in between the top and bottom dashed lines, as shown in the image below. **Only the bottom waveform should be used as a reference for color correction**.

![Calibration8](https://github.com/user-attachments/assets/929f68e6-057c-4b0c-bcca-dd953227ccc5)

*Example of a good waveform. This waveform is keeping the highlights and shadows in between the top and bottom dashed lines.*

![Calibration9](https://github.com/user-attachments/assets/f04caa55-b52b-4649-814a-62b0a1861515)

*Example of a bad waveform. This waveform is clipping the highlights and crushing the blacks. The terms ‘clipping’ and ‘crushing’ refer to the loss of information.*

> e. Use the Color Control and Curve Mix bars to set the final exposure. (Generally, we do not use the Light Source bars). 
> > i. Lift controls shadows.
> >
> > ii. Gamma controls the grays or “midtones.”
> >
> > iii. Gain controls the highlights.
> >
> > iv. Curve Mix: digital controls that offer fine-tuning adjustments. These tools are highly recommended for achieving the look of a professional restoration.

> f. Adjust Lift, Gamma, and Gain to achieve a more even spread of the waveform between the top and bottom dotted lines. This ensures an accurate and comprehensive capture of the image’s information.

12. **Save the Color Settings**:
> a. It is not uncommon for the Kinetta software to crash, especially for longer films. To mitigate the trouble of re-dialing the final exposure settings, the color settings may be saved as a template. See part b.
>
> b. Navigate to Color Controls and select Save Mem A, B, C, or D. Any one of these options will do.
>
> c. If you need to restart the software for any reason, navigate to the Color Controls, then Load Mem A,B, C, or D, depending on the option selected in the previous step. **Please note**: If the Kinetta crashes, or the software  must be closed, **set all other settings before reloading the color settings**. Otherwise, the Kinetta will freeze.

### Record

1. In the Kinetta software control panel, click “New Movie.”
2. In the file explorer, navigate to the **Kinetta Raid (K:)**
3. Navigate to the folder for the appropriate class, or create a new folder as needed.
> a. In that folder, create another folder labeled by name or group.
>
> b. Name the file, then specify the save location with a single click and press.
4. Cue the film to the beginning.
> a. Using the larger green arrows to the right and left of the red stop sign, advance or rewind to the beginning of the film, or the point at which the recording should begin.
>
> b. **Important note**: It is recommended to include at least 3 seconds of leader or extra footage prior to the first image in the final recording. In some cases, is it recommended to include even more leader to avoid Bayer Shift, a type of color distortion impacting the first few frames of a film. 
5. Ensure that “Preview Off” is set, as in the image below.
6. Click “Start Record”, then click the green arrow to the right of the stop sign to play the film. **Please note: The film must be stationary before the recording starts.**

![Record2 ](https://github.com/user-attachments/assets/7557108e-9d51-4cbe-9077-451e5ec92d94)

*How the Kinetta software should look during a scan.*

7. If the film contains segments at different photographic extremes (e.g. high exposure/low exposure) or in different formats (e.g. b+w/color), it’s recommended to record once with settings for one extreme, the next with settings for the other. For reels containing both black and white and color, consider making separate recordings for each, to provide time to adjust the settings for both. The approach chosen depends on individual preferences and time constraints.

![Record3](https://github.com/user-attachments/assets/7c7f745b-b553-4edf-9008-843670cef6f3)

*Example of an image that is properly centered for the lighting process.*

8. Important note: Always rewind the film for a couple of seconds before restarting the capture, to ensure that the entire film will be recorded.

#### Monitor recording

1. Watch the entire capture to check for capture issues.
2. Stop the recording if unfixable issues such as the following arise:
> a. Film loses stabilization.
>
> b. Film image jumps out of the preview monitor frame.
>
> c. Image goes out of focus.
3. Capture in parts if continuous capture seems impossible.
4. Stop capture between clips if recording in parts.
5. Always rewind the film a couple of seconds before restarting capture to be sure that the entire film has been recorded.
6. As the film nears its end, please be aware that **THE RECORDING MUST BE STOPPED BEFORE RUNNING OUT OF LEADER. Otherwise, the film will fly off of the Kinetta, risking potential damage to the film and to the machine.**
7. Press the red Stop button.
8. Select the ‘Stop Record’ button to end the recording.
9. Ensure that the blue PTRs stop.

#### Save the Recording

1. Move the recordings to the server in the following step:
2. Move the folder created in the Kinetta (K:) drive to the IS Media Lab’s synology server: navigate to Network > **ISmediaLAB** > class folder.

![Record4](https://github.com/user-attachments/assets/9cd26d36-ee05-4ab3-aaa6-fafa9baf34dc)

*Network in Finder Window*

3. This folder will now be accessible at any of the other workstations in the lab. The other two stations with DaVinci are the Video Editing Station and the Video Transfer Station (this version of DaVinci cannot support the 4K resolution needed for 16mm).

#### Check Capture Quality

1. Navigate to the saved file for the film scan.
> a. Make sure Quicktime 7 and [Cineform Decoder](http://cineform.com/gopro-cineform-decoder "Cineform Decoder") are both installed on the computer prior to playback.

2. Scrub through the video and audio files to ensure smooth playback.Revisit the scanning process if the following problems arise:
> a. Capture encompasses film from head leader to tail leader.
>
> b. If scanning clips, make sure the film has buffers on either end of a clip.

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
