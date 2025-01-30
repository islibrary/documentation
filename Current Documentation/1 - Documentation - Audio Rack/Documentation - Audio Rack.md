# IS Library and Media Preservation Lab: Audio rack workflow documentation

*Last updated: April 22, 2024*

## Overview
The audio rack workflow documentation is a comprehensive guide for utilizing the audio rack in the IS Media Preservation Lab (IS Lab for short). This guide includes workflow instructions for using the transfer software, WaveLab Pro 11, and all playback decks in the audio rack.

This documentation covers:

**Pre-digitization:** selecting the correct deck for the digitization project, cleaning and preparing media for optimal transfer, and establishing a signal path prior to transfer.

**Digitization:** workflow for converting analog data to digital formats using WaveLab 11.

**Post-digitization:** directions for file management and storage, and considerations for digital preservation and description (e.g. metadata creation).

The IS Lab audio rack supports the following formats: 

  * Audio cassette
  * Minidisc
  * Microcassette
  * DAT (digital audio tape)
  *  ¼’’ Open reel tape, 
  * Vinyl record, 
  * 78 Shellac Transcription disc
  * Lacquer/Acetate Disc

## Table of Contents

[IS Library and Media Preservation Lab: Audio rack workflow documentation](#is-library-and-media-preservation-lab-audio-rack-workflow-documentation)

[Overview](#overview)

[Resources](#resources)
> [Wavelab Resources](#wavelab-resources)

[Guidelines and Rules](#guidelines-and-rules)

[Pre-Digitization](#pre-digitization)
> [Audio Rack Workflow](#audio-rack-workflow)
> > [Identifying audio formats and choosing the correct deck](#identifying-audio-formats-and-choosing-the-correct-deck)
> > 
> > [Required Inspection](#required-inspection)
> > 
> > [Cassette Tapes](#cassette-tapes)
> > 
> > [Quarter Inch Tapes](#quarter-inch-tapes)
> >
> > [Playback Considerations](#playback-considerations)
> >
> > [Mold and Dirt](#mold-and-dirt)
> >
> > [Grooved Media Deterioration](#grooved-media-deterioration)
> >

[Audio Rack Equipment](#audio-rack-equipment)

[Turning on the Equipment](#turning-on-the-equipment)

[Setting the Signal Path on the Prism](#setting-the-signal-path-on-the-prism)
> 
> [About the Prism ADA-8XR](#about-the-prism-ada-8xr)
> 
> [Configuring the Audio Patch Bay](#configuring-the-audio-patch-bay)

[Digitization](#digitization)
> [Wavelab 11 Recording Workflow](#wavelab-11-pro-workflow)
> 
> > [Opening Wavelab](#opening-wavelab-11)
> > 
> > [Perform a 10-second test capture](#perform-a-10-second-test-capture)
> > 
> > [Record](#record)
>
> [Exporting Derivative Files in WaveLab Pro 11](#exporting-derivative-files-in-wavelab-pro-11)
> > 
> > [Export Preservation Master](#export-preservation-master)
> >
> > [Export Access Master](#export-access-master)
> >
> > [WaveLab RestoreRig (restoration tools) workflow](#wavelab-restorerig-restoration-tools-workflow)
>
> [Powering down audio rack](#powering-down-the-audio-rack)

[Metadata Capture](#metadata-capture)
> > [A Note on Metadata Entry](#a-note-on-metadata-entry)
> 
> [PBCore](#pb-core)
>
> [Dublin Core](#dublin-core)

[Appendix A: Supported Formats and Identification Guide](#appendix-a-supported-formats-and-identification-guide)
> [Supported format and Identification Chart](#supported-format-and-identification-chart)
> 
> [Timeline of Audio Formats](#timeline-of-audio-formats)

[Appendix B: Identifying Vinegar Syndrome & Sticky-Shed Syndrome](#appendix-b-identifying-vinegar-syndrome--sticky-shed-syndrome)

[Appendix C: Baking Audio Tape](#appendix-c-baking-audio-tape)

[Appendix D: Reading Spectrograms in WaveLab](#appendix-d-reading-spectrograms-in-wavelab)

[Appendix E: Timestep Archival Pre Amp](#appendix-e-timestep-archival-pre-amp)

[Appendix F: Stylus Selection](#appendix-f-stylus-selection)
> [Types of Styli](#types-of-styli)
>
> [Other Considerations](#other-considerations)
> > [Nude and Bonded Styli](#nude-and-bonded-styli)
> >
> > [Round and Square Shank](#round-and-square-shank)
> >
> > [A Note on Cartridges](#a-note-on-cartridges)

[Appendix G: Replacing Styluses and Balancing the Tone arm (Lab Staff Only)](#appendix-g-replacing-styluses-and-balancing-the-tone-arm-lab-staff-only)

[Appendix H: Keith Monks Record Cleaning Machine Information](#appendix-h-keith-monks-record-cleaning-machine-information)

[Appendix I: Demagnetizing Audio Playheads (Lab Staff Only)](#appendix-i-demagnetizing-audio-playheads-lab-staff-only)

[Appendix J: Guidelines for DAT Inspection and Playback](#appendix-j-guidelines-for-dat-inspection-and-playback)

## Resources
[UCLA Media Archival Studies Research Guide](https://guides.library.ucla.edu/mas "UCLA Media Archival Studies Research Guide")

Resources for media preservation from the UCLA Library, intended for students in the Media Archival Studies program.

[UCLA Library Audio Archiving Guide](https://guides.library.ucla.edu/mas/audio "UCLA Library Audio Archiving Guide")

A collection of resources on audio archiving from UCLA Library’s Media Archival Studies Research Guide. Publications and websites are included.

[ARSC Guide to Audio Preservation](https://www.clir.org/wp-content/uploads/sites/6/pub164.pdf "ARSC Guide to Audio Preservation")

The ARSC Guide to Audio Preservation is a practical introduction to caring for and preserving audio collections. It is aimed at individuals and institutions that have recorded sound collections but lack the expertise in one or more areas to preserve them. Commissioned for and sponsored by the National Recording Preservation Board of the Library of Congress. Copublished by the Association for Recorded Sound Collections, the Council on Library and Information Resources, and The Library of Congress.

[FACET Field Audio Collection Evaluation Toolkit](https://dlib.indiana.edu/projects/sounddirections/facet/facet_formats.pdf "FACET Field Audio Collection Evaluation Toolkit")

An excellent resource for the identification and risk assessments of audio formats. Also make recommendations on preservation priorities due to risk factors.

[NEDCC Fundamentals of AV Preservation](https://www.nedcc.org/preservation-training/fundamentals-of-av-preservation "NEDCC Fundamentals of AV Preservation")

Textbook created by NEDCC along with a fee-based accompanying [course](https://www.nedcc.org/preservation-training/fundamentals-of-av-preservation).

[Guidelines on the Production and Preservation of Digital Audio Objects](https://www.iasa-web.org/tc04/audio-preservation "Guidelines on the Production and Preservation of Digital Audio Objects")

This is the English language web edition of IASA-TC 04 (Second Edition, 2009), an accepted authority on digital audio preservation in the sound archiving field.

[University of Illinois’ Preservation Self-Assessment Program](https://psap.library.illinois.edu/collection-id-guide/audiotape "University of Illinois’ Preservation Self-Assessment Program")

Timeline of format obsolescence featuring a collection of images to help with the identification of open reel and cartridge-based audio formats.

[Sticky-Shed Syndrome and Audiotape Baking from Arizona State Libraries](https://archivistapprenticeship.wordpress.com/2017/12/13/sticky-shed-syndrome-in-audiotapes/ "Sticky-Shed Syndrome and Audiotape Baking from Arizona State Libraries")

Introductory blog post concerning the warning signs for sticky-shed syndrome, as well as preservation considerations for audiotape.

[Care, Handling, and Storage of Audio Visual Materials](https://www.loc.gov/preservation/care/record.html "Care, Handling, and Storage of Audio Visual Materials")

Guidelines for preservation and long term care for various audio formats from the Library of Congress.

[PBCore](https://pbcore.org/ "PBCore")

PBCore is a cataloging standard for the description of audiovisual content, a data sharing tool, and much more. Since its development in the early 2000s, dozens of organizations have been using PBCore's comprehensive and flexible features for their archiving needs. Consult this website for an overview and video tutorials on using PBCore for metadata management.



### Wavelab Resources

[WaveLab Pro 11.2.0 Operation Manual](https://steinberg.help/wavelab_pro/v11/en/WaveLab_Pro_11_Operation_Manual_en.pdf "WaveLab Pro 11.2.0 Operation Manual")

Comprehensive manual for WaveLab Pro 11 software. An in-depth technical companion intended to supplement the introductory-level knowledge of this documentation.

[Single Song Mastering in the Audio Montage - WaveLab Pro Workflows w/ Justin Perkins](https://www.youtube.com/watch?v=7yH8-ZFSfFk "Single Song Mastering in the Audio Montage - WaveLab Pro Workflows w/ Justin Perkins")

Video tutorial on single song mastering and editing, one of the most-used functions in WaveLab Pro 11.

[All of Justin Perkins’ WaveLab Workflows on YouTube](https://www.youtube.com/results?search_query=justin+perkins+wavelab "All of Justin Perkins’ WaveLab Workflows on YouTube")

YouTube playlist containing video walkthroughs, tutorials, and workflows for every aspect of the WaveLab Pro 11 software.

[Izotope - “Understanding Spectrograms"](https://www.izotope.com/en/learn/understanding-spectrograms.html "Izotope - 'Understanding Spectrograms'")

Article explaining spectrograms and other important elements to monitor during the audio transfer process. Consult this resource for noise reduction and removal using WaveLab RestoreRig.

[Wavelab Export Workflow Tutorial](https://drive.google.com/drive/u/0/folders/1--f5oU3bb0ALXTbzm2NCatdvxr3gqum7 "Wavelab Export Workflow Tutorial")

Google Drive folder containing video tutorials on how to export the finished audio files from WaveLab Pro.

[The RestoreRig Plug-in Suite](https://www.youtube.com/watch?v=yXDx0OnRNwY "The RestoreRig Plug-in Suite")

Video tutorial on the sound restoration tools available in the RestoreRig plugin on WaveLab. Please note: while applicable, the tutorial is not based on the most current version of the software.. 

## Guidelines and rules 
Please contact an IS Lab Staff team member for any and all questions about the guidelines listed below.

1. Leave all food and drinks outside of the lab on the designated table in Zone A of the library.
2. **Do not clean any deck’s audio heads. Please ask a staff member for assistance.**
3. If any equipment or software stops working or breaks during transfer, **immediately contact an IS Lab staff team member** for assistance.
4. **All tapes need to be inspected before using any deck** to ensure the tape is safe to transfer. For any questions about the quality of a tape, ask an IS Lab staff member. 
> a. If the magnetic material on the tape looks broken or cracked, it is very possible that the tape has been affected by **Sticky-shed syndrome**. Refer to [Appendix B](#appendix-b-identifying-vinegar-syndrome--sticky-shed-syndrome) for more information on sticky-shed syndrome.
5. Keeping audiotape away from humid temperatures is highly recommended. Whenever possible, store in air-tight containers. 
6. For certain tapes, baking is a requirement in the IS Lab in order to ensure the preservation of our vintage equipment. For guidelines on baking, please visit [Appendix C: Baking](#appendix-c-baking-audio-tape). 
7. For first-time use of decks and first-time audio transfers, please reach out to a member of the IS Lab Staff for assistance.
8. If materials needed to complete a project are lacking or out of stock (e.g. gloves, alcohol, etc.), please inform a member of the IS Lab Staff so that they may place an inventory request. 
9. Copy files to the appropriate IS Lab server folder or to a personal storage device after transferring. **Do not leave files on the transfer computer’s hard drive or desktop**—all files are deleted from the computer at the end of each week.



## Pre-Digitization

### Audio rack workflow

#### Identifying audio formats and choosing the correct deck 
Prior to digitization, it is necessary to identify the correct deck and format for media transfers. Refer to [Appendix A](#appendix-a-supported-formats-and-identification-guide) and the [list of audio formats in the overview section](#supported-format-and-identification-chart) to identify the format of a selected tape, choose the correct deck for playback, prepare the media prior to transfer, and ensure the protection of equipment while working with the audio rack transfer station.

After identifying formats and decks for digitization, contact a lab staff team member to ensure all heads are clean prior to proceeding with the transfer. This step ensures that the transfer of information will be smooth and accurate.

#### Required inspection
**Inspection is required before playing back any media in the audio rack.** Inspection helps to ensure that transfers will not cause undue stress or damage to IS Lab equipment. The inspection process also aids the identification of the proper settings for a given piece of media, which will ensure a clean transfer. 

**Equipment in the audio rack is expensive and/or obsolete, and replacement parts can be difficult to come by. Therefore, IS Lab kindly asks for the exercise of attention and caution during the use of all equipment, so as to mitigate costly repairs. This starts with the inspection process.**

#### Cassette Tapes
1. Check for signs of microbial growth. Mold may appear as fuzzy threadlike or hairy growth on the tape pack.Typically, these growths are white in color although they may also be black, brown, or mustard-colored. **Do not playback for any tape showing signs of fungal growth in the IS Lab. Likewise, in the case of uncertainty about fungal growth, do not attempt playback.** 
2. Check tape using the plastic window for pack/wind issues, stretching, twists, or creases. See that the tape path is tight and fed straight across the pads, pinch rollers, and hub teeth. 
3. The type of tape will change its susceptibility to deterioration, resulting in high-end dropout at the start of the tape.
4. Consider tape length (90, 100, 110, or 120 min) and likelihood of getting caught, stretched, and damaged in the machine.
5. Inspect pads, pinch rollers, hub teeth, and protective slips. 
6. Rehousing and repair:
> a. Pull the tape tightly against the supply reel to ensure the leader is securely attached. If it unwinds unevenly during an initial hand winding, rehouse or repair the tape before playback.
7. Ensure that a sufficient amount of leader is attached and in good enough condition for playback.
8. Assess the overall safety of playing tape and anticipate any potential difficulties  to monitor during playback.
9. Determine the ideal storage conditions for longevity (container, shelf orientation, temperature and humidity controls).
10. **Check the slots on the top of tape, to identify it as a Type I, Type II, or Type IV tape.** This verifies that the settings on the tape deck are correct to ensure proper playback. For assistance, refer to the chart below:

Cassette Type | Image | EQ Curve
:---: | :---: | :---: |
Type IV | ![Cassette Types](https://theaudioowl.com/wp-content/uploads/2020/02/cassette-tape-type-notches.png?ezimgfmt=ng:webp/ngcb16)|70 μs
Type III| ^ | 70 μs 
Ty[e II ("high bias") | ^ | 70 μs 
Type I ("normal bias") | ^ | 120 μs 

“EQ Curve” refers to the low frequency boost and high frequency rolloff applied to the recording. Different cassette types were manufactured to be recorded with different EQ curves applied. On many tape decks, the notches in the top of the tapes correspond to the cassette type, and automatically apply the correct EQ accordingly. The Nakamichi Dragon requires users to set the EQ settings manually. 

11. Type III vs. Type I tapes. These two varieties have the same notch positioning and different EQ curves; distinguishing between the two is difficult and necessary. Type III tapes are made with a ferro chromium magnetic formulation: look for FeCr or “ferro chromium” on the tape’s packaging.
12. Select the appropriate EQ curve to be applied by the Nakamichi dragon (refer to the chart on the previous page). Labels have been adhered next to the EQ buttons on the Gray Nakamichi Dragon CAS 1 for assistance.


![NakamichiEQButtons](https://github.com/user-attachments/assets/6261cc58-15c0-4651-af11-f96b88785894)

*If the “Eq (μsec)” button is out, that means the deck is applying the 120 μs suitable for type I cassettes. For other tape types, press the “Eq (μsec)” in.*

13. **Dolby NR**: Determine if the tape was recorded with Dolby NR, and if so, select the appropriate form on the Dragon. Dolby NR identification is usually indicated on the tape itself, either in notes accompanying the tape or a logo on the cassette shell with Dolby NR logo. In the case of uncertainty about whether or not a tape was recorded with Dolby NR, **leave this setting turned off** on the Nakamichi Dragon.


![DolbyNRButtons](https://github.com/user-attachments/assets/0bac77d5-5a8b-4ac9-b0ff-01f4568f3010)

*Correct positions of the Dolby NR B-Type and C-Type buttons for each formulation of Dolby on the Nakamichi Dragon Tape Decks. 
Source: Nakamichi Dragon 3 Head Tape Deck manual.*


#### Quarter-inch Tapes
1. Identify tape type (acetate or polyester-based stock). 
> a. Acetate: Identify potential issues, such as vinegar syndrome
> b. Polyester: Identify potential issues, such as sticky-shed syndrome, and if the tape easily comes off the reel.
2. Examine for pack wind, curling, cupping, stretching, twists, creases, or folds.
3. Check for adequate leader or add additional leader as needed.
4. Assess for tears, breaks, or splices requiring repair.
5. Consider tape thickness and susceptibility to damage.
6. Check for warping of the reel.
7. Assess safety for playback and anticipate difficulties to monitor during transfer.
8. Determine ideal storage conditions.



#### ¼” Open Reel Audio Tape
1. **Identifying the base of audio tape** 
> **a. Acetate**: It is common to find acetate-based ¼” audio tape. This format was the predominant tape base until the 1970s. It can be identified by its transparency, in comparison to the opaqueness of polyester tape. Light will pass through the tape pack of acetate tape. Acetate-based tape will also break easily and cleanly when torn by hand, as opposed to polyester-based tape.
> 
> **b. Polyester**: Polyester is one of the most commonly found tape bases. It was first developed in the 1950s and came into wide use in the 1970s and 1980s. It can be identified by its opaqueness under light, in contrast to the transparency of acetate-based tape. If the tape is opaque and light does not pass through, it is most likely Polyester, unless it is one of the named PVC brands [mentioned in the PSAP guide](https://psap.library.illinois.edu/collection-id-guide/audiotape "mentioned in the PSAP guide"). Polyester stretches when pulled by hand, as opposed to acetate-based tape, which breaks cleanly. 


![PolyesterOrAcetate](https://github.com/user-attachments/assets/ed966c81-b16b-4296-b493-f8a1e0544579)

*Polyester vs acetate. From ARSC Guide to Audio Preservation pg. 26.* 

> **c. Paper**: It is unlikely that a tape would be paper-based, due to the limited adoption of the format. Paper was used as a base for magnetic audio tape from ca. 1935-1950, but was eventually phased out, as it was seen as inferior to acetate-based tape.
>
> **d. PVC**: Polyvinyl chloride is a fairly rare base of audio tape. It was mainly used by one German company BASF, from around 1942-1970. It is difficult to distinguish PVC tape from Polyester as they both appear opaque when light shines on them. It also stretches like polyester when pulled. BASF was the main manufacturer of the tape, and not many U.S. manufacturers made PVC-based tape (Page 4 of the FACET Field Evaluation Toolkit has a list of brands of tape known to be PVC base). PVC is especially susceptible to plasticizer loss, so if there is suspicion that a tape is PVC, do not attempt playback in the Lab. 

2. **Sticky shed syndrome**: 
> **a. Sticky Shed Syndrome represents a significant preservation risk to polyester ¼” open reel tapes**. PVC, acetate, or paper tapes do not get sticky shed syndrome. **Tapes affected by sticky-shed cannot be played nor transferred in the IS Lab**. During playback, polyester polyurethane binder tape with this condition sticks together, leaving magnetic deposits on the tape deck. The tape will audibly squeal during playback. **Attempting playback with a tape affected by sticky-shed can lead to complete loss of the magnetic binder and the recording itself**. These deposits can also damage the playback heads. If at any point in the playback process, squealing is heard, playback should be stopped immediately, and Lab staff should be alerted.

> **b.** FACET developed an incomplete list of brands that have been observed to have sticky shed syndrome in almost all cases. **All of the following tapes must be baked before playback in the Lab:** 
> * **Ampex 406, 407, 456, 457** 
> * **Capitol Q15**
> * **Scotch 226, 227, 806, 807, 808, 809**
  
> **c. Exercise extreme caution with any non-major brand of polyester base tape. Major brands are considered to be any of the following:** 
> * **Afga** 
> * **Ampex/Quantegy** 
> * **AudioTape**
> * **BASF**
> * **EMI**
> * **Maxell**
> * **Orwo**
> * **Reeves**
> * **Soundcraft**
> * **Scotch**
> * **Sony**

> **d.** Tapes affected by sticky-shed syndrome usually have a black coating on the tape, which was added for superior sound quality. Apart from this, there is no way to visually determine if a tape is susceptible to sticky shed syndrome. Any other brand must be examined, baked, and played back carefully. Archivists and researchers agree that major tape brands are consistent, stable, and reliable. By contrast, non-major brands, which often varied in formulations and were poorer in quality, present risks to their preservation. For more information on identifying sticky-shed syndrome, please refer to [Appendix B](#appendix-b-identifying-vinegar-syndrome--sticky-shed-syndrome).

3. **Vinegar syndrome**:
* A type of deterioration that affects acetate-based audio tapes. Similar to the way in which vinegar syndrome affects acetate-based film, affected tapes will have a profuse vinegar-like smell. In severe cases, the tape can become brittle due to “hydrolysis,” a reaction of the binder of the tape with moisture in the air. Vinegar syndrome is not considered as significant as sticky shed syndrome or soft binder syndrome. However, **tapes with advanced stages of vinegar syndrome probably are too brittle to withstand playback and should not be used in the Lab**. 
* Please note: Contrary to film, AD test strips are not recommended for audio tape because they are not developed to detect the amount of acid in an affected audio tape. For more information on identifying vinegar syndrome, see [Appendix B](#appendix-b-identifying-vinegar-syndrome--sticky-shed-syndrome).

#### Cleaning ¼” Audio Tape Decks

![AudioTapeDeck](https://github.com/user-attachments/assets/fbf1bc7d-e6c8-49b7-8255-ec272dece970)

*¼” Audio Tape Deck*

¼” Audio Tape Decks need to be cleaned before and after each transfer. 

* Rollers **with** rubber are cleaned with **distilled water** and a foam cleaning swab. 
* Rollers **without** rubber and the **deck heads** are cleaned with **Isopropyl Alcohol** and a foam cleaning swab. 

(images/gifs will need to be added for the following, unsure if GitHub supports GIFS) 

![AudioTapeDeckHeads](https://github.com/user-attachments/assets/70925c02-ee65-43f2-a6e6-704b6f60bbf6)

*¼” Audio Tape Deck Heads*	

![CleaningTapeHeads](https://github.com/user-attachments/assets/c0656c46-b86f-48de-8cbd-03ef1d026696)

*Cleaning a Rubber Roller*
	
![Foam Cleaning Swabs](https://github.com/user-attachments/assets/c90c89dd-c059-4af1-95a8-4ecc73cefb0f)

*Foam Cleaning Swabs*

![Isopropyl](https://github.com/user-attachments/assets/6330fb71-4402-4238-99dc-7bbfccd163da)

*Isopropyl Alcohol*

![DistilledWater](https://github.com/user-attachments/assets/966a2506-6d3a-411c-a598-e0a82247845a)

*Distilled Water*

Tape wind issues (for ¼” open reel audio tape)
Poor tape winds can cause mechanical issues to the tape and playback deck. It’s important to identify tape pack issues and the damages they pose to equipment.


#### Adding leader (for ¼” audio tape) 
It’s important to add leader to any ¼” open reel tape without leader, or with deteriorated leader, to the head and tail of the tape. Splicing materials and leader are both located on the black rolling cart, in the box labeled “splicing materials.” Please [refer to this video tutorial](https://www.youtube.com/watch?v=LXx2nq6dmpg "Proper Splicing Technique") for proper splicing technique.

It’s important to not touch the dull side of the audio tape where the recording is encoded. It is advised that nitrile gloves are worn to make a splice.To perform a splice, please gather the following materials:
* Leader
* Razor blades
* Splicing tape 
* Splicing block 

1. Lay the tape end on the splicing block, with the matte side facing down. On audio tape, the magnetic information is on the matte side, so it is important to put splicing tape on the base side (shiny side). Splice tape with the shiny side facing up. 


![Analog Tape Splicing Example](https://tapeop.com/_m/photologue/photos/cache/TapeSpliceEdit01_display_hires.png)
[Analog Tape Splicing Example](https://tapeop.com/tutorials/11/intro-analog-tape-splicing-and-editing-and-tape-loops/ "Intro to Analog Tape Splicing")


2. Use the razor blade to cut the audio tape along the biased slot. Cut as close to the end of the tape as possible. 
3. Once the tape is cut, remove the tape from the block temporarily. Put the end of the leader on the splicing block and make a cut, using the same biased slot. Like audio tape, the leader has a matte side and shiny side. Ensure the shiny sides of both are facing up.
4. Join the two ends of the leader and tape together on the splicing block, shiny sides up. The two ends should match exactly. 
5. Using the razor blade, scrape the blue adhesive splicing tape off the roll. Cut off a 1-2 cm piece of tape using scissors. Keep the razor blade stuck to that side of the tape. Do not touch the sticky side.
6. Carefully use the razor blade to place the adhesive tape over the splice. The cut should be exactly in the middle of the tape. The adhesive tape should not extend over the edge of the tape and should have no air bubbles.
7. Once the blue tape is down, flip the splice over to check the work. No blue should be visible in between the leader and the tape.
8. Gently pinch tape on either side of the splice with an index finger and thumb. Twist in opposite directions to verify the splice strength.
9. When the splice looks good, unroll about a wingspan in length of leader from its reel, and cut with scissors.

#### Track Configuration and Tape Speed
 
Proceed once it is confirmed that tape does not have the following issues:
* Sticky-shed syndrome
* Vinegar syndrome
* Mold
* Dirt
* Mechanical or tape pack issues

#### Playback on the Otari MX 5050 (R2R 2)
1. Load the tape onto the deck on the left side of the machine. Ensure that the reel is completely and fully loaded into the hub.
2. Pull on the hub and twist to secure the reel safely on the hub. 
3. Refer to the diagram on the front of the machine for the threading pattern. Put a remote plastic reel on the takeup (right) side of the machine, unless one is already there.
4. Play the tape on the deck. Fast forward to a segment of the tape where sound has been recorded. Monitor the sound quality and speed with the checklist below:
* Note if the recording sounds too fast or too slow.
* Note if the recording seems to be playing forwards or backwards. 
* Using desktop stereo speakers or a pair of monitor headphones, listen carefully to the right and left channels. Alternatively, remove one cable from the patchbay to silence one channel and isolate the other. 
* WaveLab may be used to confirm that information is playing through both channels.
* **The Otari MX-50 cannot play quarter-track tapes**. It is a two track machine and can only play full-track or half-track tapes. For quarter track recordings, use the Otari MX-5050. The chart below shows the most common tape track configurations.
* Refer to the flowchart and diagram below to determine the track configuration. Always use a magnetic viewer to confirm the track configuration. 
* Magnetic viewers are weak magnets filled with fluid with metal particles used to discern the track configuration of audio tape recordings. The viewer sits in a plastic container on a sponge with water in the bottom of a container. The viewer should stay saturated with water so that the fluid in the viewer does not evaporate.
* Use below flowchart and diagram to figure out the track configuration of the tape.


![FACET](https://github.com/user-attachments/assets/d70ea42e-8db2-446f-9731-14fcfa50ef2a)

*From the FACET Field Guide Preservation Tool. Use the left column to identify the sound of a particular configuration. Use the center column to identify the corresponding configuration. Use the right column to make appropriate adjustments to the audio.*

![Track](https://github.com/user-attachments/assets/bf982014-387b-4256-8346-4829a1c363af)

*Variety of the most common track configurations.*

#### Playback Considerations
**For cassette Tapes**:
* Contact a member of Lab Staff to ensure that the deck is properly cleaned and [demagnetized](#appendix-i-demagnetizing-audio-playheads-lab-staff-only).
* Identify tape type and appropriate bias and EQ settings.
* Check recording tab status.
* Confirm Dolby NR type and availability of decoder.
* Verify correct loading of tape for desired playback side.
* Adjust azimuth if necessary.

**For quarter-inch Tapes**:
* Ensure deck is cleaned and demagnetized.
* Set EQ setting according to recording origin.
* Check for Dolby or DBX NR and decoder availability.
* Lock reels in place before playback.
* Identify recording speed and track configuration.
* Adjust azimuth if necessary. 

#### Mold and Dirt
Many formats are susceptible to fungal growth.
**Moldy tapes cannot be played back in the IS Media Lab**. Refer to images of moldy tape below:

![MoldyTape](https://github.com/user-attachments/assets/f118a809-9059-4fef-bce5-2db48ebd9911)
![MoldyTape2](https://github.com/user-attachments/assets/7ecbcf3d-b182-4f50-8cc0-4ef74534abb7)
![MoldyCassette2](https://github.com/user-attachments/assets/211add6c-2367-44dc-a28c-4467e76f45b5)
![MoldyCassette](https://github.com/user-attachments/assets/7066ee84-9839-46e3-8eae-1a43fceef2a3)

*Images of moldy audiotapes and moldy cassettes. 
Mold is visible as white, cloudy coagulations.*

If a tape is discovered to have mold after bringing into the IS Media Lab. Wipe down any surfaces the tape touched during the inspection and alert Lab staff. Moldy tapes should be cleaned professionally or away from the IS Media Lab where there is little chance for contamination of other media. 

Grooved media is also susceptible to mold growth. Some transcription discs and cylinders(an unsupported format) develop a type of plasticizer loss that is sometimes mistaken for mold due to its white color. Look for the spindly structures of mold growth as this plasticizer loss will look more powdery. 

![Plasticizer loss on a disc](https://psap.library.illinois.edu/assets/record-lacquer-plasticizer2-320-591684bca696322963594dd155c9b0cb8c85f1efea34108ce0ca314eab4c5e41.jpg)

[Plasticizer loss on a disc (from PSAP)](https://psap.library.illinois.edu/collection-id-guide/phonodisc. "Plasticizer loss on a disc")


#### Dirt 
Any format is susceptible to dirt and media with excess dirt should not be played back before cleaning. Vinyl Grooved discs may be cleaned with the record cleaner as detailed in the [Grooved Media Deterioration](#grooved-media-deterioration) section of this document. Shellac and transcription discs should only be cleaned by hand and dry cleaned. They should be wiped with a microfiber cloth in the direction of the grooves. With one hand holding the disc by the label in the center of the disc.  

CDs may be cleaned dry only with a microfiber towel by starting in the center of the disc and wiping in a circular pattern toward the edge.

#### Grooved Media Deterioration
**Shellac (78 rpm)**:
Shellac discs are a robust and relatively stable format. However, because of the variety in their composition, it is difficult to know for certain how shellac-based discs as a format will fare over time (Nguyen et al. 2011). Shellac discs become more brittle over time, particularly if stored without sufficient temperature and humidity controls (St. Laurent 1997). The organic cellulosic material present in most discs is susceptible to fungal growth, especially if conditions are humid or if the discs are exposed to water and not quickly dried. Exposure to water can also cause networks of fine cracks on the playback surface, a condition referred to as crazing.

* Dry clean shellac discs with microfiber cloth found in gray “Audio Maintenance” box by the turntable. 
* Use a magnifying glass or film loupe to inspect the surface of the disc. 
* If no cracks can be found in the shellac coating of the discs, it is possible to spot clean dirty areas of the discs with distilled water only (seen in image to the right). Spray water onto the cloth and gently rub the surface of the disc in the direction of the grooves. 

![DistilledWater](https://github.com/user-attachments/assets/06d29875-f7c2-4460-b7be-dad70ca1b7e5)

*Distilled Water*

**Vinyl (45 and 33 1/3 rpm)**:
Vinyl discs are the most stable physical sound recording format developed to date; they can last 100 years in a controlled environment. However, heat and ultraviolet radiation both degrade the polymer. Vinyl softens and flows when exposed to excessive heat, which deforms the grooves. Polyvinyl chloride (PVC) releases hydrogen chloride as it thermodegrades. Stabilizers added to the compound during production arrest this process, but excessive heat, ultraviolet radiation, and humidity accelerate the degradation and deplete the available stabilizers. Dust and foreign matter, such as oils from fingers, can cause distortion and surface noise in playback; these deposits can promote fungal growth and damage the playback surface. Water can combine with the “off-gassing” of hydrogen chloride to form hydrochloric acid in excessively hot conditions (St. Laurent 1997). Heat and pressure can also cause the discs to warp, which can adversely affect playback. Vinyl discs are relatively soft compared with shellac discs, and they are susceptible to mechanical damage, such as scratches. Consequently, they require much lighter downforce from the tonearm on a playback device than do shellac discs.

1. Cleaning vinyl at the IS Media Preservation Lab 

![KeithMonksMachine](https://github.com/user-attachments/assets/4c2373e7-7f7f-4334-97e4-8f26965831f0)
2. Turn on the Keith Monks record cleaner via the blue power button and place the record on the turntable (machine is located to the right of the Audio Transfer Station).      
* Use the 45 adapter ring as necessary


![45AdapterRing](https://github.com/user-attachments/assets/b8954c54-665a-457f-98f5-be81d9cb7f6d)

*Vinyl Record 45 Adapter Ring*

* Please refer to the Keith Monks record cleaning machine documentation for further information.
3. **Apply cleaning solution**: Push down on the brush and slide it over the record. Ensure that the brush makes contact with the record. The brush should be fairly saturated, as shown in the image below.
4. Turn the record knob to the “ON” setting to start rotating the record, press down on the cleaner dispenser button and let the cleaning solution cover the record with the brush. Take the brush off the record.

![KeithMonksBrush](https://github.com/user-attachments/assets/ad8d18c3-f8fe-4ba3-99ca-e73cf1b953b1)

*The attached brush sometimes doesn’t cover the entire record that well. If this is happening, 
loosen the knob on top of the brush (turn counterclockwise) to free it, and slide it on the metal rod 
toward the center of the record or out toward the edge. 


![KeithMonksControls](https://github.com/user-attachments/assets/78be73fc-0b9e-4b79-b2a0-f888df9e7803)

Controls for the Keith Monks Record Cleaner 
located on top in the front left corner of the device.


5. If cleaning a 45 disc, do not use the attached brush. Instead just use the bottled cleaning solution and hand held brush.
6. **Vacuum the record** by picking up the tone arm. **move it to the middle of the record**. Once the arm is lifted, the vacuum will automatically turn on. Let the vacuum catch on the grooves and let the record run until the tone arm has reached the end of the disc.
7. Repeat for the second side if needed and let dry for a few minutes in the drying rack before playing. 

![KeithMonksVacuum](https://github.com/user-attachments/assets/761cd47b-b09e-4d84-a76a-335aa0d4c5fd)

Start the vacuum “tone arm” in the middle grooves of the record and it will 
track the grooves backwards toward the outer edge of the record. 


![RecordDrying](https://github.com/user-attachments/assets/0e69f34d-7dcc-456c-97ad-43e757446a99)

Dry the record vertically on the light green drying rack 
before playback. Drying is approximately 5 minutes. 

**Lacquer Disc**:
* The recording layer of all lacquer discs is susceptible to loss of plasticizer, which produces palmitic and stearic acid. This causes the recording to flake, crack, and separate from the rigid base, and results in loss of playback capability. The soft surface is easily marred by needle drops, gouges, and scratches. During the World War II era, glass replaced aluminum as the base in lacquer discs. Glass instantaneous discs become brittle and are subject to cracks and breakage. Their inherent fragility increases over time as the glass becomes more brittle. Nitrocellulose is a flammable substance. Although the spontaneous combustion of a lacquer disc is virtually unheard of, a concentrated collection of nitrocellulose compressed media can cause a fire to burn more intensely. 
* Lacquer discs that are not flaking or de-plasticized may in certain cases be played back in the IS Media Preservation lab. Doing so will require research on what eq to apply on the preamp and correct stylus selection. **Talk to Lab Staff before attempting Lacquer or transcription disc playback in the IS Lab**.
> * Lacquer discs should be dry cleaned with microfiber cloth only. Do not clean if there is any sign of delamination. 

![Delamination](https://github.com/user-attachments/assets/ed357321-7162-47c7-b956-4174d8a37912)

Lacquer disc displaying serious delamination of the lacquer coating. The grooves where the audio information is stored was laid in this lacquer coating. When delamination occurs the risk to the recording is severe.


## Audio Rack Equipment

![Audio Rack Equipment](https://github.com/user-attachments/assets/11693e25-bf1b-4b61-b975-67117d83b3c8)
![AudioRackEquipment2](https://github.com/user-attachments/assets/73ad46ff-6dcd-40aa-87fe-64b702e723cb)
![AudioRackEquipment3](https://github.com/user-attachments/assets/84f184fc-35b1-4c26-ac01-d09949909832)
![AudioRackEquipment4](https://github.com/user-attachments/assets/c782e136-cb1f-43fc-a499-142c9eb211dd)

*In order from top to bottom*

Number | Deck Shorthand | Deck Make/Model | Supported Media Formats
:--- | :--- | :--- | :--- 
1 | CAS 1 **(NO rewinds)** | Nakamichi DRAGON 3 Head/Auto Reverse | Audio cassette
1 | CAS 2 (rewinds) | Teac W600-R | Audio cassette 
1 | CAS 3 **(NO rewinds)** | Nakamichi DRAGON 3 Head/Auto Reverse | Audio cassette
2 | MDS | Sony MDS-J330 | Minidisc
3 | PB | Audio Patch Bay | n/a
4 | RAD 1 | Radial Engineering J-RAK 4 4-Space Rack Adapter | n/a
5 | RAD 2 | Radial Engineering J-RAK 4 4-Space Rack Adapter | n/a
6 | PRS | PrismSound Dream ADA-8XR | n/a
7 | DBR | Dolby A-Type Model 361 | n/a
8 | DBL | Dolby A-Type Model 362 | n/a
9 | MCAS | Olympus Optical T100 | Microcassette
10 | OCS | Yeapook ADS1014D | n/a
11 | DAT 1 | Sony PCM-R500 | DAT / Digital audio tape
12 | DAT 2 | Panasonic SV-3800 | DAT / Digital audio tape
13 | R2R 1 | Otari MX-5050 | Open reel audio tape
14 | R2R 2 | Otari MX-50 | Open reel audio tape
15 | PHONO | Technics SL-1210MK2 | Vinyl record; 78 shellac; transcription disc; acetate disc
16 | TS^2 Dual Outputs Abrev. as TSFL and TSEQ. Refer to [Appendix E](#appendix-e-timestep-archival-pre-amp) for more info. | Time Step T-03EQ A+ |



## Turning on the Equipment

Turning on the Equipment
**Tip:** When transferring audio using this rack, it can be beneficial to have the audio (cassette or vinyl) playing before turning on WaveLab. Sometimes the signal will not go through to WaveLab if there is not something already playing.

![TurningOnEquipment](https://github.com/user-attachments/assets/b1df44ec-250c-4e74-8713-29b599ab861d)
![TurningOnEquipment2](https://github.com/user-attachments/assets/b1d81044-f9c9-4007-99c8-44fcdc615385)

1. Turn on the **Audio Transfer Station Computer** by pressing the power button on the tower.
2. **Turn on the power supply** for the Audio Rack and Speakers. Find the little red buttons within a plastic flap, located on the left of the CyberPower deck, and on the right of the Tripp-Lite deck.
3. **Turn on the Prism**, located above the power supply, which transforms the analog audio signal into a digital signal. Power button is located on the upper left.
4. Select the appropriate deck and turn it on:
   > a. **Cassette:**
	Power buttons for the Dragons are in the upper left corners; Power button for the Teac is on the lower left.
   >
   > b. **Microcassette:**
	Power button for the Olympus is located on the bottom left corner of the machine.
   >
   > c. **Minidisc:**
	Power button for the Sony is located on the upper left corner of the machine.
   >
   > d. **DAT:** Power buttons for the Sony and the Panasonic are located on the upper left corners of both machines.
   >
   > e. **Vinyl:** To turn on the record player, locate the power button at the top of the GE power strip on the floor, underneath and to 	the left of the record player table. Make sure the strip is turned on (the button will glow blue).
5. Once the audio rack and desktop are powered, please refer to [WaveLab 11 workflow](#wavelab-11-pro-workflow).



### Setting the Signal Path on the Prism
This section:
* Defines the terms ‘audio signal’ and ‘audio signal flow.’
* Explains the relationship between the audio playback decks, the Audio Patch Bay, and the Prism, and how it facilitates the transfer process.
* Introduces the four panels on the Prism, their functions, and what kind of information each one provides about an audio signal.
* Explains how to configure the settings on the Prism and on the Audio Patch Bay. This ensures the audio signal flows smoothly from the chosen deck to the Prism.

**What is an audio signal?**
An audio signal is a representation of sound, typically using either a changing level of electrical voltage for analog signals, or a series of binary numbers for digital signals. These are both forms of audio information.

**What is an audio signal flow?**
The audio signal flow is the path an audio signal travels, from its source to a specific output. It can be thought of as a chain of many devices, which are connected together in a pathway from playback to output.

**Audio Rack Signal Flow Chart:**The signal flow chart on the following page shows the sequence of devices connected in the signal flow, and the function which each device performs during the transfer process.
* The orange rectangles represent the **playback decks**, which read and play the audio recording.
* The blue rectangles represent the **space extenders**, which maximize the amount of available space on the audio rack.
* The green rectangle represents the **Audio Patch Bay**, the central hub that connects the sound source to hardware and software programs which monitor, transform, edit, and save audio signals.
* The red rectangle represents the **Prism**, which converts the analog signal into a digital signal.

![IS Library Audio Rack Signal Flow Chart](https://github.com/user-attachments/assets/1b8ccdbc-71bf-4a8e-b89a-bb3951c4426a)

*Audio Rack signal flow chart*


#### About the Prism ADA-8XR
This device transforms an analog audio signal into a digital signal. It also enables the creation of large systems with multiple audio channels. Due to its sophistication and complexity, learning to use the Prism can be challenging, and requires patience. Please follow the steps in this section carefully and treat it as a technical companion to the Prism.

**The front panel of the Prism ADA-8XR contains four divided panels, which are responsible for the following functions:**

![AudioRackPrism](https://github.com/user-attachments/assets/3fd49c7d-ba1a-4331-9b61-6b5fa79f7be7)

* **Montior Panel:** Controls and displays all parameters of the two-channel Monitor.
* **Mimic Panel:** Displays the flow of signals through the Prism.
* **Meter Panel:** Contains eight LED bar graphs used to control selected channels.
* **Menu Panel:** Manages parametic adjustments. On the bottom are the Configuration/Stores buttons.

#### Configuring the Audio Patch Bay
1. For DAT, reel to reel, and minicasette decks, the signal runs to the Prism via the audio patchbay (PB). To route the signal to the Prism, the ¼” cables should be plugged into the output 24 labeled “To PRS.” Ensure the signal is routed properly by using both ¼” cables, one for each channel on the patchbay. The table below is a key that shows how the left and right channels of different decks in the audio rack are assigned to corresponding channels in the prism. It distinguishes between Path 1 inputs and Path 2 inputs.

***Path 1 Inputs*** | 1: Patchbay (Left) | 2: Patchbay (Right) | 3: CAS 1 (L) | 4: CAS 1 (R) | 5: CAS 2 (L) | 6: CAS 2 (R) | 7: CAS 3 (L) | 8: CAS 3 (R) 
:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: 
***Path 2 Inputs*** | **1: TSFL (Left)** | **2: TSFL (Right)** | **3: TSEQ (L)** | **4: TSEQ (R)** | **5: MDS (L)** | **6: MDS (R)** | **7: Empty** | **8: Empty** 


2. Please ensure that the media is actively playing back in the selected deck PRIOR to opening the WaveLab application. This step will ensure that WaveLab recognizes the audio signal upon opening the application.

![Path1](https://github.com/user-attachments/assets/f77314cb-83f0-455a-a492-05d5fd546d15)


3. Refer to the Menu Panel located on the far right side of the Prism. Press the small square button labeled “Bank,” then the button for “1” or “2,” depending on the desired path. The display will read  “Path 1/2 Template [Store4.1] Load?” Press the circular button labeled “Enter/Accept.” The Prism will respond with an audible click to confirm the selected path has been set.
	*As shown in the images below, the Meter and Mimic Panels will display the path for which they are set. Pay attention to this 		information when setting levels and cueing a particular channel.

![MonitorPanel](https://github.com/user-attachments/assets/881146fb-d684-4b20-992e-527d2042b4fd)

*The Monitor Panel. 
Circled are the options for Path 1 and 2.*

![MimicPanel](https://github.com/user-attachments/assets/b68773b7-0430-45c0-9e45-d1be91b297f8)

*The Mimic Panel. 
Circled are two signal pathways.*

![AudioPatchBay](https://github.com/user-attachments/assets/f55ddbcf-e9ca-47c4-87a4-376227b0f2ae)

*The two circled configurations on the Audio Patch Bay remain fixed for all circumstances.*


## Digitization

### WaveLab Overview
WaveLab Pro 11 is a professional-level digital audio workstation (DAW) used for audio transfers. It can be accessed via the desktop computers at the Audio Transfer Station and the Audio Editing Station. This software interfaces with the Audio Transfer Station Computer’s sound cards and the Prism converter, to capture recordings being played on the audio decks. Once captured, the audio recording can be digitized, edited, and remastered with a robust suite of functions. Due to the program’s complexity and sophistication, it can be difficult to learn and navigate, and thus requires patience. For first-time users, please refer to WaveLab’s [YouTube playlist of tutorial videos](https://www.youtube.com/watch?v=bC0MYgNXXjE&list=PLKgGKF-FSsJ_OAlNnzTLMKK_CWAM1cXhb&pp=iAQB "Wavelab Tutorials") as a technical companion while learning to use the software.

### WaveLab 11 Pro Workflow


#### Opening WaveLab 11
1. Open WaveLab Pro 11 on the desktop at the Audio Transfer Station. 
2. In the first window that pops up, click “Audio File” and then “Create Empty”.  
3. The main window will open. Create an empty document using the icon on the lower third of the page on the right side of the window.

![WaveLabMainWindow](https://github.com/user-attachments/assets/9e8fafb2-782e-44db-8263-23fe668a32ee)

The main window of WaveLab will appear once the application is opened.

![WaveLab2](https://github.com/user-attachments/assets/6b578167-8d82-451d-a90a-13af3ecf405b)

Click the Square-Plus icon to create a new project.

4. In the Properties window (seen on next page), set the empty document with the following specifications: 
> a. Stereo track configuration
> 
> b. 96kHz
> 
> c. 24 bit depth

5. Once these settings have been selected, click “create.”

![WaveLab3](https://github.com/user-attachments/assets/1458f4da-4e31-4917-8b6a-c86f33f104c4)

*Properties should be set to match the Prism settings (96kHz; 24 bit).*

![WaveLab4](https://github.com/user-attachments/assets/15e90c40-1012-4cb9-974c-5117f8ed2630)

*Monitoring microphone icon highlighted in red.*

6. Click the arrow next to the monitoring microphone icon. Set the input and sample rate to 96000Hz (the same sample rate set on the Prism). This enables the program to monitor the audio signal. **Please note**: WaveLab defaults to 44100 Hz, so **double check** that the program is set to **96000 Hz**.

![WaveLab5](https://github.com/user-attachments/assets/cc3aa961-ff04-4743-836d-2743e468a1dd)

7. **Set monitoring input**: In the menu under the little microphone, set the input that is being used. In the above photo WaveLab is set to monitor PB or Audio Patchbay.

8. **Turn monitoring on**: click the red microphone button to illuminate it.  

	* Sound should be heard from the speakers if the speakers and the PreSonus monitoring station are on.
	* If audio is still not heard, WaveLab may need to be restarted and steps 1,2, and 3 need to be repeated in that exact order. **Do 	not click the microphone** until the sample rate and input have been set.

![WaveLab6](https://github.com/user-attachments/assets/5083a364-64bd-4c29-98da-78652d83c5e4)

*The monitoring station and speakers are powered by the red switches in the rack. The volume knob is illuminated in blue when the speakers are on. Power switch for the speakers is located on the back.*

![WaveLab7](https://github.com/user-attachments/assets/e7a81d77-7309-42a5-a40b-7f6ee754cd10)

*Ensure that the following buttons on the Presonus monitoring station are illuminated: ST1 (Hdphs.); ST1 (Spkrs.); ST2; and AUX.*

9. **Set audio levels**: Observe the level meter in WaveLab. Look at the numerical values at the right end of the bars. These peaks should average between -6 and -3dB. If not, the levels need to be adjusted using the Prism. While the levels do not always have to fall exactly within the range of -6dB and -3dB, as a general guideline, **the peaks should never surpass 0dB in WaveLab**. This is to prevent clipping, or the loss of audio information when the signal is too high.
> b. To change levels on the Prism, press “source” on the prism (far left bottom corner). Press source until the following is visible: **“AI1 Lin: +(xx).0dBu.”**

![WaveLab8](https://github.com/user-attachments/assets/65b3dc7b-270a-4c8a-af04-9709b889ebdd)

*The source button is circled in yellow.*

![WaveLab9](https://github.com/user-attachments/assets/97e95b6c-e467-47de-9d98-41a93c637e0c)

*The screen where channel levels can be adjusted. The number in the top right corner represents the setting adjusted with the “select/change” button. The number in the lower left corner represents the live peaks of the signal.*

> c. If the signal is passing through the Prism, it will be visible on the Meter Panel (refer to [Setting the Signal Path on the Prism](#setting-the-signal-path-on-the-prism). The two illuminated bars on the Meter Panel illustrate the peaks of the left and right channels, respectively.

10. Select one of the channels and use the “Select/Change” buttons to set the volume. Ideally, peaks will fall between -6 to -3dB range. To avoid clipping, **avoid going above -3dB and do not surpass 0dB**. This is to prevent the loss of audio information from the signal being too high. Observe the signal in WaveLab while making adjustments to the levels, as its interface is the easiest to read. **Please note** that the Prism is limiting the signal for digitization, which means that **the lower the number, the louder the signal, and the higher the number, the lower the volume level**.

11. Once the correct level has been set for one side of the channel, select the second channel, then use the “Select/Change” arrows to match the dBu (decibel unit) for the two channels. The dBu needs to match with both channels to accurately reflect how the recording was made.

![Wavelab11](https://github.com/user-attachments/assets/5258a67d-6e7a-48e5-8ed3-0cd67a6332f1)

*On the Menu Panel, two bars of light represent the two channels receiving the signal from the playback deck. Channel 5 is the left channel; Channel 6 is the right. Limiter is set to +14.0dBu.*

![Wavelab10](https://github.com/user-attachments/assets/007ec23c-046a-48d5-891b-cf43bb0638dd)

*Level should also be set to +14.0dBu in channel 6, the right side of the channel pair.*

> d. Monitor a substantial enough portion of the recording to ensure that the volume does not change dramatically over its course.
> 
> e. If the levels have remained well-balanced over the course of the monitoring, it is time to begin the digitization process. **Please ensure that the tape is running before commencing the digitization instructions that follow.**

#### Perform a 10-second test capture

1. By this point, the audio levels should have been accurately set on the Prism. **Please note: the tape should be actively playing on the chosen deck prior to opening the application.** This step ensures that the program will be able detect the audio recording as soon as it is opened.
2. At the bottom of the program, select the ‘Record’ button (circled below).

![Wavelab12](https://github.com/user-attachments/assets/2ec24a86-2f83-4103-930b-4341a7d6abcc)

*The record button in WaveLab.*

3. A new window labeled ‘Recording’ will appear. Ensure that the input selected is correct (the input may need to be changed, as it does not automatically match the input used to monitor the sound earlier).

![Wavelab13](https://github.com/user-attachments/assets/6b6e90db-6ae1-4489-8158-759c683e6ef3)

*Select Audio Monitoring to observe the levels in real time.*


4. **Check the box for “audio monitoring.” Uncheck the red microphone icon, which was used for monitoring earlier.** This step prevents the sound from echoing as it is played back.

![Wavelab14](https://github.com/user-attachments/assets/2643f222-32a7-4560-b26b-b8c7513e9944)

*Microphone icon in the “off” position.*

5. Press ‘Record’ to perform a 10-second capture. The window will change to a red color while recording. Press the ‘Stop’ button or ‘Record’ button when finished recording. 

![WaveLab15](https://github.com/user-attachments/assets/8a90edf0-8132-4a1a-89a7-f96fa6a6d29c)

*View of recording window when recording is in progress. Audio monitoring is checked.*

6. A waveform should appear in the window. Play it back by pressing the play button (the green, rectangular button shown below).

![WaveLab16](https://github.com/user-attachments/assets/91a15217-8a9b-403f-b657-ff2104341d3a)

*Playback button in WaveLab*

7. Ensure the quality of the playback audio is satisfactory. Once the quality of the audio has been verified, it is time to begin the capture.
8. Rewind on the playback deck. If using cassette, rewind in CAS 2. 

#### Record

1. At the bottom of the project window, press the square ‘Record’ icon.
2. In the recording window that comes up, **confirm the input is correct** and check the audio monitoring box. Likewise, **confirm the file location is set to the project folder, then choose a name for the file.**
3. To start the recording, cue the media, then press ‘Record’ in the WaveLab window. Start playing the media on the appropriate deck. Monitor the recording levels during playback.
4. Once the playback has finished and to end the recording, press “Stop” or “Record.” **Playback the recording in WaveLab to confirm it sounds correct. It is recommended to export a Preservation Master, an Access Master, and a Listening Copy at this time.**

### Post-Digitization

*This section will cover actions undertaken with digitized files. This includes exporting of derivative files from the preservation master in WaveLab. It will also cover light editing tools needed to trim silence at the beginning or end of recording for listening copies. It will also detail how to use Wavelab to duplicate and route recording to different channels to aid the intelligibility of listening copies. It will also explain how to use Audacity to speed up or slow down recordings to a desired speed. This may be helpful for discs recorded at unconventional speeds or for ¼ open reel recordings recorded at speeds not supported by lab equipment (i.e. 1 ⅞ ips). Finally, this section will also give instructions on how to perform some light restorations to aid intelligibility of listening copies using WaveLab’s RestoreRig tools. As a general rule its important to understand that your raw transfer is a preservation master that should not be touched. None of these post-digitization actions should be taken on the preservation master. Even trimming of silence at the beginning or end of the recording should not be done to the preservation master. The first section describes how to export derivative copies and access master and listening copies should be used for, channel reconfigurations, speed changes and light restoration work.*

#### Exporting Derivative Files in WaveLab Pro 11

##### Export Preservation Master

1. Once the source has been captured, export the Preservation Master and the Access Master to the scratch folder. **Please note: there should be no editing or restoration done to the Preservation Master.**
2. Export the file with the bit rate and sample rate set to the archival standard: 96 kHz + 24 bit.
3. Go to **File>Export** and give the project a name. e.g. Artist_Track tile_96kHz24bit_PreservationMaster.wav (this must match the file name entered in the recording window)
4. **Confirm the location** is set to the project folder in the server created in Step 7.3. 
5. Click the Format presets button, circled in the image below, and select the following option: Wav_PreservationMaster_24bit96hz.

![PostDig1](https://github.com/user-attachments/assets/6f345601-2e6e-4933-bd3d-a5f2a2f68670)

*Format presets button circled in yellow.*

![PostDig2](https://github.com/user-attachments/assets/1e4abdc5-ecaf-4455-9250-878d7f9ae8c1)

*Dropdown menu of options for Format presets.*

6. Press “Start.” The export should occur within a few seconds.

#### Export Access Master 

1. After the 96kHz24bit Preservation Master has been exported, export the Access Master at the same 96kHz 24bit archival settings.  
Follow the instructions below, please do not export through the render tab. 
2. Go to File, then Export, and give the file a name that differentiates it as an Access Master. E.g. Artist_Track tile_96kHz24bit_AccessMaster.wav

![AccessMaster1](https://github.com/user-attachments/assets/650b0efc-ef5a-4df9-bc48-de1dd2ac9b4e)

*For Access Master files, 24 bit 96 Hz is the recommended preset.*

3. Set sample rate to 96 kHz and the bit rate to 24 bit (or select the Access Master Template).
4. Press Start.
5. Open the Scratch Files folder and confirm the Preservation Master and the Access Master are both present. 
6. Open them in a separate application, such as VLC Media Player, to confirm that the audio plays back.
7. Close WaveLab. For further edits and applying restoration tools to a listening copy, close WaveLab, navigate to the project folder, and perform edits on the access master copy exported.

#### Adjusting Channel Configurations (Creating Dual Mono Outputs)

For quarter-inch open reel recordings, recordings may be transferred with single channel  mono tracks that may be duplicated to create a stereo-sounding dual mono recordings. 

1. Open an Access Master Copy of a recording or create an empty project in Wavelab. In the file group options create an “audio montage”. This allows multiple “tracks” of audio to be manipulated simultaneously.

![Channel1](https://github.com/user-attachments/assets/80a64a8b-abee-47da-bbdf-e95f59db5c23)

*Audio montage selection NOT “Audio File” as would be selected normally.*

2. This will create an empty audio montage. Right-click and use the Insert File command to browse for the wav file you want to import, or copy and paste from the access master file in the other tab. (If you have a file open in an Audio File tab, you can also simply Select All in your Audio File timeline then copy and paste that file into your open Audio Montage tab.)

![Channel2](https://github.com/user-attachments/assets/c5336253-40e6-46f1-9fc0-fd7d67462d8d)

*Can select “Insert Audio Files” and open access master file or can copy and paste or simply drag from another file “tab” open in wavelab.*

3. With the recording displayed in the timeline, right-click in the Control Track area to the left of the timeline, then select the option to “Split Channels into L/R Mono.”

![Channel3](https://github.com/user-attachments/assets/da5a0533-f7d7-4109-abb6-37be5d609b33)

*Right-clicking in the Control Track area produces this menu.*

![Channel4](https://github.com/user-attachments/assets/f77106b5-e038-4f91-a34a-195e9a9a4245)

*Zoomed screenshot of the “split channels” button.*

4. From here, delete any blank channels and replace it with the “Duplicate Track” function, located above “Split Channels” when right-clicked.

![Channel5](https://github.com/user-attachments/assets/faee149e-9606-42a9-970f-5fe7672b0827)

*Two “tracks” which will be treated as separate channels for the dual mono listening copy.*

5. Finally, assign the new track to a separate stereo channel. Right click again in the Control Track area previously to select “Duplicate Track”, and after selecting Input Bus (see photo), then click “Track Routing.” If the original transfer was left channel only, keep that assigned to the left channel, then assign the duplicate track to the right channel.

![Channel6](https://github.com/user-attachments/assets/343f6f22-330b-488a-8d57-9f01663224de)

*Select “Track Routing” in the “Input Bus” menu.*

![Channel7](https://github.com/user-attachments/assets/782c2f41-02d7-4319-a427-e76146c2523d)

*The “track routing options”. Ensure one of the channels is routed to right and the other to left.*

6. Playback the file to ensure that the mono tracks are playing simultaneously in each channel.

#### Modifying the Speed of an Audio Recording

*This section describes the use of Audacity, a free, open-source digital audio workstation (DAW) that may be used to change the speed of a recording.  Audacity is installed on the Audio Transfer Station and Audio Editing Station.*

##### Setting up Audacity
1. Navigate to the location of the access file with an improper speed and right click. Select “Open With” and  “Audacity.”

![Audacity1](https://github.com/user-attachments/assets/70f272a8-7ea9-4cc1-a1a9-cc225f147486)

*“Open with”< “Audacity”*

2. The file should open in Audacity and the waveform of the recording will be visible in the main window.

![Audacity2](https://github.com/user-attachments/assets/fab6e9c6-a0b5-4897-9f3a-f97c19ff72c2)

*The main window in audacity. Note that the signal is only in the right channel. This recording was a single mono track of a quarter track mono tape.*


3. Split the recording into stereo tracks that may be routed to either channel. Navigate to the right side of the window in the “track control area” of the track. This will be similar to the [adjusting channel configuration](#adjusting-channel-configurations-creating-dual-mono-outputs) part of this document.
4. Click the arrow in the area where the name of the recording is displayed. In the drop down menu select “Split Stereo track”

![Audacity3](https://github.com/user-attachments/assets/b30b2f63-b581-4bd2-aab9-dd07e39d8268)

*“Split Stereo Track”*

![Audacity4](https://github.com/user-attachments/assets/b24d3ec0-2276-4dbf-9ce8-03b23433e1b7)

*This action created two separate stereo tracks. Audacity should have routed each track to either the right or left. This can be verified in the track control window in the slider that goes between “L” and “R”. The blue dot reflects the extent to which the track is routed to the right or left side (underlined in red).*

5. Now there are two stereo tracks. One of the tracks should be filled with the recording but it is effectively blank. “Click” on the empty track and delete the information. 
6. Click on the other track where the recording is to highlight it and copy and paste it into the other track area.
   > a. When pasting, make sure the play head is set to 00:00:00 to ensure the two tracks are timed correctly.

![Audacity5](https://github.com/user-attachments/assets/7e74b816-087c-4ce2-bac6-a4d856fb5fc5)

*The circle is meant to indicate that the track has been highlighted in light blue. Press “Backspace” on the keyboard.* 

![Audacity6](https://github.com/user-attachments/assets/ee3448ad-3b76-49cc-8c41-b4c78e58300c)

*After copying and pasting the recording from the right channel to the left channel.*
   
7. At this point there should be a stereo pair of tracks routed to either side. Press “Play” to ensure the tracks are synced. 

![Audacity7](https://github.com/user-attachments/assets/30174f73-06f8-42c6-872f-d475b8256553)

*Play button.*

8. Now its time to change the speed of the recordings. Highlight both of the tracks. 
9. Go to the top menu and select “Effect.” In the long drop down menu select “Change Speed.” 

![Audacity8](https://github.com/user-attachments/assets/95dcff1c-f442-4142-945c-43dbe2d03f26)

*Both tracks highlighted. The tracks must be highlighted for the effect to know which audio should be changed.* 

![Audacity9](https://github.com/user-attachments/assets/bd78cbac-450f-4716-a85f-74bbea175500)

*The location of the “Effect” button.* 

![Audacity12](https://github.com/user-attachments/assets/4e4f9c75-93bc-42da-80d4-ac7f3a39e5ee)

*“Change speed.”*

10. The change speed menu will open. Select the desired percentage change for the recording. Click “Ok.”

![Audacity13](https://github.com/user-attachments/assets/4daaa7b1-655f-440e-9906-554a2fb0d893)

*This recording was a tape recorded at 1 ⅞” ips but it was played back 3.75 ips.*

![Audacity14](https://github.com/user-attachments/assets/eac444c5-c25b-497b-a9c9-055f5ca8499a)

*This is the screen that explains that it is working. This could take a while depending on the length/sample.*

11. When it is done, playback the track in Audacity to ensure nothing has gone wrong in this process.
12. “Export” with desired specs. Go to “File” and “Export.” 

#### WaveLab RestoreRig (restoration tools) workflow

RestoreRig has three main tools: the **DeClicker**, **DeNoiser**, and **DeBuzzer**:
	* **DeClicker** lets you remove clicks, pops, and crackles associated with grooved media recordings, as well as noise from splices in tape recordings.
	* **DeBuzzer** is for removing buzz or hum at fixed frequencies (such as 60Hz ground hum, extending up through 440 Hz).
	* **DeNoiser** removes noise from recordings, such as tape hiss or line noise. This also includes fixed sources of “static” noise and “dynamic” noise, whose characteristics change slightly over time. 

1. **Headphones**: To use Wavelab’s restoration tools, monitor the audio using the Sennheiser or AKG studio headphones in the IS Lab. Plug headphones into the jack on the Presonus Monitoring station.

2. Set WaveLab as the source when monitoring on the Audio Transfer desktop computer.
> a. Select “ST1” on the Presonus monitor controller box, located on the Audio Transfer Station table. Multiple sets of headphones may be plugged in, using the bank of quarter-inch headphone jacks that runs across the top of the audio controller.

3. **Open the Access Master file. As a reminder, restoration and editing tools should only be applied to the Access Master file, whereas the Preservation Master file should remain as is.**
> a. Right-click on the Access Master wav file, then navigate to **“Open with…” > “Wavelab.”**

4. Set WaveLab view to show “spectrograms” to diagnose noise in the recording. For more information on spectrograms and how to view them in WaveLab,[see Appendix D](#appendix-d-reading-spectrograms-in-wavelab).

![Restore1](https://github.com/user-attachments/assets/89c798c4-fdf6-4d2c-b69b-892fac43ff70)

*View project as a spectrogram by hitting the “spectrogram” button in the bottom left 
corner of the WaveLab window. Note: WaveLab is normally set at “Waveform.”*


5. Enable the RestoreRig plugin, located in the Master Section of the WaveLab window. 	
> a. The Master Section houses all effects plugins in WaveLab. Before they may be used, the Master Section must first be enabled. **Please note: these tools should not be activated when capturing audio recordings, as the effect will be applied to the effect as the recording happens.**
> 
> b. Turn on the master section by pressing the power button and turning the icon green.
> 
> c. Navigate to the bottom of the program to find the RestoreRig plugin label and ensure it is also enabled. Its bypass button should be green rather than brown, indicating  that the effect is on and working. 

![Restore2](https://github.com/user-attachments/assets/578cda6b-fd9a-498b-a1a4-4baca61493b6)

*View of “Master Section” of WaveLab with all effects “on”.*  

![Restore3](https://github.com/user-attachments/assets/1d48782d-7156-46ad-9630-48714cf53ec7)

*If the effects bypass button is brown, it has been bypassed and RestoreRig effects will not be applied. Pay attention to the Master Power button and the effect bypass button when using RestoreRig as both of these icons must be illuminated green to use RestorRig effects.* 

6. Click on the word “RestoreRig” in the Master Section to open its control window.

![Restore4](https://github.com/user-attachments/assets/e654859f-9325-410a-b96f-a0398cacf7c7)

*This is the RestoRig window that will open over the top of the main WaveLab window.*

7. Activate tools in RestoreRig. Press the power icon in the top left corner of each tool area to turn on the tool.

![Restore5](https://github.com/user-attachments/assets/461455ec-3313-4079-a35a-4b8f916383e7)

*Within this window each of the tools can be activated and deactivated. If the tool is grayed out, then it is inactive.* 

8. The intensity of the DeClicker and DeNoise effects can be adjusted from 0% to 100%. The DeBuzzer targets a specific frequency which can be set in the control window. The intensity of the noise cancellation can also be adjusted via “level” control (squelching it 0 decibels, i.e., not at all, all the way up to -96 dbu). The sensitivity controls how much that effect extends into surrounding frequencies. Broader band noise may be targeted with lower sensitivity DeBuzzer.
9. DeNoiser requires a portion of the recording to be selected, to determine the “noise” to remove. Highlight a quiet passage in the recording (where the spectrogram is the most empty) then click the “Learn” button to build a noise profile. Leaving a moment of dead space at the start of your tape or disc transfer is recommended when building a noise reference 
> a. Select the correct type of audio recording in DeNoiser so it can apply a specific algorithm intended for the specific type and content of recording (e.g. spoken word, song, etc.).

![Restore6](https://github.com/user-attachments/assets/7e0a5300-c45d-4dc6-8576-7bb2955c928a)

*Select an algorithm for WaveLab to apply to the recording from the dropdown menu.*

10. To hear the effect applied to the recording, ensure that its associated loudspeaker icon is white rather than blue.
11. If the loudspeaker icon is blue, simply click it to turn it white again.

![Restore7](https://github.com/user-attachments/assets/5e2fbe72-9057-44a9-b0f2-44dc32746ef8)

*Declicker effect with Noise Listening Mode On.*

12. Highlight a segment of the timeline for which the effect will be applied. Use the spectrogram view to find clicks, pops, and noise in your recording, and to see the affected frequency ranges and intensities.

![Restore8](https://github.com/user-attachments/assets/dc11b982-f5c9-4999-8a83-a43507c2f725)

*Noise or clicks in the [spectrogram](https://www.izotope.com/en/learn/understanding-spectrograms.html "Understanding Spectograms") will look like vertical lines as seen above.*

13. The RestoreRig window creates a visualization of the pre-effect signal (labeled “Input Signal,” in red) against the signal with effects applied (labeled “Output Signal,” in blue).

![Restore9](https://github.com/user-attachments/assets/5b05bf8e-6aa3-4c22-bf93-12608d7cdeca)

*In this example a fairly aggressive DeNoising is applied, which has wiped out frequencies above about 8kHz. This will also be visible on the resulting spectrogram, after rendering.*

14. Click on the small “FX” icon in the top left hand of the RestoreRig (Listen to Effect Only) to hear only the affected portion of the signal. If too much of the desired signal is heard, it is possible that excessive noise reduction has been applied. As long as this FX icon is blue, only the portion of the signal being affected by the NR tools will be audible. At this stage, WaveLab is only previewing the effect; it has not been applied to the recording. 
15. Once the noise has been targeted effectively, highlight the portion of the track to select it for noise canceling. Click the “Render In Place” button in “RestoreRig,” or alternatively, apply the effect to the entire recording through the render tab of the main window.

![Restore10](https://github.com/user-attachments/assets/4cb7e6b1-0661-42b4-91e6-7bcf74ca4ac2)

*“Render in Place” icon in RestoreRig.*

![Restore11](https://github.com/user-attachments/assets/842d5ace-bc03-4db8-a249-65c627d7f6ce)

*The “Render tab” in the main window which allows you to render whole or part of the file or to create a new rendered file with the effect applied.* 

![Restore12](https://github.com/user-attachments/assets/fdb3bafd-ebd6-4ef4-8f74-d4050a15822d)

*Pre-effect signal*

![Restore13](https://github.com/user-attachments/assets/9a716707-a69b-49f4-a503-c0f71959a9ce)

*Post-effect signal*

16. **Please note: after rendering, click the power button to turn off the effect in RestoreRig. Otherwise, the effect will be applied again to the rendered file.**
17. Once effects have been rendered, examine the spectrogram closely. Listen to the recording in the timeline to see the results of the restoration tools. If playback is satisfactory, save changes to the Access Master copy.
18. Export an additional, lower-quality Listening Copy using WaveLab’s 16bit/48kHz Listening copy Preset.

![Restore14](https://github.com/user-attachments/assets/cb1ea960-7c3f-434a-92e2-635bfce142ff)


### Powering down the audio rack 

This documentation outlines the steps required to properly power down the audio rack. Proper shutdown procedures are essential to prevent damage to equipment. **Please turn off all equipment before leaving the lab–including the lab computer in use.**

**After completing the audio transfer:**
1. Close Wavelab.
2. Turn off the audio deck in use (cassette, vinyl, DAT, etc.).
3. Turn off the Prism, located above the power supply, which transforms the analog audio signal into a digital signal. Power button is located on the upper left.
4. Turn off the power supply for the Audio Rack and Speakers. Find the little red buttons underneath a plastic flap, located on the left of the CyberPower deck, and on the right of the Tripp-Lite deck.
5. Turn off the Audio Transfer Station Computer by pressing the power button on the tower.

## Metadata Capture

Metadata can be extremely beneficial in documenting details about the files (track title, author, date, location). Care must be taken to avoid ambiguity about which object is being described in the metadata; it is necessary to describe the work, its original manifestation, and subsequent digital versions. **It is critical to be able to distinguish what is being described in each instance.** The IS Media Lab has spreadsheet templates for [PBCore](https://docs.google.com/spreadsheets/d/1P0-8B6YXb2r5OKkiYj2VNwV9yf-3c0-fdGql0h2jGK8/edit#gid=226473954 "PBCore Template"), [general AV metadata](https://docs.google.com/spreadsheets/d/1EJ1VIpf-ytQOY_76WCxX_FNiTbZjas2SZ6TnUGyrUwE/edit#gid=0 "AV Metadata"), and Dublin Core. Select one of these schemas to fill out while listening to the track. 


### A Note on Metadata Entry

When filling out a metadata template, ensure that each cell is devoted to **one piece of information**. This can change depending on the document (e.g. one document has first and last name contained in the same cell; another document separates this data). Separating data into specific categories can help when changing data from one system to another.

### PB Core

The IS Media Lab recommends PB Core as the metadata schema of choice for describing digitized audio files. PB Core is a cataloging standard for the description of audiovisual content, a data sharing tool, a controlled vocabulary, and much more. It was developed in the 2000s by public broadcasters in the United States, in order to more effectively share, manage, and preserve media among different organizations and individuals. Visit the [PBCore site](https://pbcore.org/what-is-pbcore "What Is PBCore") to learn more about PBCore’s uses and applications.

### Dublin Core

Dublin Core is a set of fifteen generic, widely used elements first drafted at a 1995 meeting in Dublin, Ohio, to facilitate information discovery on an explosively growing Web. A diverse community of librarians, technologists, and researchers rallied to the idea of achieving rough interoperability across languages and disciplines through a core of shared semantics. Visit the Dublin Core site to learn more about Dublin Core’s uses and applications. Below is a metadata template for Dublin Core, which can be copied and pasted into a separate program or document for data entry.   

DC Element | DC Definition | Audiovisual Interpretation
:---: | :---: | :---: 
**Title** | A name given to the resource | The main title associated with the recording
**Subject** | The topic of the resource | Main topics covered
**Description** | An account of the resource | Explanatory notes, interview summaries, descriptions of environmental or cultural context, list of contents
**Creator** | An entity primarily responsible for making the resource | Not authors or composers of the recorded works but the name of the archive
**Publisher** | An entity responsible for making the resource available | Not the publisher of the original document that has been digitized. Typically the publisher will be the same as the Creator
**Contributor** | An entity responsible for making contributions to the resource | Any named person or sound source.Will need suitable qualifier, such as role (e.g. performer, recordist)
**Date** | A point or period of time associated with an event in the lifecycle of the resource | Not the recording or (P) date of the original but a date relating to the resource itself
**Type** | The nature or genre of the resource | The domain of the resource, not the genre of the music. So Sound, not Jazz
**Format** | The file format, physical medium, or dimensions of the resource | The file format, not the original physical carrier
**Identifier** | An unambiguous reference to the resource within a given context | Likely to be the URI of the audio file
**Source** | A related resource from which the described resource is derived | A reference to a resource from which the present resource is derived
**Language** | A language of the resource | A language of the resource
**Relation** | A related resource | Reference to related objects
**Coverage** | The spatial or temporal topic of the resource, the spatial applicability of the resource, or the jurisdiction under which the resource is relevant | What the recording exemplifies, e.g. a cultural feature such as traditional songs or a dialect
**Rights** | Information about rights held in and over the resource | Information about rights held in and over the resource

## Appendix A: Supported Formats and Identification Guide

### Supported format and identification chart

Format Type | Image/Visual | Decks Supported | Description
:---: | :---: | :---: | :---: 
**Audio Cassette** | ![AppendixA1](https://github.com/user-attachments/assets/b5d36d55-33c7-4bd6-94c0-c6af1c7a1483) | Nakamichi DRAGON (CAS 1), TEAC W-600R (CAS 2), Nakamichi DRAGON (CAS 3) | The most popular varieties of cassette tape are C60 (30 minutes per side), C90 (45 minutes per side), and C120 (60 minutes per side). Cassette tape information is magnetic.
**Minidisc** | ![AppendixA2](https://github.com/user-attachments/assets/1c643852-3308-4a97-9de9-cf626089156a) | Sony Minidisc Deck MDS-JE330 (MDS) | The most popular varieties of Minidisc have capacities of 60, 74, and 80 minutes of audio. Minidisc information is magnetic.
**Microcassette** | ![AppendixA3](https://github.com/user-attachments/assets/af9a55f6-a2cd-4a58-8e94-30899f45d08b) | Nakamichi DRAGON
(CAS 1), TEAC W-600R(CAS 2), Nakamichi DRAGON (CAS 3) | Because the recording speed is slower and the tape is thinner than an audio cassette, a tiny microcassette can hold 30 minutes per side. Microcassette information is magnetic.
**DAT (Digital audio tape)** | ![AppendixA4](https://github.com/user-attachments/assets/a57930d7-0ca8-499b-a0f9-2c66a1962ac3) | Sony PCM-R500 (DAT 1), Panasonic SV-3800 (DAT 2) | DATs are between 15 and 180 minutes in length, a 120-minute tape being 60 meters in length. DATs longer than 60 meters tend to be problematic in DAT recorders due to the thinner media. DAT information is magnetic.
**¼” open reel tape** | ![AppendixA5](https://github.com/user-attachments/assets/a9636180-1fbf-4ae7-a56f-359e669ea404) | Otari MX-5050 (R2R 1), Otari MX-50 (R2R 2) | The duration of audio tape depends on the reel. Generally, a 5-inch reel is 30 minutes, a 7-inch reel 60 minutes, and a 10.5-inch reel is 90-120 minutes, depending on the speed of the tape. ¼’’ open reel tape information is magnetic.
**Vinyl record** | ![AppendixA6](https://github.com/user-attachments/assets/6db3ca49-2ff9-4589-ad84-1c628271a396) | Technics Quartz SL-1210MK2 (PHONO) | A 12-inch vinyl LP originally stored 23 minutes per side, with later iterations increasing this capacity by several minutes. 7 inch records can hold between 4-6 minutes of music on each side. Vinyl record information is grooved. 
**78 Shellac** | ![AppendixA7](https://github.com/user-attachments/assets/9932b14c-4247-4187-ad38-f1f1bcf93dd9) | Technics Quartz SL-1210MK2 (PHONO) | The first records were made from acetate/shellac. Since 78s were typically 10- to 12-inch records, they only had the ability to record about three to five minutes of music per side. This limited the number of songs that could be recorded per side to one or two.78 shellac information is grooved.
**Transcription Disk** | ![AppendixA8](https://github.com/user-attachments/assets/c56c9fd7-a641-4660-a8f9-9832b798e8c2) | Technics Quartz SL-1210MK2 (PHONO) | 15 minutes of recorded information per side. Transcription disc information is grooved. Often groove can be vertical cut unlike other grooved disc formats. 
**Lacquer/acetate disc** | ![AppendixA9](https://github.com/user-attachments/assets/978c25c7-688e-44ec-a035-f9519c59c1db) | Technics Quartz SL-1210MK2 (PHONO) | A 12-inch lacquer LP can hold 22 minutes of audio per side. Lacquer/acetate disc information is grooved. 

### Timeline of Audio Formats

Format Type | Year Invented | Commercially Available | Obsolescence
:--- | :--- | :--- | :---
Cassette | 1963 | 1966 | Early 2000s 
Minidisc | 1992 | 1992 | 2013
Microcassette | 1969 | 1969 | Early 2000s 
DAT | 1987 | 1987 | 2005
¼” open reel tape | 1928 | 1958 | 1980s
Vinyl Record | 1880s | 1940s | n/a 
78 Shellac Record | 1894 | 1912 | 2010s
Transcription disc | 1920s | n/a | 

## Appendix B: Identifying Vinegar Syndrome & Sticky-Shed Syndrome

**Vinegar syndrome** is a condition created by the deterioration of acetate-based audio tape. The tape will release acetic acid, resulting in the infamous vinegar odor. In more advanced cases, hydrolysis causes the plastic base to shrink, resulting in a difference in width between the base and the magnetic binder. This creates cupping. In extreme cases this will cause tapes to become very brittle and break easily. In the latter case, the tape cannot be spliced without loss of information. While AD test strips can be used to diagnose the level breakdown due to vinegar syndrome in acetate based film, **strips cannot be used in this way on acetate audio tape** because of the relatively lower amount of cellulose acetate used in audio tape. **Please contact IS Lab Staff for help determining if a tape affected by vinegar syndrome may be used in the Lab.**

**Sticky-shed syndrome** is a condition created by the deterioration of the binders in a magnetic tape, which hold the ferric oxide magnetizable coating to its plastic carrier, or which hold the thinner back-coating on the outside of the tape. This deterioration renders the tape unusable. Visible signs include dust in the audio tape’s canister and patches of magnetic material that have flaked off the tape, creating a broken or cracked appearance on the surface. Auditory signs include loud screeching during playback, fast-forward, or rewinding, in which case playback must be stopped. **Tapes affected by sticky-shed syndrome cannot be transferred nor played in the Lab.**

“Audio engineers and sound archivists have over twenty years of experience identifying SSS tapes and treating them through baking. There are a small number of tape brands that are known to be afflicted with SSS in almost all cases. It is not only safe, but prudent, to assume that these brands have SSS as playback of sticky shed tapes will usually damage them.” See list of affected tapes in [Required Inspection](#required-inspection) section.

The following images depict the visual indications of sticky-shed syndrome:

![AppendixB1](https://github.com/user-attachments/assets/f76091e7-072d-47f4-b518-c0bde9f80278)

![AppendixB2](https://github.com/user-attachments/assets/66787d3a-1fd0-45a2-b49c-3005e06bf38c)

![AppendixB3](https://github.com/user-attachments/assets/d821f6ec-3cb4-46ca-8aca-285a393c6771)

*Example of Sticky Shed Syndrome*

## Appendix C: Baking Audio Tape

**Assistance by an IS Lab Staff member is required** in order to bake audiotape in the ThermoCenter tape oven. Please see [Thermocenter oven documentation - combined](https://docs.google.com/document/u/0/d/1PUGxgF3gJMQ374QfshrFgLr5_3rAtVtNAeZRWoPlrJE/edit "Thermocenter Documentation") for more information about tape baking.

## Appendix D: Reading Spectrograms in WaveLab

A spectrogram is an audio viewing tool that depicts time frequency and amplitude all in one graph. Spectrograms can be helpful in visualizing noise in a digital audio file. Izotope has a very [useful article](https://www.izotope.com/en/learn/understanding-spectrograms.html "Understanding Spectrograms") that explains what spectrograms.
1. Some problems may be easier to diagnose on a spectrogram or wavelet than in a waveform view, and some restoration tools are easier to apply at lower or higher levels of magnification. Use the smaller, upper timeline window for quicker navigation across the length of the recording, then use the lower timeline for analyzing and addressing any problem areas.
2. It can be helpful to view the recordings as spectrograms to note any noise or unwanted pops/cracks. Some problems may be easier to diagnose on a spectrogram or wavelet than in a waveform view, and some restoration tools are easier to apply at lower or higher levels of magnification. Use the smaller, upper timeline window for quicker navigation across the length of the recording, then use the lower timeline for analyzing and addressing any problem areas.
3. In order to do this, select “Spectrogram” in the bottom right part of the window to change the view of the recording.  

![AppendixD1](https://github.com/user-attachments/assets/46fbc20e-a76a-42c4-b833-dc66e7887be8)

4. To change the color or contrast of the spectrogram, click the check mark icon  to the right of the “spectrogram” button used to change the view.
	* Slide the markers on the “magnitude range” spectrum to affect the contrast. 
	* Slide the opacity controls and color scheme to get a better view of the recording. 
	* Do not touch any of the controls on the right side of the window. 

![AppendixD2](https://github.com/user-attachments/assets/35e61fd5-81e8-4c71-abdb-ef2ac0c42018)

* Change the color of the spectrogram by clicking on the icon on the right side of the “untitled” bar, as shown in the image above. 	Then go to the “Factory Presets'' menu to change the color.

## Appendix E: Timestep Archival Pre-Amp

In sound recording and reproduction, equalization (EQ) is the process of adjusting the volume of different frequency bands within an audio signal. A recording of music or spoken word can pick up a variety of tones, some of which are unpleasant. A graphic equalizer (EQ) boosts or cuts (amplifies or softens) a specific range of frequencies to improve sound quality. Archivists recreate EQ curves when transferring media that reflecting the EQ applied to the recordings originally. Typically preamps boost the signal and apply an EQ curve. After 1954, EQ curves in the U.S. were standardized across commercial record companies when the Recording Industry Association of America (RIAA) EQ curve was adopted. Every U.S. commercially produced record made after 1954 uses this EQ setting. This is the same EQ curve applied by most modern turntables and preamps because it is assumed that most people are playing back records made in this time period. 

Before 1954, each record company applied its own levels of EQ. Often each company had its own proprietary mix of materials to make shellac records so surface noise differed slightly between labels.

![AppendixE1](https://github.com/user-attachments/assets/52d7d111-a685-405f-a0c5-e79a2ba70d4f)

*Front control panel of the TimeStep*

**EQ Presets:** The Timestep Pre-Amp has built in EQ presets that apply differently EQ curves based on the record label/ era the disc was manufactured based on historical documentation. To change these presets, set the “Flat-EQ-Preset” knob to Preset (shown on display screen) and flip the “Preset” know to the right to find the desired preset. Refer to the TimeStep manual page to see a list of EQ presets (shown below). 

![AppendixE2](https://github.com/user-attachments/assets/077c0a48-ff31-4fa7-a400-aa5b59b9d4c4)

*TimeStep manual showing list of built-in EQ presets.*

**Manual EQ:** The timestep also allows the high frequency rolloff and low freq. turnover to custom levels. Set the “Flat-EQ-Preset” knob to “EQ” and us the “turnover LF” and “Rolloff RF” knobs to the left to set desired level. Note that the “TSEQ” or TimeStep EQ Prism input must be used for captures to apply the EQ settings. 

**TSFL Vs TSEQ**: On the Prism and WaveLab there are two sets of stereo input corresponding to the TimeStep Archival Preamp. That’s because it always outputs a signal with EQ curve applied and one without EQ otherwise known as “Flat” signal. This can be helpful as it may not be ascertainable which EQ was used in the original recording process because the recording is homemade or rare. In that case it’s best to use perform a “Flat Transfer” without any EQ using the “TSFL” input on the Prism and WaveLab. With a flat transfer, another archivist in the future, who may have access to documentation about the proper EQ adjustments made to the recording can easily add them in without having to work with a recording where an EQ curve has already been applied. The TimeStep constantly outputs both of these signals so it is possible to capture both at once. 

## Appendix F: Stylus Selection

*With the touch of a stylus picking up vibrations, a record player converts and amplifies subtle movements into pure, crystal clear sound. A record player’s stylus plays a vital role in this process, determining how the needle runs along the groove of the record and captures movement. Due to its impact on recording quality and grooved media longevity, it is important to select the stylus carefully. Stylus selection can be one of the most important parts of transferring grooved media. It’s important to choose a stylus that wouldn’t cause damage to the grooves or the stylus itself during playback. Certain types of disc are designed for playback with a stylus with a specific tip shape. Listed below are the five major types of styli.*

### Types of Styli

**Conical:** A reliable baseline model. Its head is rounded with a radius of around 0.6 mil which touches the center of the record groove walls, though 78 RPM records will need a much larger needle. Conical styli are often more budget friendly, producing a rich, solid sound. Older styli were typically conical styli so it’s safe to assume that most 78 rpm records will require this shape

**Elliptical**: The front part of the needle rides in the center of the record groove, while the smaller side makes more contact with the groove walls. This helps produce a more enveloping sound, as an Elliptical stylus tracks the grooves with greater precision. These needles are ideal for modern, stereo records.

**Microlinear**: These styli closely match the head used in the production of the master disc, producing an incredibly authentic sound thanks to extremely accurate tracking. The unique shape of the tip wears more evenly too, which extends the life of both the record and the stylus. 

**Shibata**: The Shibata stylus was originally designed for records with four channels of sound. These greatly reduce vinyl wear and tear compared to other needles whilst also producing a well-balanced sound.

**Special Line Contact**: This premium cartridge styli offers high frequency response, low distortion and low record wear thanks to its long vertical contact area and optimum tip design. Special Line Contact needles are not a budget option, though keen audiophiles will relish the difference in range and clarity.

Table of Styli at the IS Media lab
Size (in mm) | Shape | Ideal for 
:--- | :--- | :---
.7 | Elliptical (stereo) | Stereo, commercial vinyl 45 or 33 rpm discs.
.7 | Conical (stereo) | Stereo, commercial vinyl 45 or 33 rpm discs that are worn or in bad condition. 
1.1 | Conical | Mono 45 or 33 vinyl discs in poor condition.
1.1 | Mono elliptical (labeled MEXT/C) | Mono 45 or 33 vinyl discs.
2 | Conical | 78 rpm shellac records in good condition. 
2 | Elliptical | Mono 45 or 33 vinyl discs in poor condition (not advised for use)
2.3 | Conical | 78 rpm shellac records in good condition.
2.5 | Conical | 78 rpm shellac records in fair condition.
2.8 | Conical | 78 rpm shellac records in fair condition.
3 | Conical | 78 rpm shellac records in fair condition.
3.2 | Conical | 78 rpm shellac records in fair condition. 
3.5 | Conical | 78 rpm shellac records in fair/poor condition.
4 | Conical | 78 rpm shellac records in fair/poor condition.
2.3 | Elliptical | Wider and coarse groove historical record formats
2.5 | Elliptical | Wider and coarse groove historical record formats
3.2 | Elliptical | Wider and coarse groove historical record formats
3.5 | Elliptical | Wider and coarse groove historical record formats
4.0 | Elliptical | Wider and coarse groove historical record formats
4.5 | Elliptical | Wider and coarse groove historical record formats
5.0 | Elliptical | Wider and coarse groove historical record formats

Explore the charts in the TimeStep Archival preamp manual (shown below). They list a specific stylus recommendation for different record companies or date ranges. They are just meant to be starting points. Stylus selection is often fairly subjective. Generally, with worn records, it’s better to have a larger stylus which won’t be as sensitive to the damage as a thinner needle. A lot of this has to come with multiple plays of the same record using different styli. Questions to consider when you are listening: Is the surface noise taking over the recording? Then try a thicker needle. Does the high frequency response of the record feel like it could be better? Then try a thinner needle. 

![AppendixF1](https://github.com/user-attachments/assets/4b33551f-c5f9-4b86-9c40-3d4c025af5b3)

![AppendixF2](https://github.com/user-attachments/assets/294de3aa-7341-4975-931f-e2f7f7cb618b)

![AppendixF3](https://github.com/user-attachments/assets/8e61b188-dc02-4d05-8b3e-ca566202bc41)

![AppendixF4](https://github.com/user-attachments/assets/68925353-5ea1-4dda-aca7-c7b8988ff076)

![AppendixF5](https://github.com/user-attachments/assets/e959f114-79cb-43a3-8246-c1034e125c65)

### Other Considerations

#### Nude and Bonded Styli
The ‘nude’ stylus is solid diamond from top to bottom. Because of their lower mass, nude styli track vinyl records more accurately. Enhanced pickup from the vinyl to the cartridge head produces a better sound, helping you get lost in the music.

The bonded stylus is metal with a diamond material industrially adhered to the tip. Generally speaking, bonded styli are heavier and that increase in mass can inhibit the frequency from the stylus to the cartridge, ultimately producing a lower quality sound.

#### Round and Square Shank
There are two types of stylus shank: round and square. A stylus shank connects the tip to the cantilever, positioning the stylus tip in the record groove. A square shank stays in place firmly as it is mounted in a laser-cut square hole in the cantilever, locking the stylus in precise alignment with the record groove. Round shank styli may be more affordable, though round shanks can be more difficult to align when affixed to the cantilever. High quality styli are usually square shanks, as their shape enables a more precise alignment with the groove.

#### A Note on Cartridges
Moving Coil cartridges do not allow replacement of the stylus, which is bonded to the cartridge itself. Moving Coil cartridges are highly regarded, as they produce superior sound clarity with lower distortion. By contrast, Moving Magnet cartridges do allow replacement of the stylus, ensuring consistent quality without the need to replace the cartridge when its needle wears out. 
To deliver premium performance, the needle must accompany a quality cartridge. For optimum sound quality (particularly for discerning audiophiles), select a high quality Dual Moving Coil cartridge complete with a Special Line Contact nude stylus. 
To enjoy superior sound on a budget, consider a Moving Magnet, Elliptical, bonded cartridge. 

**The IS Media Lab is currently fitted with a Shure M44-G Cartridge**

## Appendix G: Replacing Styluses and Balancing the Tone arm (Lab Staff Only)

The tonearm should be balanced at least once a month and every time the stylus is changed. The tonearm should be balanced more frequently especially when the turntable is getting more use. Each stylus weighs slightly differently and thus the tonearm needs to be balanced whenever switching out stylii to ensure the tracking force doesn’t get out of whack. The record player does not need to be turned on to replace the stylus. Handle the tone arm, cartridge, and stylus with great care. During this process, flip the plastic stylus guard down to protect the stylus from hitting anything. The stylus guard for this stylus will flip down IN FRONT of the needle. 

Check out these videos for a more visual explanation of balancing the tone arm:
[Very Detailed Turntable Setup for Beginners](https://www.youtube.com/watch?v=WM-aIDwfrhc "Very Detailed Turntable Setup for Beginners")

[How to Set Up the Fluance RT80 & RT81 Turntable - Properly Balance the Tonearm](https://www.youtube.com/watch?v=01IZfGKfs5E "How to Set Up the Fluance RT80 & RT81 Turntable - Properly Balance the Tonearm")

And also this one which explains tracking force and anti-skate:
[What is Tracking Force and Anti-Skate on a Turntable? (And where to make adjustments to both)](https://www.youtube.com/watch?v=PEN2ROEdjhk "What is Tracking Force and Anti-Skate on a Turntable? (And where to make adjustments to both)")

Tracking force is the weight that the stylus applies to the record to be able to track the grooves properly. Each stylus should have a manufacturer recommended tracking force which must be set manually by the user. The force is set by the counterweight which sits on the back side of the tonearm. If the tracking weight is too low, the stylus won’t seat in the groove properly and may bounce around as the record spins. If the tracking force is set too high, it can cause damage to the record and the stylus. 

Anti-skate refers to a force applied to the tone arm by the turntable which counters the natural physical force that pulls the tonearm toward the center of the record when it spins. Without anti- skate the grooves would not be tracked properly by the stylus favoring one side Appendix H: Cleaning Tape Paths of the groove over the other. It’s important that it is set properly and applied at all times. 

### Regular Tonearm Balancing without Changing the Stylus
1. If not changing the stylus, the tracking weight of the tonearm can be checked simply by using the Pro-Ject Measure It-S2 High Precision Stylus Balance.
   > a. This is an extremely precise electronic scale made for measuring tracking weight.

![AppendixG1](https://github.com/user-attachments/assets/e7b871e4-026c-41ec-8906-d9f292f370dc)

*Box of the stylus balance scale.*

![AppendixG2](https://github.com/user-attachments/assets/6d626f78-984c-4ea3-ac21-1adc8526ff4e)

*Reference image of the device.*

2. Place the stylus carefully, without the guard directly on the black dot of the scale. The weight shown on the digital display should match the number shown by the counterweight. Within .2 grams of the correct tracking weight is acceptable. 
3. If the weight on the scale does not match the tracking weight, adjust the counter weight by twisting the counterweight clockwise to add more tracking weight and counter clockwise to take tracking weight away. If it needs to be adjusted majorly. Twist the number ring to set the weight shown on the scale on the tonearm. 
4. Put the High Precision Stylus Balance scale back in the way it was already package. Place the foam cube on top of the scale sensor before putting the metal cover. Then put the faux-leather sheath around the scale and place the scale in its plastic holder before sliding it into the box. 

![AppendixG3](https://github.com/user-attachments/assets/7dbe44ab-aa24-4c9d-95d5-a1b3eba723d2)

*Foam cube is placed on top of the scale before the metal cover goes on.*

### Changing Stylii
1. Flip plastic stylus guard down (if there is one) and remove the stylus from the cartridge. Put two fingers on either side of the stylus and pull it straight out of the cartridge away from the tone arm. 

![AppendixG4](https://github.com/user-attachments/assets/12188c60-347a-43d8-bb0b-0b83b6f655cf)

*Flip the stylus guard in front of the stylus to cover it.*

2. Put the stylus into its hole in one of the stylus cases. 

![AppendixG5](https://github.com/user-attachments/assets/7c57328f-37f5-46c1-b31e-de25abfe2880)

3. Pick the desired stylus and put it in the cartridge. Push the stylus straight into the hole. There should be a little resistance when pushing but do not force it in. Flip down the stylus guard if there is one. It should go into the cartridge naturally. 

![AppendixG6](https://github.com/user-attachments/assets/5fb68929-273e-493e-be6b-0d73e8239072)

*Gently, pull the stylus straight out of the cartridge.*

![AppendixG7](https://github.com/user-attachments/assets/7f7fd418-e6f8-4671-b587-74f48c2fd0f3)

*Check the location of the socket on the moving magnet cartridge before replacing the new stylus.*

![AppendixG8](https://github.com/user-attachments/assets/3c4965cd-2f65-41bf-b503-110484494622)

*Grasp the cartridge on either side with two fingers and carefully place it into the sock. There should be just a little resistance.*

4. Set the counterweight and anti-skate to zero to balance the tone arm. 
> a. Turn the counterweight clockwise to go to zero.

![AppendixG9](https://github.com/user-attachments/assets/5c2083f6-9d39-4c80-bfbc-ef1a4840a72d)

*Set the counterweight at and anti-skate to zero before balancing. Twist counterweight clockwise and anti-skate counterclockwise.*

5. Remove the tone arm from plastic holster and let it fall. If there is no stylus guard **MAKE SURE IT DOESN’T ACTUALLY HIT THE TURNTABLE**.

![AppendixG10](https://github.com/user-attachments/assets/a09e29bc-081f-4d77-ad3d-7390a4a92f6e)

*Tone arm is not resting on anything in the photo. The arm is also level. This is balanced.*

![AppendixG11](https://github.com/user-attachments/assets/74387102-ffb0-40c2-be65-f7d0807814a3)

*In the circled region its clear that the tone arm is not resting on anything and is floating evenly.*

6. If the stylus end of the tone arm wants to fall on the turntable the stylus is too heavy. If the counterweight brings the stylus up in the air at an angle there is too much weight on the back end of the tone arm.
> a. The idea is to completely balance the tone arm without it hitting or falling onto anything.
>
> b. It may be tricky to tell when it is actually balanced. The tone arm should hang unfettered and be level above the surface of the turntable

7. Once the tonearm has been balanced to the new stylus, set the balance point to zero by moving the number ring in front of the counter weight and bringing the 0 next to the line in the tone arm. Only turn the ring, not the entire counter weight. 

![AppendixG12](https://github.com/user-attachments/assets/8bf25a9c-8ac7-4d85-882c-cc54b0fd8f1f)

*Set the new balance as zero by aligning the white line on the tone arm with the “0” on the plastic ring attached to the counter weight. Only move the ring, not the whole weight. The object is to set the balance point for that stylus as “0”*

8. Look at the box where the stylus was to find the recommended tracking force. 
9. Set the tracking force by twisting the counter weight to the number indicated to apply that weight to the stylus. 
10. Set the anti-skate to equal the number of the tracking force. For instance if the tracking weight is 2 grams, set the anti-skate to 2. 
11. Sit back and listen to the joy of analog audio.

Tape paths should be cleaned before transfer to prevent interference from dust and debris during the transfer process. Please refer to the following instructions:

1. Cut or rip a strip of **printer paper** and **soak it with 99% isopropyl alcohol only**. Any amount of alcohol lesser than 99% risks damage to the machine.
2. Press the paper onto the roller at a 90-degree angle, applying moderate pressure. 
3. At the same time, use another figure to manually rotate the roller and collect dust or dirt on the piece of paper. 
4. Repeat this process multiple times, with several strips of soaked paper, until dust and dirt is no longer collecting on the paper. 

## Appendix H: Keith Monks Record Cleaning Machine Information

### Overview

In the late 1960s, the world’s first commercially produced record cleaner was designed and developed by Keith Monks Audio with BBC Radio engineers at Broadcasting House in London. The Keith Monks Record Cleaning Machine (RCM) is a precision instrument designed for the thorough cleaning and restoration of vinyl records. The Keith Monks RCM ensures optimal sound quality by removing dust, debris, and contaminants from the grooves of vinyl records. 

**discOvery miniOne Sapphire 45th Anniversary Limited Edition**

![KeithMonksMachine](https://github.com/user-attachments/assets/4c2373e7-7f7f-4334-97e4-8f26965831f0)

The discOvery mini One Sapphire is the smallest Keith Monks vinyl record washing machine and one of only 45 copies in the world. The device has a vacuum pump and an articulated arm with brush to carry out precision cleaning of microgrooves. On the left side of the top is the brush and fluid dispenser arm. In the middle of the top plinth is a slightly undersized platter topped with the proprietary Pyr/\Mat, and on the right side is the vacuum and thread arm with the spool of thread mounted near the pivot.

### Resources 

Official Website: [Keith Monks RCM](http://www.keithmonks-rcm.co.uk/range.html)

Official Manuals on operating the Keith Monks RCM:
* [Keith Monks Record Cleaning Machine Manual (Part 1)](https://memory.loc.gov/master/mbrs/recording_preservation/manuals/Keith%20Monks%20Record%20Cleaning%20Machine%20(1).pdf)
* [Keith Monks Record Cleaning Machine Manual (Part 2)](https://memory.loc.gov/master/mbrs/recording_preservation/manuals/Keith%20Monks%20Record%20Cleaning%20Machine%20(2).pdf)

[Keith Monks Audio Works • discOveryOne Redux Record-Cleaning Machine](https://www.theaudiobeat.com/equipment/keith_monks_discoveryone_redux.htm)

[Keith Monks Spare Parts](https://www.keith-monks.com/spare-parts)

### Maintenance 

![AppendixH1](https://github.com/user-attachments/assets/3417556d-e47a-4e94-b082-b316d79a56e8)

![AppendixH2](https://github.com/user-attachments/assets/39dc0673-54c4-4636-ab5d-b67722ddd25c)

![AppendixH3](https://github.com/user-attachments/assets/c9da6fb5-3afc-4787-abf2-9432953abfc3)

**KEEP THE MACHINE CLEAN**: Records need to be kept clean and free of dust. Wipe the cabinet, top deck and deck components with a damp cloth, and a little mild detergent or Windex glass cleaner if required.

**CHECK THE WASTE JAR REGULARLY**:

1. Open side door to reveal two cans
> a. Left contains dirty fluid (and has two tubes inside)
>  
> b. Right contains cleaning solution

2. Pour out liquid from the left “dirty” jar in the trash or toilet.
3. Wipe the inside of the jar with a paper towel.
4. Wash your hands.
5. Fill the right fluid jar (the ones with the single tubes) with the selected cleaning fluids (“record time cleaning solution”)
6. Refit the lids and replace the jars in the unit. 
7. **NEVER** allow the waste jar to become more than three-quarters full, as suction may draw fluid through the outlet tube and cause very expensive damage to the vacuum pump. Any such damage will not be covered under warranty. 

### Workflow (from manufacturer)

#### Tips:
* Do not apply brush pressure for longer than 5 to 10 seconds
* Fluid should not be left on the record surface for more than two minutes, to avoid evaporation, thus re-embedding particles. It is often necessary to slide the brush block along the metal tube support arm to ensure the complete surface is covered with fluid.
* If the discs are severely soiled, use a separate hand brush or vacuum cleaner brush wand to remove all loose debris. This is to avoid
damaging the Monk's brush.


#### Cleaning the Record:

1. Place the record on the turntable platter.
2. Push and swing the brush over the record until it locates into a slot in the mounting pillar, and is held in place, then loosen the hand screw on top of the brush block. 
3. Position the brush so that it is vertical, and the edge, near the outside of the turntable, is over the run-in groove at the start of the record. Its length should cover the grooved area of the record towards the label. It is ok if the brush is overhanging on the edge of the disc. 
4. Gently re-tighten the hand screw.
5. Before you start the turntable, check that the brush is just slightly shifted where it contacts the record. Added pressure damages the bristles further and will reduce the cleaning capability. 
6. Press the hand pump to dispense the appropriate liquid. 
7. Activate the turntable motor by moving the round switch on the left of the machine to the 'wet' position. The turntable will now revolve, but the vacuum pump does not operate in this position. You should be using only enough fluid to flow evenly over the record, forming a thin mirror-like film over the surface as the turntable revolves. The brush should contact the record for 5 to 10 seconds to loosen any particles embedded in the grooves.
8. Lift the vacuum arm, swing it to the center of the disc, and gently place the nozzle down just inside where the fluid edge is. 
9. Move the switch to 'dry' position, and raise the brush. You can allow the brush to lightly touch the disc as you move it off in order to sweep any excess liquid on the disc as the brush travels outwards. Remove excess fluid by holding the suction arm and swinging the arm back and forth just above the surface of the record edge. 
10. When the vacuum arm has reached the edge of the disc, switch to 'wet' position again, and replace the ann on its rest. Now use the edge of a folded paper towel slipped under the edge of the disc to catch any remaining fluid.

You now have a clean, dry disc. You can stop here if you feel like your record is clean enough. For archival standards, continue to step 11.

11. Lift the vacuum arm from its rest, and move it to the center of the disc just inside where the fluid line is. Move the switch to 'dry' position, and raise the brush. Again, you can allow the brush to lightly sweep across the disc as you move it off in order to keep any excess liquid on the disc for the vacuum arm to catch as it travels outwards.
12. When the arm has traversed the disc, switch to 'wet' position again, and replace the arm on its rest. 
13. Use the edge of a folded paper towel slipped under the edge of the disc to catch any remaining liquid at the edge of the disc. Wipe the vertical edge of the disc. 
14. You now have an archivally clean record. Place the record in a new clean sleeve.

## Appendix I: Demagnetizing Audio Playheads (Lab Staff Only)

Playback heads become magnetized due to contact with magnetic tape. Demagnetization should be performed after 10 hours or more of playback, and whenever it is suspected that a magnetic field has built up on the playhead. If not corrected, the field on the head will get larger with more playback. If excessive hiss or the loss of high frequency response is heard during playback, it may be necessary to demagnetize the tape head. Cassette tape decks or ¼” open reel deck playheads may be demagnetized. Always be careful when demagnetizing heads, failure to follow the steps risks damage to the deck or other equipment. The Han-D-Mag is a powerful magnet so keep tapes, electronics and other magnets away from it when plugged in. **Demagnetizing playheads is to be performed by lab staff only. It is not recommended that those with pacemakers or magnetic medical devices use the Han-D-Mag.** Refer to [Annis’ Hand-D-Mag kit](https://www.rbannis.com/Han-D-Mags.html "Han D Mags") for more information about demagnetization.  

You can find the “Hand-D-Mag” in the black metal cabinet near the front of the shelves. It is in a clear plastic box. Paper instructions for use are included in the box. 

![AppendixI1](https://github.com/user-attachments/assets/5344d704-13fa-4010-8708-d945bf67597d)

*Han-D-Mag in its box*

![AppendixI2](https://github.com/user-attachments/assets/be4f7519-2fab-49a6-99f3-5fbcf07bcb9b)

*What the Han-D-Mag looks like*

Before beginning, it may be helpful to look up a manual of the deck that needs to be demagnetized to ensure that the proper head is demagnetized. 

![AppendixI3](https://github.com/user-attachments/assets/cff35b54-37b2-46e4-bb83-346b01d2c727)

*Here is an explanation of the configuration of the heads for the Otari MX5050. Since only the playback heads are typically used at the IS Lab, only H2 and H4 would be demagnetized. The lab’s machine is on the top line of the chart.*

### Prepare to Demagnetize

1. Unplug deck
> a. It is imperative that the deck is turned off while demagnetizing the heads. Failure to do this could cause irreparable damage to the amplifier in the deck.

2. Move deck to clear space (recommended white tables at the front of room 118)

![AppendixI4](https://github.com/user-attachments/assets/94b4b3a1-a3b3-4e8a-abce-78b9b9794451)

*Open reel deck is positioned away from any magnets or electronics and is unplugged.*

> a. Pick up the deck and move it to a clear table away from any speaker or any electronic device. Demagnetizing in the immediate presence of other electronic devices risks damage to those devices.
> 
> b. No magnetic tapes should be in the vicinity of the deck.
> 
> c. It is also recommended that phones/ credit cards are taken out of pockets because of the strength of the “Hand-D Mag.

3. Lie tape deck on its back (if it’s open reel) to get better access/view of the heads.
4. Locate an 115V outlet at least 3 feet away from the deck and any other magnets/tape/ electronic equipment. 

![AppendixI5](https://github.com/user-attachments/assets/c9b56ff7-17da-4daa-8086-33add51613c0)

*Can visualize the deck and the heads better when open reel deck is laid on its back.*

![AppendixI6](https://github.com/user-attachments/assets/b7985b08-c3ee-407c-a8b1-0c37cc4cecf6)

*Use an outlet several feet away from the deck and away from other electronics or magnetic media.*

### Demagnetize 

1. Plug the ‘Hand-D-Mag” into the outlet. You should feel the “Hand-D-Mag” emitting pretty strong vibrations.
2. Approach the component to be demagnetized with the plastic jacketed probe.
3. Bring the probe tip within 1/8” of the head.
4. Wave sideways slightly.
5. Then withdraw slowly, while Hand-D Mag is still plugged in at a rate no faster than 3” to 4” per second; to a distance of at least 12.” 

![AppendixI7](https://github.com/user-attachments/assets/043b305a-b275-4062-82ce-637d6d4ee557)

*When the Han-D-Mag is on, CAREFULLY bring it close to the playhead.*

![AppendixI8](https://github.com/user-attachments/assets/809a1436-6e97-4475-bd27-cbe1802ccd33)

*Bring the probe tip until it is ⅛” from the head.*

![AppendixI9](https://github.com/user-attachments/assets/a813f95a-f4ad-4cdd-922f-ac4845a603f0)

*Wave the probe tip to the side slightly*

![AppendixI10](https://github.com/user-attachments/assets/8b7b7859-3141-4f67-8fce-141f3493fc15)

*Slowly, bring the probe away from the playhead at a rate of 3-4” per second.*

6. Repeat with other magnetic heads as needed.
7. Unplug the Hand-D Mag. **DO NOT keep the Hand-D-Mag plugged in for longer than 5 minutes** (unit may overheat).

## Appendix J: Guidelines for DAT Inspection and Playback

![AppendixJ1](https://github.com/user-attachments/assets/3a1d7818-9aca-4500-9810-9d1ca51ef6db)

*DATs are much larger than micro cassettes and slightly larger than MiniDVs but smaller than regular analog audio cassettes.*

### General Format Info

DAT stands for digital audio tape. Its signal is encoded digitally via 4mm helical scans, by contrast to other magnetic audio tape formats encoded by lateral scan. Because it is a helical scan, DAT playback decks have spinning heads which read the tape.The tape base consists of polyester with pure metal particles floating in a polyester urethane binder. Many tapes often have a back coating of graphite or another lubricant. DATs were being made from around 1985-2005. The pure iron pigments used in the magnetic layer of DATs are susceptible to oxidation (rust). Binder hydrolysis in the polyester urethane binder has proven to be a prevalent issue with many DATs, causing complete loss of information. The high speeds produced by the rotating heads passing by the moving tape exacerbate damage to the information layer. After the error threshold is crossed, the information is irretrievable. These factors combine to make DATs a very high-risk format.

DAT is a digital signal encoded on tape, which means that it will have an inherent sample rate and bit depth that cannot be changed. Most common bit depths/ sample rates are 12/32kHz 16/44.1kHz or 16/48kHz. Often the playback deck will detect the sample rate of the tape and will show it on the main display of the deck.

### Inspection and Preservation Guidelines 

According to the University of Illinois Preservation Self-Assessment Program, DATs are a “high-risk format,” due to the variety of preservation risks which they pose. During inspection for a DAT / digital audio tape, check for and note any of the following signs of deterioration which are known to afflict this format:
* Pure iron pigments used in the magnetic layer of DATs are susceptible to oxidation, or rust.
* Cracked or broken cartridge.
* Loose or missing pressure pad (small, square piece of foam underneath the tape).
* An uneven tape pack (when the wind of tape is not completely uniform).
* Binder hydrolysis results in tape shedding or sticky residue. **Do not attempt playback for tapes afflicted with these issues, as they can damage the decks and the tape.**
* As per the general instructions in the [Required Inspection](#required-inspection) section of this document, look for signs of mold and mechanical damage to the tape pack. **Moldy tapes must be isolated and cannot be played back in the Lab.**
* Make note of the manufacturer of the tape. Different manufacturers had varying ways of encoding information; different tapes may play better or worse on different decks. For example, if it is a Sony brand tape, try playback on the Sony PCM R-500, for example.
  > a. As noted in the [Audio Rack Equipment Section](#audio-rack-equipment), the Lab has two DAT decks. It is suggested to play tapes on decks made by their respective brands. If the tape is neither Sony nor Panasonic, try the Panasonic SV-3800.
* Never do the following:
> * Freeze DAT
> * Unspool the tape
> * Submerge the tape in water
* Before playback: Clean the outside of the cassette with a foam swab, dipped in a solution of 1 part isopropyl alcohol and 2 parts water. 

### Preservation and Playback

The high speed of the tape as it passes through the audio head can exacerbate pre-existing tape damage and loss of information. As soon as an error with the deck is presented, DATs should be removed to prevent further or complete loss of audio information. **At this point, tapes with these issues should only be digitized by trained preservation engineers, using high-quality audio equipment.**

**Important reminder**: Except in the case of serious errors, DATs **must be played to the end of the recording**. This is to ensure that the tape has a proper “library wind” for storage. If DATs are stopped in the middle of the recording and left unplayed, **this poses a serious risk of long-term physical damage or warping to the tape**, and loss of information.

In the case of playback errors, it may be necessary to make a separate access master that stitches together segments from successive playbacks into one good file. See Dan Figurelli’s discussion of this method from the [“What’s Up with DAT?” ARSC webinar](https://arsc.aviaryplatform.com/playlists/134/show/playlist_resource_id/7212/collection_resource_file_id/130155 "What's Up with DAT").

### DAT Workflow

Users should note that the [signal path](#audio-rack-equipment) for the DAT decks are slightly different than other playback equipment. Since the tape is encoded digitally, the Prism Analog-to-Digital converter can be bypassed and interpreted by the computer sound cards. While there is an analog routing system for the two DAT players, it is recommended to select **digital out**.

1. Because of the different signal path for DATs, it has been observed that, contrary to other decks, it’s better to have WaveLab open **before** playing the tape on the deck.
2. When opening WaveLab, remember to set the project and monitoring sample rate to the sample rate specified by the deck (see left image):

![AppendixJ2](https://github.com/user-attachments/assets/2680b256-f538-4ad3-a2e3-a6f1877edeb7)

*Sample rate of the tape is depicted on the upper left of the display.*

![AppendixJ3](https://github.com/user-attachments/assets/653d872b-e8d5-4c5c-8599-b6fa525dfd3f)

*Zoomed out photo of Panasonic sv-3800 for reference.*

![AppendixJ4](https://github.com/user-attachments/assets/30f55ff2-7141-4a55-b14a-65f927fc4f68)

*The monitoring sample rate on WaveLab must match the sample rate of the DAT. This information is communicated to the computer’s audio card, which receives the signal from the deck.*

![AppendixJ5](https://github.com/user-attachments/assets/b710d4ff-423f-4937-ac67-37b5757824e4)

*Set the project settings in WaveLab to match the DAT’s specifications.*

2. Once the sample rate has been set on WaveLab, begin monitoring to check for dropout.  Sometimes it may be difficult to tell when dropout is occurring. If someone is talking, it might be easier to tell that audio cutting mid sentence indicates dropout on the tape.
> a. High-pitched screeching indicates deterioration of the metal particle binder. In this case, the tape should be immediately stopped and removed from the deck.

3. DATs do not require levels to be set, since the audio reflected in the tape has already been sampled digitally.

### Digitization 

1. Capture the audio in WaveLab following the standard audio transfer workflow, which is available in the [Digitization](#digitization) section of this document.
2. If excessive dropout or noise occurs, stop the tape and start capturing from the beginning again. Due to the nature of playback and deterioration of the tape, more information may be read in a second pass of the tape.
   > a. Alternatively, if dropouts or failures occur, try playing the tape on the other DAT deck in the rack. Slight differences in tape or playback technology may make a deck better suited to a particular tape.
   >
   > b. If playback does not reveal more information where dropouts existed, that information is likely irretrievable.
3. **Ensure that the tape is played until the very end of the recording**. If a tape is stopped in the middle of a recording, this risks warping and physical damage to the tape.
