# bfheroes-sound-tools
Useful stuff to work with Battefield: Heroes™ sound and/or music files.

## How to use

1. find a __.wav__ file you want to convert. *(mp3 files just no)*

2. open a command prompt inside this folder and run any of these commands depending which task you'd like to perform:

**IN-GAME SOUND** *(eg. weapons, bullets?)*

`sox in.wav -b 32 -s -c 1 -r 44100 out.wav`

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

## Possible thanks to
- Apache Thunder for letting me know about bf2 sound tools.
Discord: `Apache Thunder#1696`
- Original distributor of BF2 sound tools, I was unable to track him/her.
