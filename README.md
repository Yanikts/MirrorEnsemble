# MirrorEnsemble
Use of a physical interface and High-dynamic light sensors to manipulate sound in PureData.

Reflex is the main patch. To make it work properly, you need these objects and patches : grainclone2~, granulateur1, granulateur2, granulateur3, HuzzahReceive (if you want to receive OSC message from a Adafruit Feather Huzzah microcontroler), lfo~, randomize and randomize~.

You will also need the soundfiles "Souffle1.wav", "Lick1a.wav", "Lick2.wav" and "Cles1.wav" to get the desired results (most of the interaction between the sensors is hard-coded for these samples anyway).

You can also run the Arduino code to send OSC messages to the "HuzzahReceive" patch.

This is the version that was presented at Université de Montréal on April 25th 2018. Further improvements will occur and future presentations will have improved features.

Modifications will include :
-Improved response from the light sensors
-Addition of sound cues to complement the aleatory comportment of the sensors
-Additional visual scenes
-CPU optimization

Special thanks to Olivier Bélanger and Jean Piché for their precious contribution to the project.
