# 8C_streamdeck
Control your Dutch & Dutch 8c speakers from an Elgato Stream Deck. No browser tab, no cloud.
! Unofficial plugin. Not affiliated with, endorsed by, or supported by Dutch & Dutch.

(Version française plus bas.)

WHAT IT DOES
------------

8C_streamdeck_TJ_V1 talks directly to your 8c speakers over your local network, using the same local API as the speakers' own web app (Ascend). You get all your everyday controls on physical buttons and dials. The displays update live, even when you change something from the web app.

Keys (all Stream Deck models)
------------

- Volume + / Volume − : Raises or lowers the volume by an adjustable step (0.5 to 6 dB). Hold the key to keep changing it. The key shows the current level in dB.
- Mute : Mutes or unmutes. The key turns red when muted.
- Fixed volume : Jumps to a set level (for example your reference level). The key lights up when you are at that level.
- Volume toggle : The first press goes to a set level. The second press goes back to the volume you had before. Useful for a quick "dim" or a reference level.
- Standby : Puts the speakers in standby or wakes them up.
- Source : Selects a given input, or steps through them one after another.
- Voicing : Selects a given voicing, or steps through them. The key shows the active voicing.
- Preset : Selects a given preset, or steps through them.
- Room matching : Selects a given Room Matching profile (room EQ), or steps through them. The key shows the active profile.
- Linear phase : Turns linear phase on or off.
- XLR mode : Toggles the XLR input between AES and Analog (low or high gain), or selects one mode directly.
- Front LED : Turns the front LED on or off.

Keys set to a fixed choice (a source, voicing, preset, Room Matching profile, XLR mode or level) light up when that choice is active. Put several side by side and you get an instant selector.

Dial and touch strip (Stream Deck +)
------------

- Rotate: volume.
- Rotate while pressing: fine volume adjustment.
- Press the dial: an action of your choice (default: mute).
- Touch strip, left half: an action of your choice (default: standby).
- Touch strip, right half: an action of your choice (default: next voicing).

The press and each half of the touch strip can do any of these: mute, standby, fixed volume, volume toggle, source, voicing, preset, room matching, linear phase, XLR mode, front LED, or nothing.

The touch strip shows, live:
- a speaker icon;
- the input in use: PL (player / streaming), AES, or AN (analog, shown in red in high-gain mode);
- LP when linear phase is on;
- the room name;
- the room EQ (Room Matching profile) and the voicing;
- the volume in dB, or MUTE / STANDBY;
- a volume bar.

Connection
------------

- Automatic discovery of the speakers on the network, or enter the IP address of either speaker.
- The plugin finds and follows the master speaker of the pair on its own.
- Automatic reconnection after a network drop or when the computer wakes from sleep.
- 100 % local: nothing goes through the internet.

REQUIREMENTS
------------

- Stream Deck software 7.1 or later (macOS 12+ or Windows 10+).
- Dutch & Dutch 8c speakers on the same local network as the computer (TCP port 8768).
- Tested on macOS with a Stream Deck +.

INSTALLATION
------------

1. Double-click 8C_streamdeck_TJ_V1.streamDeckPlugin.
2. Drag the actions from the 8C_streamdeck_TJ category onto your keys or dials.
3. Open the settings of any action. The status line should read "Connected to …". If it doesn't, click Search or type the IP address of one of your speakers.

DISCLAIMER
----------

This is an independent, unofficial plugin. It is not affiliated with, endorsed by, or supported by Dutch & Dutch. "Dutch & Dutch" and "8c" are trademarks of their respective owners and are used here only to describe the compatible hardware. Use at your own risk.
