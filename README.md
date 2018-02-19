# MirrorEnsemble
Use of a physical interface and RGB light sensors to manipulate sound in PureData.

Reflex is the main patch. To make it work properly, you need these objects and patches : grainclone~, granulateur1, granulateur2, granulateur3, HuzzahReceive (if you want to receive OSC message from a Adafruit Feather Huzzah microcontroler), lfo~, randomize and randomize~.

You will also need the soundfiles "StetsonSamp1.wav", "StetsonSamp2.wav" and "StetsonSamp3.wav" to get the desired results (most of the interaction between the sensors is hard-coded for these samples anyway).
