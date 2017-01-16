[TOC](../README.md) > [Software](README.md) > Animoog
```
┌┬┐┬─┐┌─┐┌─┐┌┬┐  ┬  ┬┌─┐┬─┐┌─┐┬┌─┐┌┐┌
 ││├┬┘├─┤├┤  │   └┐┌┘├┤ ├┬┘└─┐││ ││││
─┴┘┴└─┴ ┴└   ┴    └┘ └─┘┴└─└─┘┴└─┘┘└┘
```

# Playing Animoog with the ROLI Seaboard RISE

Moog Music's [Animoog](https://itunes.apple.com/ca/app/animoog/id471638724?mt=8) is a popular and award-winning iPad instrument. If you want to use the ROLI Seaboard to play Animoog, here's what you need to know.

# MIDI configuration

The Seaboard can be connected to Animoog directly from Bluetooth.

## Mandatory configuration

Mandatory configuration requirements
  - Set MIDI Channel to 'MPE'
  - Set Pitch Bend range to '48'

```
           _    _                      _               
          | |  | |                    (_)              
          | |  | |  __ _  _ __  _ __   _  _ __    __ _
          | |/\| | / _` || '__|| '_ \ | || '_ \  / _` |
          \  /\  /| (_| || |   | | | || || | | || (_| |
           \/  \/  \__,_||_|   |_| |_||_||_| |_| \__, |
                                                 __/ |
                                                |___/
```
  WARNING: you MUST use this configuration to ensure the ROLI Seaboard expressive capabilities as best rendered in Animoog.

[source](http://forum.moogmusic.com/viewtopic.php?f=13&t=24292&p=160898#p160898):
  There have been no changes, polyphonic legato MIDI messages are handled the same in Animoog and Model 15 and they're compatible, they can control each-other. Both Animoog and Model 15 support incoming MPE messages, so they're great synths for per-note control. We're waiting for the MPE spec to be finalized to evaluate if we can add output MPE support.


## Multiple input MIDI sources

If you want to leverage additional input MIDI devices, because Animoog don't support multiple input MIDI sources, you'll need an app to merge the signal. I use [Kymatica's AUM app](http://kymatica.com/Software/AUM) and [configure its MIDI Matrix](http://kymatica.com/aum/help.html#toc66) to send both the ROLI Seaboard MIDI and my additional devices to the 'Network Session 1' and 'Animoog [virtual]' destinations and then the signal of multiple MIDI controllers can be seen in Animoog.


# Other Animoog references

* [Animoog.org](http://animoog.org): community-driven website with lists over 2,500 Animoog presets and over 4,000 timbres, lots of them free
