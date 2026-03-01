### Arturia KeyLab mk3 integration plugin for Renoise 3.1 (API 5)
Tested with KeyLab 49 mk3 on OSX 10.9

![tool window](/tool_window.PNG)

### Notes:
Basically I took the last version of [KeyLab mkII tool](https://www.renoise.com/tools/arturia-keylab-mkii) still compatible for Renoise 3.1, fixed the device names, stripped out the unused buttons and added a few features, like:

– **Auto-start**, because having to open tool and press ON button each time to make it work sucks;

– **Optional injection of Pad MIDI mappings** into current song to use Bank A pads for navigation.
 
  ⚠️ Warning: this may force save + overwrite of the current song

&nbsp;

Anything except KeyLab 49 mk3 was not tested, so use it at your own risk.

This _might_ work on KeyLab Essential mk3, but I don't have the hardware to test that.

I am not really interested in updating this for newer Renoise versions that use API 6, but you're free to do so yourself.

### Quick start:
- On KeyLab, select DAW Program with MCU protocol;
- Set KeyLab (MIDI) device as Renoise Master Keyboard;
- Choose your device name in the list and press ON button.

Optionally patch the current song with MIDI mappings to use Bank A pads for navigation
