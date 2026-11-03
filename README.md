# GrayGlish 2.0 Reclist

**GrayGlish 2.0** - Reclist and resources for GraySlate's English UTAU reclist

## What is GrayGlish?

GrayGlish is a method of English UTAU voicebank creation.  All recordings and aliases utilize X-Sampa for transcribing phonemes.  This list is meant to give users the essentials needed for coverage of the English language while removing unneeded bloat and duplicate recordings and oto entries other reclists are infamous for.<br />
<br />
Personal modifications of GrayGlish 2.0 for private use are fully permitted without permission required. Please ask permission before distributing modified GrayGlish reclists. 
## GrayGlish 2.0 Specs Breakdown

- Number of recordings: 495 per pitch
- Number of oto lines: 2,231 (approximately)

## Reclist Package Contents

- GrayGlish 2.0 Development Guide PDF
- Full GrayGlish 2.0 reclist
- Full OREMO GrayGlish 2.0 reclist
- X-Sampa phoneme pronunciation guide
- Full base oto
- Full suffixed base oto
- Sample recording examples
- vLabaler base projects (suffixed and non-suffixed)
- GrayGlish 1.0 and 2.0 bank links
- Additional GrayGlish 1.0 and 2.0 UST links
- IroIro2 replace lists (VCCV/ARPAsing to GrayGlish)
- Replacement en-xsampa.yaml file for OpenUTAU's EN X-SAMPA phonemizer
- Sample UST (Take Me To Church - Hozier, UST by GraySlate)<br />
<br />
GrayGlish 2.0 differs from the now deprecated GrayGlish 1.0 in the way that the main portion of the reclist is comprised of 2-syllable strings, as opposed to the longer strings in 1.0.  While GrayGlish 1.0 voicebanks are perfectly usable and compatible with the OpenUTAU EN X-Sampa phonemizer, the recording method of 1.0 is not recommended.  GrayGlish 2.0 is a far easier, more optimal system for GrayGlish voicebank creation.

## Recommended Recording Steps

[OREMO](<https://github.com/SuibianP/OREMO_Unicode/blob/master/OREMO-3.0-b190106-CHS-b190306-Unicode-b200314.zip>) or [Recstar](<https://github.com/sdercolin/recstar/releases>) are recommended for recording GrayGlish voicebanks.  VV and CC strings vary in length but if you want to use Guide BGM, any 2-syllable BGM will work with the main CV section of the reclist.<br />
<br />
Portions of the reclist can be separated into distinct output folders or the reclist can be divided when loading it into OREMO or Recstar for ease of recording.  By default, all recordings for GrayGlish 2.0 are placed in the same folder per pitch.

## Oto Configuration

[vLabeler](<https://vlabeler.com/>) is recommended for configuring GrayGlish otos.  vLabeler projects for suffixed and non-suffixed otos have been included in the reclist package. Oto entries are tagged by type - Consonant, Vowel, CV - for convenience in the configuration process.  To use the vLabeler projects, simply load your voicebank and base oto into the .lbp file over the example voicebank and oto.<br />
<br />
For more in-depth and specific otoing guidance, consult the Development Guide included in the package.

## Voicebank Usage

GrayGlish 2.0 and 1.0 voicebanks are compatible with the OpenUTAU EN-XSAMPA phonemizer.  The en-xsampa.yaml file included in the reclist package will need to be placed in your voicebank's root folder to enable the fallbacks and replacements required to use GrayGlish banks with the phonemizer.  While this file will not always be perfect and phonemes will still need to be edited, it makes using GrayGlish banks a smoother experience in OpenUTAU.<br />
<br />
Do note that GrayGlish 2.0 banks have dummy aliases for vowels to make the replacements and fallbacks for the phonemizer work.  Some standalone vowels are not otherwise used in 2.0 and exist as dummy duplicate aliases so the phonemizer works as intended.<br />
<br />
<img width="1899" height="952" alt="{354D0677-0908-4C57-BC34-1FF3D43BB7D0}" src="https://github.com/user-attachments/assets/35beaa6f-acd6-4833-9b72-cb2a2be4b7e9" /><br />
<br />
## Video Tutorial
<div align="left">
      <a href="https://youtu.be/N3c7l1udams">
         <img src="https://img.youtube.com/vi/N3c7l1udams/0.jpg" style="width:50%;">
      </a>
</div>
When using Classic UTAU, there are several recommended tools to aid in voicebank usage.

### IroIro2 Replace Lists

The package contains replace lists for UST files that were originally intended for VCCV and ARPASing voicebanks.  These lists replace VCCV/ARPASing phonemes with the X-Sampa used in GrayGlish.  This requires the plugin [IroIro2](<ux.getuploader.com/bizz_v/download/182>) to use.<br />
<br />
Follow the below steps to use the replace list:

- Make sure iroiro2 is installed properly and with the English translation.
- Copy the "VCCV to Gryaglish 2"/"ARPASing to GrayGlish 2" text file(s).
- Navigate to where the iroiro2 plugin folder is, for me that's C:\Tools\Utau\plugins\iroiro2.
- Open the "Replace" Folder, then "Tikan".
- Paste "VCCV to GrayGlish 2"/"ARPASing to GrayGlish 2" in that location.
- Open UTAU and a VCCV English or ARPASing UST.
- Select all or the portion of the UST's notes you're converting.
- Open IroIro2.
- Select "Replace (By List)".
- In the "Replacement" drop down menu, select the VCCV to GrayGlish 2 or ARPASing to GrayGlish 2 option, depending on which UST you chose.
- Press OK in that menu and OK in the main menu to change the phonemes.<br />
<br />
Conversion won't always be accurate, but it will assist in conversion and will help familiarize you with GrayGlish 2.0's X-Sampa.

### Video Tutorial
<div align="left">
      <a href="https://www.youtube.com/watch?v=21Dt25XPDDA">
         <img src="https://img.youtube.com/vi/21Dt25XPDDA/0.jpg" style="width:50%;">
      </a>
</div>

### PhonemizeronUTAU - Classic UTAU Plugin
---
The plugin [PhonemizeronUTAU](<https://github.com/xunmengshe/PhonemizerOnUtau/releases/tag/0.0.4>) does essentially what the OU phonemizer does but in Classic UTAU.  This splits the phonemes in word-based UST files, taking a lot of work out of splitting up phonemes by hand.  While not always accurate, it is helpful in reducing the workload when working on USTs.<br />
<br />
<img width="1900" height="956" alt="{FB8B1E1F-AAF0-4BB8-8B4E-43DE08143481}" src="https://github.com/user-attachments/assets/5d715604-7dae-4909-9f87-f6e3477f4009" />
<img width="1911" height="941" alt="{36D7C24A-154A-4377-AEF5-DF05A4AA4D22}" src="https://github.com/user-attachments/assets/51b16457-5946-48ab-ba64-541ef57aba7d" />

# GrayGlish USTx and UST files

### [UST list on official website](<https://assbackwardsp.wixsite.com/utaubackwards/usts>)
### [UST list on UtaForum](<https://utau.forum/resources/grayslates-ust-svp-vsqx-etc-directory.552/>)
### [Vocalsynth Distribution Files on VocaLoader](<https://vocaloader.app/search?type=sequence&user=387>)

# Voicebanks that use GrayGlish (1.0 and 2.0)

### [Miyuki Masara](<https://utau.wikidot.com/utau:miyuki-masara>)
### [Hanae Masara](<https://utau.wikidot.com/utau:hanae-masara>)
### [Hayate Nori Masara](<https://utau.wikidot.com/utau:hayate-nori-masara>)
### [Seiji Masara](<https://utau.wikidot.com/utau:seiji-masara>)
### [Yuina Harune](<https://utau.wikidot.com/utau:yuina-harune>)
### [Daryl 'Murica Jones](https://utau.wikidot.com/utau:daryl-murica-jones)
### [Hinaya Nurune](https://utau.wikidot.com/utau:hinaya-nurune)
### [Lewis Wendelken](https://utau.wikidot.com/utau:lewis-wendelken)
### [Paris Carlile](<https://utau.wikidot.com/utau:paris-carlisle>)
### [Ichirou Honda](<http://utau.wikidot.com/utau:ichirou-honda>)
### [Ichiko Honda](<http://utau.wikidot.com/utau:ichiko-honda>)
### [Cherilee](<http://utau.wikidot.com/utau:cherilee>)
### [Roselle](<http://utau.wikidot.com/utau:roselle>)
### [Hareff Linohai](<http://utau.wikidot.com/utau:hareff-linohai>)
### [Kagyakune Souma](<http://utau.wikidot.com/utau:souma-kagyakune>)
### [Uzuhi](<http://utau.wikidot.com/utau:uzuhi>)
# Other Miscellaneous Resources

### [GrayGlish Official Website Resources](<https://assbackwardsp.wixsite.com/utaubackwards/reclists>)<br />
<br />

### Video Tutorials

<div align="left">
      <a href="https://www.youtube.com/watch?v=ojkvIh2kcQw">
         <img src="https://img.youtube.com/vi/ojkvIh2kcQw/0.jpg" style="width:50%;">
      </a>
</div>

<div align="left">
      <a href="https://www.youtube.com/watch?v=8oogHLJk1vs">
         <img src="https://img.youtube.com/vi/8oogHLJk1vs/0.jpg" style="width:50%;">
      </a>
</div>
