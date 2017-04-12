# Touchpoint

## Disclaimer
This software is abandonware. It is provided as-is, with some machine-specific paths and deprecated patching techniques preserved. It may recieve an overhaul some day (perhaps an update with proper serialization in Reaktor 6!), but the original Reaktor Ensemble and [Lemur](https://liine.net/en/products/lemur/) layout have been provided in their alpha state. Submitting issues would certainly be a good way to thaw the project!

Please note, this is not a MIDI-friendly device. It won't do anything unless you've got Lemur or a similar OSC interface going.

## Installation
- [Reaktor Player](https://www.native-instruments.com/en/products/komplete/synths/reaktor-6-player/) (free option) or [Reaktor](https://www.native-instruments.com/en/products/komplete/synths/reaktor-6/) is required to open the Ensemble. Works with Reaktor 5 or newer.
- Lemur for [iOS](https://itunes.apple.com/us/app/lemur/id481290621?mt=8) or [Android](https://play.google.com/store/apps/details?id=net.liine.lemurapp&hl=en) is required to run the original OSC interface.
- Lemur Editor for [OS X](https://liine.net/assets/files/lemur/Lemur-Installer-5.3.2-OSX.dmg) or [Windows](https://liine.net/assets/files/lemur/Lemur-Installer-5.3.2WIN.exe) to upload the layout to your mobile device.

## Description
Touchpoint is my MFA thesis in the [Music Technology](https://music.calarts.edu/programs/music-technology) program at [CalArts](https://calarts.edu/) in 2014. It is an exploration of thinking about serialized multi-effects processing as a form of sound synthesis unto itself. Consider it a reaction to plugins like [The Finger](https://www.native-instruments.com/en/products/komplete/effects/the-finger/), [Turnado](http://sugar-bytes.de/content/products/Turnado/index.php?lang=), [Stutter Edit](https://www.izotope.com/en/products/create-and-design/stutter-edit.html), [Gross Beat](http://www.image-line.com/plugins/Effects/Gross+Beat/), etc.

This instrument can be used with any audio input. To that end, the ensemble also includes a rudimentary subtractive synth which is normalled as its input by default. The Lemur interface also has controls for this synth. The "TouchEnv" control on each slot effectively acts as a note on message for triggering this synth. All of the modern workarounds for proper DAW sync are implemented as well, so feel free to use it as a Reaktor plugin.

There are several places where I discuss the operational principles of Touchpoint at length, including [this 2014 ICMC/SMC paper](http://speech.di.uoa.gr/ICMC-SMC-2014/images/VOL_2/1469.pdf). For the full paper, please see [my MFA thesis](http://mtiid.calartsmusictech.com/wp-content/uploads/2016/09/nsuda_mfa_2014.pdf).

This instrument was partially developed in-house in the Research department at NI headquarters in Berlin during the summer of 2013. Huge thanks go to Max Zagler and Andre Estermann, whose input and assistance massively shaped the design of this device.

Check out the [Reaktor User Library](https://www.native-instruments.com/en/reaktor-community/reaktor-user-library/entry/show/8642/) entry for some sound examples.
