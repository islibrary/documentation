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

This section will:
1. Provide instructions on how to color correct a film scan using Resolve.
2. Explain how to extract optical sound from a film soundtrack using AEO Light.

### DaVinci Resolve Workflow

DaVinci Resolve is a film editing software with a vast toolkit for all video editing needs. After scanning a film with the Kinetta, Resolve may be used to trim and splice the footage, depending on the presence of unwanted artifacts, like dust or damaged frames. It can also be used to improve colors, edit soundtracks, layer audio, apply effects, add subtitles or intertitles, and much more.

Resolve provides robust options for color correction, which is used by archivists to create a “re-mastered” version of the raw image with adjustments to brightness, contrast, saturation, and tint. These changes can be applied to individual scenes in the film or across the film in its entirety, depending on the scope and intention of the project. Color correction is a necessary step during the creation of a preservation master, a “remastered” version of a film with improved color palettes. Color correction creates an image that is more professional-looking, appealing to the eye, and appropriate for screening and sharing purposes.

#### DaVinci Resolve Overview 

This software workflow will cover the following:
1. How to import a scanned film and set up a project for basic editing (e.g. trimming, splicing, raising or lowering audio levels).
2. How to do basic color correction (“one light”) for the entirety of a film. 
3. How to create dynamic color correction which varies scene-by-scene.

#### Setting up a new project

1. Turn on the Mac desktop at the Video Editing Station. The tower is located on the floor, to the bottom right of the monitor. Power button is located toward the back of the tower, on the top face, in the center.
2. Create a folder on the desktop with a unique name, to which the finished file will be exported. **Please do not work from the server nor the external drive**.
3. Double-click on the desktop shortcut for DaVinci Resolve:

![PostPro1](https://github.com/user-attachments/assets/c6c3f3a3-aee8-48d9-a4aa-d00dd5766af9)

*Davinci Resolve Desktop Shortcut*

4. Click the “New Project” button, located at the bottom of the window. Give the project a name, then click Create.
5. Click the Edit tab, located at the bottom of the screen.

![PostPro2](https://github.com/user-attachments/assets/ef37e3a4-2a22-448e-9104-e83244b978bc)

*Edit Tab in Davinci Resolve*

6. On the left side of the screen, right click anywhere inside of the Master Bin window. Click New Bin, which creates a new folder to import files. Rename this file. Note: this process may be repeated multiple times to create more files and help organize the project.
7. Double click on the New Bin just created. In the top left corner, click File, then click ‘Import Media.’
8. Navigate to the scanned film, then single click to select it. Then click Open.

![PostPro3](https://github.com/user-attachments/assets/94256cdb-4e5c-4a60-b993-1027df14144a)

*File>Import Media in Davinci Resolve*

9. If a window appears asking to Change Project Frame Rate, select Change. 
10. In the program workspace, right click on the imported media to bring up a side menu of options. In the menu, select Create New Timeline Using Selected Clips

![PostPro4](https://github.com/user-attachments/assets/cd3a3c66-87b8-4b1f-a61c-c3656adade0c)

*Create New Timeline Using Selected Clips*

11. In the new window which appears, enter the Timeline Name and click Create.

![PostPro5](https://github.com/user-attachments/assets/d3f94ffa-591b-4a4b-a17b-44b7640ffbee)

*Create New Timeline*

12. The media should appear in two places: the media player in the center of the program, and the timeline at the bottom of the frame. The timeline can be thought of as an editing ‘workspace,’ to perform basic functions such as trimming, splicing, and adjusting audio levels.
13. Scroll through the timeline by dragging the orange playhead, or by pressing the spacebar to play.

#### Stabilize the film

1. Select the Color tab, located at the bottom of the program.

![PostPro6](https://github.com/user-attachments/assets/0223a058-8b73-42f5-b410-101a9d454f89)

*Color Tab in Davinci Resolve*

2. Open Stabilize with the Crosshair icon.
3. Click the Shaky Camera icon, shown below, then in the triple-dot menu, navigate to Classic Stabilizer.

![PostPro7](https://github.com/user-attachments/assets/6a4ad8b9-ecb1-4b45-98ff-78127cc16be6)

*Navigate to Classic Stabilizer under the triple-dot menu.*

4. In the bottom right corner, Make sure it is set to Cloud Tracker.
5. **Uncheck** Zoom and Rotate.
6. In the bottom left corner, click Interactive Mode, then click the square icon to the right. Click and drag the mouse to draw a rectangle over the entire image.
7. Click the trashcan to erase all the crosshairs on the frame. Redraw the rectangle so that it covers the sprockets holes, then re-click the rectangle icon. Set the point icon (this is the icon just to the right of the rectangle)
8. Run the film forward. If it stops, redraw the rectangle and run forward again.
9. Once it has run through the whole film, click Stabilize.

![PostPro8](https://github.com/user-attachments/assets/6a54387d-69f1-4ac5-99a3-3f0dd1cb4565)

*Click Stabilize*

#### Set sizing for the image

1. To preserve the highest resolution and aspect ratio of the scanned image, proceed with the next step.
2. Go to File, then Project Settings. 

![PostPro9](https://github.com/user-attachments/assets/cffaedf1-b81d-4b13-9f8b-57b8bffcef32)

*File>Project Settings*

3. Set the Timeline Resolution to a resolution that corresponds to the media. **This will depend on the aspect ratio of the film**. For example, this Dole Commercial is 35mm with a 4x3 (1.33) aspect ratio. *This step may require a bit of trial and error to set properly. It’s alright to set this incorrectly and then come back and change it*.
4. For this particular film scan, a Timeline Resolution of 3840x2880 will provide the appropriate cropping for the image. Because there is no standard Timeline Resolution in Resolve for 3840x2880, a custom resolution must be set. Click the Timeline Resolution dropdown menu and choose Custom, then enter the resolution in the boxes below.

![PostPro10](https://github.com/user-attachments/assets/67807cde-202b-429e-9753-cea3fef720cd)

*Timeline Format with a dropdown menu of options for the Timeline resolution.*

![PostPro11](https://github.com/user-attachments/assets/318437da-902b-4f45-962c-9eac243951fb)

*Setting a custom resolution.*

**NOTE: Below is a list of 4K resolutions for common film aspect ratios:**
* **3840 x 2880 – 1.33 (4x3)** 
* **3840 x 2304 – 1.66 (Super 16mm)**
* **3840 x 2160 – 1.77 (16x9)**
* **3840 x 2076 – 1.85 (Flat)**
* **3840 x 1634 – 2.35 (Cinemascope)**

5. If the resolutions above result in a frame that’s too big or too small, additional resolutions for these and other aspect ratios can be found at [this site](https://www.unravel.com.au/aspect-ratio-cheat-sheet "Aspect Ratio Cheat Sheet").
6. In Project Settings, navigate to Image Scaling in the menu on the left. Under Input Scaling, click the dropdown menu and select Center crop with no resizing.

![PostPro12](https://github.com/user-attachments/assets/d3e97473-7606-4138-979e-c4dfb413fa49)

*Image Scaling under Project Settings*

7. Choosing this setting will ensure the image is not stretched and maintains its scanned resolution.
8. Then click Save.
9. Check the image in the viewer on the right. If the image is significantly out of proportion, adjust the Timeline Resolution to reflect the appropriate resolution back in project settings (see the note on the previous page for other resolutions). If the image is slightly off but close to correct, then proceed to the next step. **NOTE: When working with multiple film scans that have different formats or were scanned on separate occasions, it is beneficial to create separate projects for each format or scan session, since the timeline resolution set in Project Settings will be universal for all timelines within a Resolve project. However, if working with multiple rolls of the same format, which were scanned without any zoom adjustments on the scanner, it is possible to include them all on the same timeline**.
10. Fine tune sizing of the image. Click on the Inspector button on the top right to reveal Transform settings.

![PostPro13](https://github.com/user-attachments/assets/e64d7cf4-e27f-4816-be7f-f6b1ffc47f33)

*Fine tune sizing of the image*

11. In Transform settings, adjust Zoom and X and Y position parameters to crop out the frame edge. NOTE: Hold down Option on the keyboard while clicking and dragging these parameters to make very minor adjustments.

![PostPro14](https://github.com/user-attachments/assets/6e20ccd2-7d9f-400c-8268-63de42c68114)

*Transform Settings in Davinci Resolve*

#### Color correction

1. Once the sizing of the image is satisfactory, click on the Color Tab by clicking the Color button on the bottom of the screen.

![PostPro15](https://github.com/user-attachments/assets/12324bd4-ba0c-4af3-b6a7-736134eb5b88)

*Color Tab in Davinci Resolve*

2. Before beginning color correction, it is important to ensure that the appropriate scopes are made visible for the monitoring process. Click the Scopes button on the lower right side of the screen.

![PostPro16](https://github.com/user-attachments/assets/2dad3cc1-3844-4447-b3a5-32885306f376)

*Scopes Button*

3. Ensure that the ‘Parade’ scope is visible. If this scope is not already selected, click the scope dropdown menu and select Parade.

![PostPro17](https://github.com/user-attachments/assets/f9741435-a2db-4840-8443-6f1d9d5f1bf7)

*Parade Scope under Waveform in Davinci Resolve.*

![PostPro18](https://github.com/user-attachments/assets/ee9ee305-0545-481c-a686-a0ec247c8db6)

*Parade Waveform Scope.*

4. The color correction process can now begin. A ‘one light’ correction is a simple overall correction for the entire roll of film, rather than an in-depth, shot-by-shot correction. For the one light color correction, the only settings to adjust are the ‘Primaries - Color Wheels’ controls–Lift, Gamma, and Gain, which are located on the lower left portion of the screen.

![PostPro19](https://github.com/user-attachments/assets/053801b7-e6ac-4136-a3c2-3fb5e88ec3a5)

*Color Wheels in Davinci Resolve.*

5. Each of these controls has a color wheel and a scroll bar underneath. The color wheels adjust color balance, and scroll wheels adjust exposure. Lift, Gamma, and Gain adjust the shadows, midtones, and highlights respectively. Offset, which is a universal adjustment, can be ignored.
6. Before making any adjustments, search for a film frame that contains a wide range of exposure. Scroll through the film roll using the bar underneath the image.
7. An ideal frame will have highlights at their brightest and shadows at their darkest in a single image. For example, a good looking frame to start with in this Dole commercial might be this one, which contains both bright highlights and dark shadows:

![PostPro20](https://github.com/user-attachments/assets/7322132f-dfbd-45e6-8771-dbfe02ccc83e)

*Example of a frame that contains both bright highlights and dark shadows.*

8. Now make an adjustment to **exposure** using the Gain, and Lift scroll bars (not the color wheels). For guidance on this adjustment consult the scopes. The information on the scopes should be close to the top and bottom of the scopes window, but nothing in the Red, Green or Blue channels should be ‘clipped’ (over the top or bottom edges of the scopes).
> a. **NOTE: The top of the Parade scopes represents the brightest whites, whereas the bottom of the Parade scopes represent the darkest blacks. Any information above the top or below the bottom of the scopes will be clipped and lost.**
9. For example, in the image below, the Gain is brought down slightly to unclip the highlights. The Lift is brought down as well, to make the blacks richer. See example images on the following page.

**Before:**

![PostPro21](https://github.com/user-attachments/assets/6fc50787-0a04-4b5e-a87e-7f8049638f0a)

![PostPro22](https://github.com/user-attachments/assets/683612b3-dbeb-4b4d-b0ae-bbe79212551e)

**After:**

![PostPro23](https://github.com/user-attachments/assets/c93c6dad-b45a-4659-94aa-8db3332a5383)

![PostPro24](https://github.com/user-attachments/assets/99e31637-d16b-458b-80d9-4632be438404)

**NOTE: Any of these adjustments can be reset by clicking the undo buttons (circular arrow rotating counter clockswise) on the upper right of each control.**

10. Now, the shadows in the image appear very dense and dark. Bring up the Gamma exposure to raise the midtones and bring more light into the shadows.

![PostPro25](https://github.com/user-attachments/assets/9aec0f9a-8832-4f2d-b70b-38c9651333c1)

*Shadows in the image appear very dense and dark.*

11. Once the exposure adjustment is set (it can be edited later) move on to adjusting the color balance. To keep things simple, we’ll want to **first adjust Gain, then Lift, then Gamma**.
12. Make an adjustment to the Gain color balance by clicking and dragging the point in the center of the Gain color wheel.

![PostPro26](https://github.com/user-attachments/assets/7cc1c33a-43ab-4bca-a285-55a113e2413f)

*Gain Color Wheel in Davinci Resolve.*

13. Use scopes as a reference but not a crutch; the primary focus should be the image itself. For example, the highlights in this image look quite yellow. To balance them out, move the Gain away from yellow and towards blue.
> a. **NOTE: Increase the size of the image window by pressing Control F and/or Shift F on a windows keyboard, or Option F and/or Shift F on a Mac keyboard.**
14. Scopes are not imperative for this, but may be helpful. Here is a before and after of the image after the Gain adjustment. Notice how the blue channel highlights (top) of the scopes are now closer to the red and green channels.

**Before:**

![PostPro27](https://github.com/user-attachments/assets/f73e6bd5-854f-41f3-ac51-b4ac133c6a8c)

![PostPro28](https://github.com/user-attachments/assets/ea94da60-0307-4e2d-af90-2b7eccecf24e)

**After:**

![PostPro29](https://github.com/user-attachments/assets/3c394e1b-a686-4e72-ba60-484a86468e8d)

![PostPro30](https://github.com/user-attachments/assets/b015aaf6-fbc4-4455-9d87-98ae09d8cc45)

15. After adjusting the highlight color balance with Gain, adjust the black balance with Lift. Such an adjustment may not be necessary. The blacks in the example image appear balanced. This is confirmed by the equal level between at the bottom of the red green and blue channels in the scopes (see above).
16. If any remaining color cast is found in the image, try adjusting the Gamma color balance to see if it helps. Slightly warming up the Gamma of this Dole commercial (by moving the color balance toward red/yellow), results in a more accurate looking image.
> a. **NOTE: Undo a change in Audition by pressing Control + Z (Windows) or Command + Z (Mac).**
17. Scroll through the film and see if any modifications are needed to the correction. Pay special attention to the scopes to make sure nothing is getting clipped.

#### Save the Corrected Film

1. Once color correction is finished, click the Deliver button on the bottom of the screen to jump over to the Deliver Tab:

![PostPro31](https://github.com/user-attachments/assets/15ea4534-cc46-46e9-8193-597f8d9d5289)

*Deliver Tab in Davinci Resolve.*

2. On the Deliver page set the render settings: 
> a. On the top left, select the Custom preset.
> 
> b. In the box next to Filename, type in an appropriate name for the file
>
> c. Click the Browse button next to Location to choose a destination for the file.

![PostPro32](https://github.com/user-attachments/assets/e384dcae-b55c-4858-b2ab-19dda867a4f2)

*Click the Browse button under Custom presets.*

> d. Next to Format, select Quicktime
>
> e. Next to Codec select the preferred codec.
>
> f. Confirm that the Resolution is the same as the timeline resolution (set in Project Settings earlier). If it is not, then type in the timeline resolution.
>
> g. Confirm the framerate is correct (this should generally be 24 fps for 35mm and 16mm)
>
> h. The settings should appear something like this:

![PostPro33](https://github.com/user-attachments/assets/dff6a2f1-f01f-492f-81b7-b30ccfa47c63)

*Render settings in Davinci Resolve.*

3. Once the settings are set properly, click Add to Render Queue.

![PostPro34](https://github.com/user-attachments/assets/908f7564-c704-472c-acfd-97c6176123b4)

4. The render job will appear in the Render Queue in the top right side of the screen. Press Render All.

![PostPro35](https://github.com/user-attachments/assets/ab5c2fd7-8284-428a-b469-8e656f81dd43)

*Press “Render All” when ready to render.*

5. Once the render is complete, locate the file in the save destination. Playback the file to verify there are no problems.
6. To backup a Resolve project, go to File > Export Project, and save the project to a harddrive.

![PostPro36](https://github.com/user-attachments/assets/1d74bad5-df6a-4843-8a58-d87b11591862)

*File>Export Project*

#### Trimming and Splicing Footage (Editing Basics)

1. Ensure that the media is present in the bottom timeline portion of the program, as shown below.

![PostPro37](https://github.com/user-attachments/assets/12a35cf8-9f74-4d40-9774-fe09348fbdf9)

> a. Should this not be the case, navigate to File > Import > then click Media. Navigate to the relevant media, click to select it, then press Open. Drag the media from the left side of the program to the timeline section at the bottom of the program.
2. Click on the Edit Tab at the bottom of the program:

![PostPro38](https://github.com/user-attachments/assets/f02cf16e-fcc4-43c6-bf76-c3971b7200bc)

*Edit Tab.*

3. Above the editing timeline, there is an icon labeled ‘Blade Edit Mode.’ Click on this icon (it will turn red), and the cursor will transform into a splicer. **Please note: to switch back to a regular cursor, for selecting clips as opposed to cutting them, click on the gray cursor button seen below. These two buttons allow one to toggle between Splicing and Selection Modes, both essential for editing (see below):**

![PostPro39](https://github.com/user-attachments/assets/e9f69964-5f3f-451e-bc44-471d957aba7a)

*Blade Edit Mode is selected.*

![PostPro40](https://github.com/user-attachments/assets/2e4eca68-80bc-419a-a4a8-5835848e50ea)

*Selection Mode is selected.*

4. To Zoom In or Zoom Out on the editing timeline, press Command + (plus) or Command - (minus), respectively. There is also a plus-minus slider located above the editing timeline. These commands are essential for navigating through the media and making more precise edits as needed. Click and drag the gray bar at the bottom of the program to scrub through the media. (Or slide a finger left and right across the Mac wireless mouse).
5. With the Blade Mode selected, hover the cursor over the media in the timeline. The cursor will turn into a red line, indicating the location of the splice to be made. To splice the footage, position the red line as needed and click on the footage. The footage will separate into two portions.

![PostPro41](https://github.com/user-attachments/assets/7c082785-d2e5-4240-ab55-b13eb960ae15)

*The red line indicates the location of the splice.*

6. Unwanted artifacts and footage may be removed using the splicing tool. To do so, create two splices, one on either side of the footage to be removed. Toggle to Selection Mode. Click on the unwanted media to highlight it, then press the Delete key.
7. To shorten or lengthen clips via dragging, click on Selection Mode. Position the cursor at the relevant end of the film clip, **until a single white bracket-and-rectangle icon appears. Once this icon is visible, click and hold the mouse, then drag in either direction to shorten or lengthen the clip as needed.**
8. To Undo any editing actions, press Command + Z on the keyboard. (Or Control Z on PC). This may be done multiple times as needed.
9. To Redo any editing actions, Click Edit > Redo in the top left corner of the program.
10. **A note on editing: To prevent gaps in the finished film, all clips must be placed exactly side by side with NO separation between them. When splicing or removing footage, ensure that the ends of each clip lock together exactly and are side-by-side (Resolve will do this clearly and automatically once two clips are dragged together.)** 
11. Please save the edits made **periodically and frequently, via Command + S or File > Save**, to prevent any work from being lost. 
12. Once the film has been edited to completion, Click the rocket ship icon (‘Deliver’) at the bottom of the screen:

![PostPro42](https://github.com/user-attachments/assets/a245cb58-d0b0-4e8c-ae4c-da55bce6be89)

*The resulting space will contain settings for the export. For more information on file formats and codecs, please refer to [Appendix D](#appendix-d-information-on-codecs).*

![PostPro43](https://github.com/user-attachments/assets/acf76941-ada7-4e67-bc2e-e588a883dd29)

#### Adding Subtitles and Intertitles

1. Ensure the Edit Tab is selected:

![PostPro44](https://github.com/user-attachments/assets/7fd1d914-3df3-42a3-8d64-45afbcd64943)

2. In the top left corner of the program, click on the Effects Tab:

![PostPro45](https://github.com/user-attachments/assets/8470e7a5-efac-4a59-b873-c0a9ecaf2225)

3. A menu will appear on the left. Click on Titles to reveal its corresponding menu, as shown below:

![PostPro46](https://github.com/user-attachments/assets/e109e46b-0215-4938-bf8a-c98ce861e535)

*Resolve offers a wide variety of title styles.*

4. Hover over the list of titles to see a preview of that title in the viewer. For most purposes, Basic Title works well. Note: The font for Basic titles can be changed
5. Click and drag the selected title from the left portion of the screen to the editing timeline, and above the main footage (see image on the next page):

![PostPro47](https://github.com/user-attachments/assets/edd7c43f-5306-4062-b298-9f2315b95b2f)

6. Click and drag the yellow timeline marker so it intersects with the title segment in the editing timeline (seen above as the box outlined in red). The subtitle should be visible in the viewer. Double click on the title in the viewer to edit the text.
7. To change the duration of the title, position the cursor at the left or right end of the Title segment **in the editing timeline**, until a white bracket-and-rectangle icon appears. Click and drag the box to the left or right to change the duration of the title.
8. Single click on the title so that it looks like the following:

![PostPro48](https://github.com/user-attachments/assets/d7c000c2-32c5-4d15-8133-d04482bc43df)

9. Click on the center dot to drag the title vertically up or down.
10. To make the title an intertitle, position it as a splice between two segments of footage.
11. To change font, size, and color, select the Inspector Tab in the top right of the program. A corresponding menu will appear (see next page for image).

![PostPro49](https://github.com/user-attachments/assets/1fa92743-5902-4dc7-9c9e-6d9a3c85b243)

12. To change the font, toggle the Font Family and Font Face. To change the color, toggle the Color. To change the size, click and drag the Size slider or enter a number into the corresponding field.

#### Exporting access copies

For access copies of video, one should choose a lossy codec to compress the size of the resulting file. This option is preferred for easier file sharing and storage, and for institutions with less resources for digital storage and file management. It is recommended to export access video copies with one of the following codecs:
* **H264/H265**
* **AVC**
* **AC3**

Avoid the lossless codecs of ProRes and PCM, as they are used for file decompression. Access video copies should be exported as **.mp4** or **.mov** files. While either of these formats are appropriate for access copies, **.mp4** is more compressed, and may be a more appropriate choice. Please follow the instructions below to export access copies:

1. Open Davinci Resolve on the Video Editing Station Mac desktop (power button is located on the top face of the tower, towards the back).
2. Once Resolve is open, import the video to compress:
* Go to File and click on New Project. Rename the project.
* Go to File, Import, then click Media.
* Navigate to the video file, single click to select it, then click Open.

3. If a dialogue box appears asking to change the frame rate, click Allow.
4. The video file will appear on the left side of the screen. Click and drag the file downward into the timeline/workspace section, which occupies the bottom portion of the program.

5. **Convert the file into .mp4/.mov**:
* Click on the Deliver rocketship icon, located at the bottom of the program:

![PostPro50](https://github.com/user-attachments/assets/6cd2858d-5373-4f23-8872-9bc93e4edf7c)

*Rocketship icon in Davinci Resolve*

* Locate the Render Settings menu in the top left of the screen (by the YouTube and Twitter logos):

![PostPro51](https://github.com/user-attachments/assets/cf03436e-f858-4f24-b0d8-58807d182c0b)

![PostPro52](https://github.com/user-attachments/assets/c5875c9e-78aa-44c5-bcd4-cc4bfc89723c)

*Render Setting Menu in Davinci Resolve*

* Click and drag the gray bar to the right, revealing H.264 and H.265. **Note**: Do not be confused by the fact that they say master; there are settings to ensure the file’s compression later on.
* Click on H.264 or H.265, depending on personal preference, to reveal the corresponding menu on the left side of the screen. In the menu, click on the Format menu bar and select MP4 (for a .mp4 file), or QuickTime (for a .mov file).
* Click on the Resolution menu bar, then choose 1920x1080 HD, 1280x720 HD, or 640x480 SD. Choose the resolution according to factors including: available storage, length of video, and desired or necessary quality.

6. **Configure the settings as follows**:

* Rename the file in the Filename field and press ‘Browse’ to set its location. Click Open to confirm.
* Select ‘Video.’
* Ensure that ‘Export Video’ is checked.
* At the very bottom of the menu, underneath Subtitle Settings, click on ‘Add to Render Queue.’ The file will appear on the right side of the screen underneath the Render Queue.

![PostPro53](https://github.com/user-attachments/assets/41bc6734-89e7-490b-9882-942421a8211d)

*In order to export a file from Resolve, it must be added to the Render Queue, selected in the Queue, and then rendered.*

* **Important**: In the Render Queue on the right side of screen, click on the file (it will be highlighted with a white border once selected), then click ‘Render All,’ at the bottom right corner of the screen.
* The progress of the DPX export is observable in the Render Queue. The export will read ‘Completed in’ with an accompanying timestamp, once it is finished.
* Finally, navigate to the save location of the access video copy. Ensure that the resulting file is satisfactory in size and quality.

[DaVinci Resolve Templates | Motion Array](https://motionarray.com/browse/davinci-resolve-templates/effects/?sort_by=most-popular&utm_source=bing&utm_medium=cpc&utm_campaign=626176449&utm_content=1151189655527101&utm_term=davinci%20resolve%20effects&keyword=davinci%20resolve%20effects&ad=&matchtype=e&device=c&msclkid=2def7a94d7a7151e95a51f566037cc3a "DaVinci Resolve Templates | Motion Array")

### AEO Light Workflow

#### AEO Light Overview

AEO Light is an open-source software, developed by the University of South Carolina, for the purpose of extracting sound information recorded on celluloid film. The program uses the scanned copy of a film to analyze and reproduce audio information recorded on the film’s optical soundtrack. The extracted audio can then be incorporated into the preservation master of the scanned film.

#### A Note on Optical Sound

Optical sound was a popular film sound format from the 1920s to the 1970s. On celluloid film, an optical soundtrack will be located along the perforations on one side, and travels the entire length of film.This recording captures the flickering of a light bulb, whose light is recorded and interpreted by a photodiode, which converts it into an electric signal. There are many different types of optical sound formats. The three variations of optical sound include mono, stereo, and multi-track. Refer to [this site for examples of optical sound](https://www.endpointaudio.com/optical-sound-detail"Optical Sound Examples"), as well as the images below:

![AEO1](https://github.com/user-attachments/assets/cecd51b1-0dc7-4318-bdd2-22e182d7d1ee)

![AEO2](https://github.com/user-attachments/assets/d6b2c913-4a9f-4cff-9357-d33e1b182ec7)

![AEO3](https://github.com/user-attachments/assets/29ddf913-9db0-4809-aa2f-cd0114a99fee)

*Three optical soundtracks. The top and bottom films have single-track audio, whereas the center film has multi-track audio.*

#### Convert files into DPX using DaVinci Resolve

Before AEO Light can extract audio from a film’s soundtrack, the film scan must be converted into a set of DPX files, using Davinci Resolve. This produces a scanned image for every frame of the film (do not worry; the program only requires one frame to be selected to work). Please follow the conversion instructions which follow:

1. Open Davinci Resolve on the Video Editing Station Mac desktop (power button is located on the top face of the tower, towards the back).
2. Once Resolve is open, import your film scan:
* Go to File and click on New Project. Rename the project.
* Go to File, Import, then click Media.
* Navigate to the scanned film, single click to select it, then click Open.
3. If a dialogue box appears asking to change the frame rate, click Allow.
4. The film scan file will appear on the left of the screen. Click and drag the file downward into the timeline/workspace section, which occupies the bottom portion of the program.
5. **Convert the file into DPX**:
  * Click on the Deliver rocketship icon, located at the bottom of the program window:

![AEO4](https://github.com/user-attachments/assets/dd6a4eaa-03a5-47d8-af57-cfad667e983f)

*Rocketship icon in Davinci Resolve*

* Locate the Render Settings menu at the top left of the screen (by the YouTube and Twitter logos):

![AEO5](https://github.com/user-attachments/assets/225e8efa-6849-4110-bc32-20db6e6f1f0b)

![AEO6](https://github.com/user-attachments/assets/f7413222-4dad-4c07-a7ef-f9847c25e9cb)

*Render Setting Menu in Davinci Resolve*

* Click and drag the gray bar to the right, revealing ‘ProRes.’
* Click on ProRes to reveal its corresponding menu on the left side of the screen. In the ProRes menu, click on the Format menu bar and select DPX from the dropdown options.

![AEO7](https://github.com/user-attachments/assets/871ded5a-1305-4269-b95c-2e54e1194030)

6. **Configure the settings as shown above**:
* Rename the file in the Filename field and press ‘Browse’ to set its location. Click Open to confirm.
* Select ‘Video.’
* Select ‘Individual clips.’ 
* Ensure that ‘Export Video’ is checked.
* Ensure that the Codec selected is ‘RGB 10 bits’
* At the very bottom of the menu, underneath Subtitle Settings, click on ‘Add to Render Queue.’ The flle will appear on the right side of the screen underneath the Render Queue.

![AEO8](https://github.com/user-attachments/assets/860bcb21-4e12-42be-9234-74169c2dc11f)

*In order to export a file from Resolve, it must be added to the Render Queue, selected in the Queue, and then rendered.*

* **Important**: In the Render Queue on the right, click on the file (it will be highlighted with a white border to indicate its selection), then click ‘Render All,’ at the bottom right corner of the screen.
* The progress of the DPX export is observable in the render queue. The export will read ‘Completed in’ with an accompanying timestamp once it is finished. **As a reminder**: the program will export several DPX files, one for each frame scanned.

#### Open DPX files in AEO Light

1. Click on the desktop icon for AEO Light:

![AEO9](https://github.com/user-attachments/assets/eff67af0-66c7-4b77-a98b-09baec65a173)

2. In the window that opens, click the New Project button (located in the top left corner).
3. Navigate to the location of the saved DPX files. Double click on any one of the DPX files in the save folder (it makes no difference which one is selected).
4. A separate viewing window will appear with a scanned frame.
5. Click on the AEO Light MainWindow, which contains the settings. Locate the ‘Scan Frame’ field towards the bottom right (shown below). **Please note**: The number in this field corresponds to the frame that appears in the viewing window. 

![AEO10](https://github.com/user-attachments/assets/df48a3ed-cc75-4a4e-8f17-dc537b880781)

*The number in the ‘Scan Frame’ section corresponds to the DPX file for that number frame.*

* Change the number in the ‘Scan Frame’ field to select **any frame of the film scan that contains an optical soundtrack**. For help determining which number frame to select, navigate to the folder of saved DPX files, then type its number into the ‘Scan Frame’ field. Look at the frame in the viewing window to confirm that an optical soundtrack is present.

#### Adjust the Soundtrack’s Legibility

1. Depending on the type of optical soundtrack, it may be advantageous to adjust the lift, gamma and gain of the image, to make the soundtrack more legible for the program. Click on the ‘Image Processing’ tab, located to the right of ‘Soundtrack Settings,’ to view the settings for Lift, Gamma, Gain, S Curve, and Blur/Sharp. Refer to the image below:

![AEO11](https://github.com/user-attachments/assets/588af34f-4414-4ac1-b5d2-8d06742f85ef)

*The settings above may be adjusted to get a more accurate reading of the optical soundtrack.*

* If the scanned film is a negative, please **check** the ‘Negative’ box in the lower left corner (refer to the image above).

2. Click on the ‘Extract Audio’ tab, located to the right of ‘Image Processing.’ A menu with options will appear (refer to image below). Ensure the following settings are selected:
* Set ‘Frame In’ to 0 (this should be automatically selected).
* Set ‘Frame Out’ to the **last numbered frame** in the DPX series. Please ensure that the timecode next to the Frame Out field represents the **correct duration for the entire scan**.
* Set the Sampling Rate to 96 kHz.
* Set the Bit Depth to 24 Bit.
* **Please note**: These latter two settings are the archival standard and are recommended for most projects.

![AEO12](https://github.com/user-attachments/assets/d6c2368c-c796-44ac-b8f7-8f70faefb7b6)

*Settings which conform to archival standards*

#### Preparing the Soundtrack Scan

1. Click on the ‘Soundtrack Settings’ tab.
* Set the correct channel configuration for the optical soundtrack:
> * If the film scan has one track of audio, select ‘Mono.’
> * If the film scan has two tracks of audio, select ‘Stereo.’
> * Refer to [Endpoint Audio Labs](https://www.endpointaudio.com/optical-sound-detail "Optical Sound Examples") to aid in soundtrack identification.

![AEO13](https://github.com/user-attachments/assets/109c24ff-0a5a-467c-be87-a89803306d18)

*Viewing window and settings in AEO-Light*

2. Set the boundaries of the optical soundtrack. These boundaries indicate the region of the image which the program will scan for audio information.
* Use the upper soundtrack control fader to move the red line, which denotes the left boundary of the optical soundtrack (refer to image below). 
* Use the lower “soundtrack control” to move the magenta line, which denotes the right boundary of the optical soundtrack (refer to image below).

![AEO14](https://github.com/user-attachments/assets/c6d7bae6-93ba-4694-8856-a955f6e83818)

*Setting optical audio track boundaries in AEO-Light*

3. Use the “Frame Pitch Start” and “Frame Pitch End” controls to indicate the upper and lower boundaries of the frame:
* Set the white “Frame Pitch Start” line on the upper boundary of the frame. 
* Set the magenta “Frame Pitch End” line on the lower boundary of the frame.
4. Scroll through the film by dragging the control beneath the “Scan Frame” field. Ensure the horizontal magenta and white lines that bound the individual frames move around while flipping through the frames.

#### Sample the audio track 

1. Click the ‘New Sample’ button on the bottom half of the window to create a 5 second sample of audio, which will play back automatically. 
2. In the popup window, select a Sample Audio slot, then click Save (refer to the image below). **Please note**: the samples may be played back in the MainWindow at the bottom, via the ‘Play Sample’ buttons.
3. To change the segment of film from which the sample is taken, change the number in the ‘Frame Scan’ field, or drag the slider below this field, then click ‘Set In.’ Repeat Steps 1-2. Collect samples at various points in the film, monitoring the sound quality until satisfied.

![AEO15](https://github.com/user-attachments/assets/2a32a472-bd93-4584-a46c-abd6158cd329)

*Save Sample Audio in AEO-Light*

#### Extract the Audio

1. Click the ‘Extract Audio’ menu, then click ‘Extract.’ 
2. In the window that opens, use the ‘Output Name’ field to name the field. In addition to audio, AEO Light can render a compressed video reference file with the. To perform this option, select ‘Output Video,’ located below the ‘Output Audio’ line. Click the blue ‘Browse’ button to specify the save location, then press OK at the bottom to commence the audio extraction.

![AEO16](https://github.com/user-attachments/assets/3dd039bb-0c3d-44c1-a479-a08a7016d85b)

*Extract to Audio File Settings in AEO-Light*

3. A mini window with a blue bar will appear to indicate the progress of the audio extraction. Once the mini window closes, the extraction is complete.

#### Adding Soundtrack in DaVinci Resolve

1. Open Davinci Resolve. In the recent files window that appears, double click on the thumbnail for the saved media file (the same file from the DPX export process).
2. Click on the icon for the Edit tab, located at the bottom of the program (shown below):

![AEO17](https://github.com/user-attachments/assets/af66a7e3-0c02-4842-8faa-5b658855e593)

*Edit Tab Icon in Davinci Resolve*

3. In the top right of the program, click ‘File,’ then hover over Import, and click Media.
4. Navigate to the .mp4 file saved from AEO Light. Single click to select the file, then click Open.
5. The audio file will appear in the media bin section on the left of the program. Click and drag the audio file into the ‘Audio’ section of the editing timeline, just below the video section containing the film content. Ensure that the audio and video files are aligned by playing the film back with the play button on the media player.
6. Now that the audio has been added to the timeline, the audio and video must be exported together as a single file to create the soundtracked film. As in the DPX export process, click the Export rocketship icon at the bottom of the program, shown below:

![AEO18](https://github.com/user-attachments/assets/557697a9-edc2-43ac-9e7b-5a52074f9502)

7. In the top left corner of the screen, click and drag the gray bar located underneath the social media icons to the right. Click on H.264 to reveal its corresponding menu (H.264 is the standard for film exports. Ensure that ‘Export Video’ and ‘Export Audio’ are both checked. Name the file in the ‘Filename’ field, then click Browse to select the save location. 
8. At the bottom left of the H.264 menu, click on ‘Add to Render Queue.’ This job should appear in the Render Queue on the right side of the program. Click to select it (it should be highlighted with a white border). In the bottom right corner of the program, press ‘Render.’ Once the job in the Render Queue reads ‘Completed’ in green text, Resolve has exported your finished film with the soundtrack.

## Troubleshooting

## Appendix A: Film Format Identification

Format | Image | Description
:--- | :---: | :---: 
**8mm** | ![AppA1](https://github.com/user-attachments/assets/84bba5dd-913a-407e-94b0-71e9b36f4054) | An image of 8mm film. As compared to Super 8 film, the image is smaller and the perforations on the left are larger.
**Super 8** | ![AppA2](https://github.com/user-attachments/assets/d5a522f8-8762-4cfb-a471-1cf339d32352) | An image of Super 8 film. As compared to 8mm, the image is larger and the perforations on the left are smaller.
**16mm** | ![AppA3](https://github.com/user-attachments/assets/e50d9ec3-62a3-4d32-a076-6d0d76b6d232) | An image of 16mm film. Optical soundtrack on the left edge. Perforations to the right of the image. As compared to 8mm and Super 8 film, the size of the image is much larger in relation to the perforations.
**35mm** | ![AppA4](https://github.com/user-attachments/assets/5f170778-a282-477b-a236-83eeedda00ab) ![AppA5](https://github.com/user-attachments/assets/ff79d4bd-9870-4ade-b7b3-1636fce49998) | Two images of 35mm film. All 35mm film has two rows of perforations on either side of the image. The top image displays a segment of 35mm film with an optical soundtrack recording to the right of the image. The bottom image displays a segment of 35mm film with no soundtrack. Both segments have an edge-code written on the right side, indicating the year of the film’s production. 

Compared Formats | Image  
:--- | :---:   
35mm vs 16mm vs 8mm vs Super8 | ![AppA6](https://github.com/user-attachments/assets/ea319563-e743-4469-9b72-5c7b3732cb50) 

**35mm**
* Largest image
* Perforations on either side of the image
  
**16mm**
* 2nd largest image
* Perforations on the right side
* Second smallest perforations
* Largest image in relation to perfs
  
**8mm**
* Smallest image
* Perforations on the right side
  
**Super 8**
* 2nd smallest image
* Perforations on the left side
* Smallest perforations

Compared Formats | Image 
:--- | :---: 
**Super 8 vs 8mm** | ![AppA7](https://github.com/user-attachments/assets/8f0a02b3-7b53-402f-a64e-6fc49e57e420)

**8mm**
* Smaller image
* Perforations on the right side
* Larger perforations

**Super 8**
* 2nd smallest image
* Larger image
* Smaller perforations

## Appendix B: Key Commands for Resolve 

### File

Action | Key Command - Mac | Key Command - PC
:--- | :--- | :---
New Bin | Shift + Command + N | Shift + Control + N
New Timeline | Command + N | Control + N
Save Project | Command + S | Control + S
Save Project As | Shift + Command + S | Shift + Control + S
Import Project | Command + I | Control + I
Export Project | Command + E | Control + E

### Timeline Navigation

Action | Key Command - Mac | Key Command - PC 
:--- | :--- | :---
Go to First Frame | ; (semicolon) | ; (semicolon)
Go to Last Frame | ‘ (apostrophe) | ‘ (apostrophe)
Play Around Current Frame | / | /
Go to Timeline Start | Function + Left Arrow | Home
Go to Timeline End | Function + Right Arrow | End
Previous Clip / Edit | Arrow Up | Arrow Up
Next Clip / Edit | Arrow Down | Arrow Down
Step One Frame Reverse | Arrow Left | Arrow Left
Step One Frame Forward | Arrow Right | Arrow Right

### Marking

Action | Key Command - Mac | Key Command - PC
Mark In | I | I
Mark Out | O | O 
Clear In | Option + I | Alt + I
Clear Out | Option + O | Alt + O
Mark Clip | X | X
Add Marker | M | M 
Add & Modify Marker | Command + M | Control + M
Modify Marker | Shift + M | Shift + M
Delete Marker | Option + M | Alt + M 

### Playback

Action | Key Command - Mac | Key Command - PC 
:--- | :--- | :---
Pause/Start Playback | Space | Space
Play Reverse | J | J 
Stop | K | K 
Play Forward | L | L 
Fast Forward | Shift + L | Shift + L
Fast Reverse | Shift + J | Shift + J
Loop/Unloop | Command + / | Control + /
Play In To Out | Option + / | Alt + /
Play To Out | Option + Command + / | Alt + Control + /

### Editing

Action | Key Command - Mac | Key Command - PC
:--- | :--- | :---
Normal Edit Mode | A | A
Trim | T | T
Blade | B | B
Razor | Command + B | Control + B
Insert Edit | F9 | F9
Overwrite Edit | F10 | F10
Replace Edit | F11 | F11
Place On Top Edit | F12 | F12
Delete Selected | Backspace | Backspace
Fit To Fill | Shift + F11 | Shift + F11
Append At End | Shift + F12 | Shift + F12
Dynamic Trim Mode | W | W
Select Clips Forward on This Track | Y | Y
Select Clips Backward on This Track | Command + Y | Control + Y
Edit Point Type | U | U 
Select Nearest Edit Point | V | V
Snapping On / Off | N | N 
Nudge One Frame Left | ,(comma) | ,(comma)
Nudge One Frame Right | .(period) | .(period)
Select Nearest Clip/Gap | Shift + V | Shift + V
Linked Selection | Shift + Command + L | Shift + Control + L
Clip Link | Option + Command + L | Alt + Control + L
Enable Clip | D | D
Split Clip | Command + \ | Command + \
Join Clips | Option + \ | Option + \

### Effects

Actions | Key Command - Mac | Key Command - PC
:--- | :--- | :---
Add Transition | Command + T | Control + T
Retime Controls | Command + R | Control + R 
Reset Retime | Option + Command + R | Alt + Control + R
Paste Attribute | Option + V | Alt + V
Add Static Keyframe | Command + [ | Control + [
Add Keyframe | Command + ] | Control + ]
Delete Keyframe | Option + ] | Alt + ]
Go to Previous Keyframe | [ | [
Go to Next Keyframe | ] | ]

## Appendix C: Identifying Edge Codes

### 8mm

[Kodak Edge Codes](https://www.filmforever.org/Edgecodes.pdf "Edgecodes")
This list is not reliable for the purpose of absolute accuracy, but is intended for guidance only, in the absence of a definitive list from Kodak.

![Edge1](https://github.com/user-attachments/assets/b4608112-9c77-4bc1-9d18-55cfa7815189)

![Edge2](https://github.com/user-attachments/assets/641c4ac3-a8e5-4509-a33e-37525348cf8b)

![Edge3](https://github.com/user-attachments/assets/2bc4a366-92c7-4ba9-b88e-39452ba4e93e)

![Edge4](https://github.com/user-attachments/assets/076c610d-a1c5-44cc-bc81-0213ac2cf79f)

### 16mm

![Edge5](https://github.com/user-attachments/assets/8a76ee08-949a-40a4-8641-7af9873043e4)

![Edge6](https://github.com/user-attachments/assets/28001bf0-56ee-4eaf-83ab-a90dc8acbc1a)

![Edge7](https://github.com/user-attachments/assets/7d9e993c-7ce0-4dde-a897-d95375e04f18)

## Appendix D: Information on Codecs

It is important to understand the relationship between digital file formats and the amount of information that each format can store. The term “codec” refers to the process of information compression or decompression, which is used to create a particular file format. The two main types of codecs are:
1. **Lossy**: These codecs compress information to make a file easier to access, store, and send.
2. **Lossless**: These codecs decompress information to make higher quality recordings, used for masters and professional presentations or deliverables.

For digital files, there are several formats (also called “wrappers” or “containers”) which archivists and preservationists will commonly encounter. **Transcoding** refers to the process of converting one file format into another. Below is a non-exhaustive list of the most common formats for digital video and audio files:
* .mov
* .mp4
* .mkv
* .avi
* .wav
* .aiff
* .mp3
* .flac

**For digital video files**:
* H264, H265, and AVC are **lossy** files that are **smaller** in size.
* ProRes is a **lossless** file that is **larger** in size. These files require a more powerful computer to be played.

For digital audio files:
* AC3 is a **lossy** file that is **smaller** in size.
* PCM is a **lossless** file that is **larger** in size.

Bit rate and sample depth are also adjustable when exporting a given file. Both of these specifications:
* will impact the quality of the recording.
* will impact the size of the file.
* It is recommended to adjust these settings to find an ideal balance between quality and storage.
* For streaming or screening purposes, a bit rate of 6000 kbps or higher is recommended.

## Appendix E: Film Inspection Sheet

See the [Film Print Condition Inspection Sheet](https://drive.google.com/file/d/1H4ACNfROGbrhsVLwagqfkyOD2hZ8wzC4/view?usp=sharing) for a printable film inspection sheet. 
