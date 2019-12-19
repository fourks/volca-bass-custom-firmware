# Volca Bass Custom Firmware
This page contains firmware modifications I wrote for the Korg Volca Bass synthesizer.
## Version 2.01
### Description
As of the latest release of the Volca Firmware from Korg, version 1.02, there are a few bugs in the official code which limit the capabilities of the instrument when modded for MIDI out. The Korg firmware plays all notes at velocity 127 and does not handle slides correctly. My custom firmware fixes these issues and allows it to better control external devices.
### New features
The firmware implements the following features:
* Correct velocities are emitted on MIDI out notes, while the the old firmware played all velocities at 127. At the moment it's possible to record velocites only via MIDI input, not with the internal ribbon keypad.
* Legatos/slides are played correctly for every note on MIDI out. The old firmware played legatos only when the previous note has the same pitch of the current one.
# Disclaimer
I don't take any responsibilities for possible damage caused by installing the firmware I provide on this page. Use at your own risk.
# Credits
Many thanks to:
* Tatsuya Takahashi and Korg for developing great products!
* Emil for releasing the firmware encoding/decoding tools at https://uglyduck.vajn.icu/ep/archive/2018/01/ 
* Pajen for giving me hints to begin with and this thread about Volca firmware hacking https://www.gearslutz.com/board/electronic-music-instruments-and-electronic-music-production/1232112-volca-sample-firmware-hack.html?s=9dd803db3f00c353b81f8eccea4ead0a 
