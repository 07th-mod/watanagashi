# PS3 Voice and Graphics Patch (in progress)

Currently hosting only the automated placed lines. All files need manual fixing, avoid placing them on your game.

README's going to be updated as the patch is developed. Refer to [Onikakushi](https://github.com/higurashi-mod/onikakushi) for more details about the patch.

Old collaborators welcome to join the repository, however it's still preferred to fork the repository and update through pull requests.


# Prerequisites

* [HigurashiPS3-Voices01.zip](https://mega.nz/#!vgdQkIrK!6Ral1MRTC266DVg4SM-P01s3Gnflo2StDdF0RrgigrY) + [HigurashiPS3-Voices02.zip](https://mega.nz/#!bQgCFK7S!Z_cFqU4WxFEo9RKONlh8dGGn7SkoEhKcodcP7uwmZqQ) [(or create a symlink using your EP1 files)](https://github.com/higurashi-mod/watanagashi#installation)
* [Graphics mod](https://www.mediafire.com/folder/ggd83ppkclafg/Higurashi_EP2_-_Graphic_mods)
* [Voice patch](https://github.com/higurashi-mod/watanagashi/archive/master.zip)

# Scripts progress

>Bold lines mean "in progress"

- [ ] **omake_02.txt**
- [ ] wata_001.txt
- [ ] wata_002.txt
- [ ] wata_003.txt
- [ ] wata_004.txt
- [ ] wata_005.txt
- [ ] wata_006.txt
- [ ] wata_007.txt
- [ ] wata_008.txt
- [ ] wata_009.txt
- [ ] wata_009_02.txt
- [ ] **wata_010.txt**
- [ ] wata_010_02.txt
- [ ] wata_010_03.txt
- [ ] wata_010_04.txt
- [ ] wata_011.txt
- [ ] wata_011_02.txt
- [ ] wata_012.txt
- [ ] wata_012_02.txt
- [ ] wata_012_03.txt
- [ ] wata_ep_01.txt
- [ ] wata_ep_02.txt
- [x] wata_tips_01.txt
- [x] wata_tips_02.txt
- [x] wata_tips_03.txt
- [x] wata_tips_04.txt
- [x] wata_tips_05.txt
- [x] wata_tips_06.txt
- [x] wata_tips_07.txt
- [x] wata_tips_08.txt
- [x] wata_tips_09.txt
- [x] wata_tips_10.txt
- [x] wata_tips_11.txt
- [x] wata_tips_12.txt
- [x] wata_tips_13.txt
- [x] wata_tips_14.txt
- [x] wata_tips_15.txt
- [x] wata_tips_16.txt
- [x] wata_tips_17.txt
- [x] wata_tips_18.txt
- [x] wata_tips_19.txt
- [x] wata_tips_20.txt
- [x] wata_tips_21.txt
- [x] wata_tips_22.txt
- [x] wata_tips_23.txt
- [x] wata_tips_24.txt

# Known issues

> In wata_tips_01.txt, [lines 474~526](https://github.com/higurashi-mod/watanagashi/blob/master/Update/wata_tips_01.txt#L474-L526) are clearly different from the PS3 version. Probably because of the whole red light talk. PS3 files for this scene are S20/05/440500017 and S20/04/440400025.


> Some voiced lines might end early if you are a slow header or playing with auto mode. There are too many cases of split lines (PS3 and PC version share the same script, but the reading is different) to fix manually. Some extreme cases may be fixed if you take your time to open an Issue.

# Installation

> Use the previous detailed tutorial to install the patch. See [here](https://github.com/higurashi-mod/onikakushi#installation).

In this patch we will only use the voice folders s02 (HigurashiPS3-Voices02.zip), s19 and s20 (HigurashiPS3-Voices01.zip). If you already have the first game with the patch installed, you don't need to download or copy the s19 and s20 folders. You can save your time creating a symbolic link.

### Creating a symlink

###### On Windows:
1. find your SteamLibrary common folder (usually \SteamLibrary\steamapps\common)
2. hold shift and right click on an empty space
3. click on "Open a command line window here" (or similar)
4. run the following commands on the cmd:
```
mklink /J ".\Higurashi 02 - Watanagashi\HigurashiEp02_Data\StreamingAssets\SE\s19" ".\Higurashi When They Cry\HigurashiEp01_Data\StreamingAssets\SE\S19"

mklink /J ".\Higurashi 02 - Watanagashi\HigurashiEp02_Data\StreamingAssets\SE\s20" ".\Higurashi When They Cry\HigurashiEp01_Data\StreamingAssets\SE\S20"
```


###### On Linux/OSX:
Use the ln -s command on terminal
```
ln -s /path/to/original /path/to/symlink
```
>Where /path/to/original is ./Higurashi When They Cry/HigurashiEp01_Data/StreamingAssets/SE/S19 and /path/to/symlink should be ./Higurashi 02 - Watanagashi/HigurashiEp02_Data/StreamingAssets/SE/s19

Repeat the command for the s20 folder.
