# bfheroes-sound-tools
Useful stuff to work with Battefield: Heroes™ sound and/or music files.

## eli5

1. find a __.wav__ file you want to convert. *(mp3 files just no)*

2. open a command prompt inside this folder and run any of these commands depending which task you'd like to perform:

**IN-GAME SOUND** *(eg. weapons, bullets?)*

`sox %1 -b 32 -s -c 1 -r 44100 file_name.wav`

(this one requires you to install SOX from the requirements folder)

**IN-GAME AMBIENCE SOUNDS** *(i never tested this one actually, not guaranteed to work)*

`oggenc.exe -b 112.001000 -s 0000194a file_name.wav`

**LOADING MAP MUSIC**

`oggenc.exe -b 112.001000 -s 00002811 file_name.wav`

**FLASHMENU CLIENT MUSIC**

`oggenc.exe -b 112.001000 -s 000035af file_name.wav`

3. wait for it.

4. keep waiting.

5. at this point you should have your fresh .wav/.ogg file ready to use, if you don't, get a better pc

or browse the internet for help idk.

## credits
Apache Thunder for letting me know about bf2 sound tools.

discord: Apache Thunder#1696

the actual creator of BF2 sound tools, she/he's the mvp here

i was unable to find him/her but anyways, thanks <3

(most of stuff remains exactly the same except for in-game sounds encoding)

bixxy for being a cute emo lol

discord: Kebab#9412
