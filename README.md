# Touchpoint

Touchpoint is my MFA thesis in the Music Technology program at CalArts in 2014. It is an exploration of thinking about serialized multi-effects processing as a form of sound synthesis unto itself. Consider it a reaction to plugins like [The Finger](https://www.native-instruments.com/en/products/komplete/effects/the-finger/), [Turnado](http://sugar-bytes.de/content/products/Turnado/index.php?lang=), [Stutter Edit](https://www.izotope.com/en/products/create-and-design/stutter-edit.html), [Gross Beat](http://www.image-line.com/plugins/Effects/Gross+Beat/), etc.

Touchpoint is meant to be played entirely with [Lemur](https://liine.net/en/products/lemur/); your computer is merely the sound source. My goal was to make these "creative DSP" environments more gesturally performative. I wanted to establish a consistent toolset and performance practice for an ecosystem as complex as these types of processors. I wanted to make an instrument that you can be good or bad at, that you can write riffs for, that is accessible and diverse at first glance but which reveals more possibilites as you dig into it.

This instrument can be used with any audio input. To that end, the ensemble also includes a rudimentary subtractive synth which is normalled as its input by default. The Lemur interface also has controls for this synth. The "TouchEnv" control on each slot effectively acts as a note on message for triggering this synth. All of the modern workarounds for proper DAW sync are implemented as well, so feel free to use it as a Reaktor plugin.

There are several places where I discuss the operational principles of Touchpoint at length, including [this 2014 ICMC/SMC paper](http://speech.di.uoa.gr/ICMC-SMC-2014/images/VOL_2/1469.pdf).

For now, I've decided I've been sitting on it for too long. I'm not going to wait for a few more key features to go in to release this thing at v1.0, since the majority of the work that had gone into it happened last year, during my thesis. This is a raw dump of the state of the rig as it was used by me for performances, so I cannot guarantee there aren't a few things that haven't been kept in step for release. For example, I know that triggering Snapshots from the Lemur interface is slightly broken.

Please enjoy! I'd love to hear about how others are using this instrument. Feel free to reach out to me if you need help with Lemur or setting up the OSC communication for it or anything else... this is not a MIDI-friendly device, so it basically won't do anything unless you've got Lemur going.

This instrument was partially developed in-house in the Research department at NI headquarters in Berlin during the summer of 2013. Huge thanks go to Max Zagler and Andre Estermann, whose input and assistance massively shaped the design of this device.
