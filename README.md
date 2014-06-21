Hybrid headphone amp
====================

Copyright (c) 2014 Xav Paice

Version 0.1 - initial prototype

Based on the circuit by Rogers Gomez at
http://diyaudioprojects.com/Solid/12AU7-IRF510-LM317-Headamp/
I have made some modifications, using a laptop power supply and IRF540
rather than IRF510, plus added a rudimentary crossfeed network.

This is an Open Hardware project. For details about OSHW, go to:
http://freedomdefined.org/OSHW

All documentation and drawings are covered by Creative Commons Attribution
4.0 International License.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Hybrid Headphone Amp</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/xavpaice/hybridheadphoneamp" property="cc:attributionName" rel="cc:attributionURL">Xav Paice</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/xavpaice/hybridheadphoneamp" rel="dct:source">https://github.com/xavpaice/hybridheadphoneamp</a>.

The schematic and PCB are all drawn with Kicad (http://www.kicad-pcb.org/).

The PCB is easily etched at home, however I did find the pads way too small
to successfully drill using a 1mm bit and dodgy battery drill.  Additionally
the silk screen is backwards and I've got my Kicad layers totally mixed up.

The current PCB (just) fits in a Hammond 1590 with the aid of some tiny heatsinks
however the box heats up a lot and it's not an ideal build by any stretch.

TODO list:
----------
* fix the silk screen and PCB layers so it prints correctly
* make the PCB pads bigger and space things out better
* use bigger heatsinks and account for that space on the PCB
* the crossfeed doesn't seem to do a lot, and the switch is
  largely useless
* there's hiss, and power supply crackle.

Hacking:
--------
* Please do.
* Please submit pull requests, I'd love some help
