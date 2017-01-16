'''
Version: 0.1.1
'''
[TOC](../README.md) > [Software](README.md) > GarageBand
```
┌┬┐┬─┐┌─┐┌─┐┌┬┐  ┬  ┬┌─┐┬─┐┌─┐┬┌─┐┌┐┌
 ││├┬┘├─┤├┤  │   └┐┌┘├┤ ├┬┘└─┐││ ││││
─┴┘┴└─┴ ┴└   ┴    └┘ └─┘┴└─└─┘┴└─┘┘└┘
```

[ROLI software](software.md), while generally well designed and offering numerous features, won't allow you to record your Seaboard performances. Apple's GarageBand software is one of the free options available on the Mac for Seaboard players to record their performances. There are however two very important steps, detailed in this guide, that *must* be taken to properly record the ROLI Seaboard with GarageBand.



# Recording your ROLI Seaboard to GarageBand on the Mac

## Connecting the Seaboard to GarageBand:

* Here's the [official ROLI guide](https://support.roli.com/article/using-the-seaboard-with-garageband/)
 * This guide presumes you know how to load audio plugins in GarageBand. For instance, enabling the ROLI Equator audio plugin in GarageBand is required to record the Seaboard's MIDI in GarageBand. Follow this link to [learn how to load the Seaboard Audio Plugin in GarageBand ](https://support.native-instruments.com/hc/en-us/articles/210292525-How-to-Insert-Native-Instruments-Plug-ins-in-GarageBand)
* While you can run the 'ROLI Dashboard' app... optional? Used for transposition, key and octave

## Using a GarageBand template for the Seaboard

Here's the GarageBand template I use to record my own Seaboard tracks: [GarageBand-SeaboardRISE49_template.band](TO DO INCLUDE)

* This template comes with the ROLI Seaboard RISE 49 audio plugin ready to start recording, but __you still need to manually turn off notes quantitisation every time you open the file__ to ensure accurate playback. [Help us request that this setting is saved within a .band file](TO-BE-CREATED) in order for the track to set the quantization automatically while loading the project
* To ensure you get the latest version of this file, if it gets improved and adapted to future versions of GarageBand, we suggest that you [fork this repository]() and clone your fork on your Mac with [GitHub Desktop]()
* Once you retrieved the file, lock it to ensure it doesn't get overwritten. You do that by selecting the file, press Command-i and enable the 'Lock' checkbox. After you open your template in GarageBand, you'll have to select 'Save as', see [the suggested nomenclature rules in yaml](TO CREATE)
* You can maximize the GarageBand display by clicking on the green dot at the top-left of the window, but in doing so you'll lose the ROLI Seaboard audio plugin anymore only GarageBand will be shown. This trick can be used to move from one view to the other

## Recording the Seaboard in GarageBand

* For an accurate playback, __it is crucial to disable the quantitisation of the notes__ in the ROLI Seaboard Audio Unit plugin __TO-DO:ADD-SCREENSHOT__, for which the default is set to 'double-croche'. Failure to update this setting means that unless one has followed the tempo on a whole track, the playback will be quite different from the original performance
* __If you use an external MIDI gear__, before you start recording, you must trigger your external MIDI instrument that needs to be set before the first note is played to ensure a message to set the value in GarageBand is sent and recorded  
* To record your Seaboard performance in an audio file (e.g. .mp3, .acc), I haven't found any better way than by purchasing [Rogue Amoeba's Audio Hijack](http://rogueamoeba.com/audiohijack/) software. [The Soundflower open source software](https://github.com/mattingalls/Soundflower) that should constitute a solution has not been updated since 2014 and failed to work properly for me. [If you're aware of a free and reliable solution, please let the community know here](LINK-TO-A-RELATED-ISSUE).. I've ask ROLI support and read GarageBand guides and blog entries without success. Apprently recording the Mac's audio through Quicktime works.
 * => If you previously recorded your performance in MIDI MPE in GarageBand, you can thus playback and record to an audio file this way

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
  WARNING: Make sure you systematically follow the instructions which invite you to disable note quantitisation. This is important otherwise playback will be different from the initial performance.


## Tips

### Playing and recording two Seaboard presets at the same time

Ready to explore new sound combinations? Play a Seaboard preset from the AudioUnit track in GarageBand and listen to a second preset over the first one by launching the Equator software that was provided to you with the Seaboard. You can select two different presets and play the ROLI Seaboard with awesome sound combinations.



# Recording the ROLI Seaboard in GarageBand on the iPad and iPhone

No documented so far. [You can contribute](../contribute.md) to this section of this guide.


# Updates to this documentation

Learn here [how to ensure you don't miss improvements to this guide](TO-DO)

# Life happens

This page has been useful to you and you can spend a few more minutes? I'm preparing an album of improvised ROLI Seaboard RISE 49 solos. It will be available on http://satri.bandcamp.com. You can have an idea of my playing style thanks to my [previous albums of improvised Animoog and Model 15 solos](http://animoog.org/satri), which you will find [for free at the same place](http://satri.bandcamp.com).


# TO-DO

* TO-DO : Cut a git release once the way to record the audio from a track recorded in MPE MIDI in GarageBand
* Publish this on Animoog.org with the link to Github page for current version
