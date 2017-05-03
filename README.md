# PS3 Voice and Graphics Patch
#### For Higurashi No Naku Koro Ni - Chapter 2 Watanagashi

> This repository **only** hosts the script files and a few voice files needed to fix bugs, check our [wiki](https://github.com/07th-mod/guide/wiki/Getting-started) for instructions on how to install the patch!

This patch aims to combine the efforts of the ps3 voice patch and the ps3 sprites/background patch, and fill in missing voice files not covered by the original voice patch.

# Installing the patch

> [Check our wiki](https://github.com/07th-mod/guide/wiki/Getting-started).

# Releases

https://github.com/higurashi-mod/watanagashi/releases/

This repository is in constant change. Sometimes new releases might get on hold until there is enough content to push a new patch. If the latest patch have a bug that seems to be already fixed in the repository, try downloading the master file. The master file will always have the latest files, regardless of the current release being outdated or not.


# Known issues

> In wata_002.txt, the scene where they are playing a game is missing a large chunk of dialog. Most likely because of obvious copyright issues. Needs retranslation to fit with the PS3 audio.

> In wata_tips_01.txt, [lines 474~526](https://github.com/higurashi-mod/watanagashi/blob/master/Update/wata_tips_01.txt#L474-L526) are clearly different from the PS3 version. Probably because of the whole red light talk. PS3 files for this scene are S20/05/440500017 and S20/04/440400025.

> In wata_004.txt, the PS3 script differs a lot from the PC version. There are dozens of new dialog lines, including voiced ones. Some voices are also missing and some lines were rewritten. This will most likely bother you if you play with japanese text.

> In wata_005.txt, the scene in Angel Mort was almost completely edited in the PS3 version. Some lines won't have voices and the flow of text/voice might get weird because of that. Later scenes in this chapters were also substantially increased in the PS3 version, this content might be translated and added later.

> In wata_008.txt, several graphic scenes were cut in the PS3 version. Because of that, some scenes are lacking voices.

>In wata_010.txt, [line 241](https://github.com/higurashi-mod/watanagashi/blob/master/Update/wata_010.txt#L241) the dialogue said in the text and the voice file diverge. In the original text, Keiichi only asks confirmation about the hour (3:00). In the sound file, he adds "昨日に続いてか？" asking about the day before.

>In wata_010_02.txt, [line 1050](https://github.com/higurashi-mod/watanagashi/blob/master/Update/wata_010_02.txt#L1050) this last comment that Shion makes about Mion dosn't seem to have a soundfile. The order in the dev folder jumps to Keiichi after the audio in line 1048. This happens again in line 1065.

>In wata_010_04.tx, [lines 2046~2053](https://github.com/higurashi-mod/watanagashi/blob/master/Update/wata_010_04.txt#L2046-L2053) this last bit of the conversation has 2 problems.
>1- The last question Oishi asks Keiichi dosn't have a sound file.
>2- There are 2 soundfiles for Keiichi in this scene, first is the one where he responds Oishi and says he didn't see the representatives. The file is S02/01/130100732 where he responds with 「見ていません。(miteimasen). The second soundfile (S02/01/130100733) is what is being said in the text displayed.I left only the second sound file, since it won't change the meaning of the conversation.

>In wata_011_02, [lines 1422~1427](https://github.com/higurashi-mod/watanagashi/blob/master/Update/wata_011_02.txt#L1422-L1427) this part of the conversation dosn't have sound files for Oishi.

>In wata_012_02.txt, lines [2768~2777](https://github.com/higurashi-mod/watanagashi/blob/master/Update/wata_012_02.txt#L2768-L2777), there are no sound files for this part of Mion's story. That's not the only part, there's actually a lot of parts without sound files during her entire story.

>In wata_012_03.txt,[lines 3067~3080](https://github.com/higurashi-mod/watanagashi/blob/master/Update/wata_012_03.txt#L3067-L3080), there are no soundfiles for Mion in this part.

> Some voiced lines might end early if you are a slow header or playing with auto mode. There are too many cases of split lines (PS3 and PC version share the same script, but the reading is different) to fix manually. Some extreme cases may be fixed if you take your time to open an Issue.

# Developing with us

Usually, older contributors are welcome to join the repository and push their own changes without supervision. However, you can also aid the development just by forking the repository and working on your own changes. After you are done, commit the changes, make a pull request and if it's good enough, the changes will be merged. Both approaches are more than welcome!

# Credits

- GuraMan - For making the graphics mod
- VocalNight - For helping with the scripts
- Anon - For giving us the PS3 files, scripts and automating most of the work
- Grelo - For the **new** graphics mod
