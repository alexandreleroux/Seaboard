````
┌┬┐┬─┐┌─┐┌─┐┌┬┐  ┬  ┬┌─┐┬─┐┌─┐┬┌─┐┌┐┌
 ││├┬┘├─┤├┤  │   └┐┌┘├┤ ├┬┘└─┐││ ││││
─┴┘┴└─┴ ┴└   ┴    └┘ └─┘┴└─└─┘┴└─┘┘└┘

 _____                    __   _                                   _                 
|  __ \                  / _| | |                                 (_)                
| |  | |  _ __    __ _  | |_  | |_    __   __   ___   _ __   ___   _    ___    _ __  
| |  | | | '__|  / _` | |  _| | __|   \ \ / /  / _ \ | '__| / __| | |  / _ \  | '_ \
| |__| | | |    | (_| | | |   | |_     \ V /  |  __/ | |    \__ \ | | | (_) | | | | |
|_____/  |_|     \__,_| |_|    \__|     \_/    \___| |_|    |___/ |_|  \___/  |_| |_|

```

# Connecting the ROLI to GarageBand:

* Here's the [official guide](https://support.roli.com/article/using-the-seaboard-with-garageband/)
* This guide presumes you know how to load audio plugins in GarageBand. For instance, enabling the ROLI Equator audio plugin in GarageBand is required to record the Seaboard's MIDI in GarageBand. [Follow this link to learn how you](https://support.native-instruments.com/hc/en-us/articles/210292525-How-to-Insert-Native-Instruments-Plug-ins-in-GarageBand)
* For an accurate playback, it is crucial to disable the quantitisation of the notes, for which the default is set to 'double-croche'. Failure to update this setting means that unless one has followed the tempo on a whole track, the playback will be quite different from the original performance
* Here's the GarageBand template I use to record my own Seaboard tracks: [GarageBand-SeaboardRISE49_template.band](TO DO INCLUDE)
 * This template comes with the ROLI Seaboard RISE 49 audio plugin ready to start recording, but __you still need to manually turn off notes quantitisation every time you open the file__ to ensure accurate playback. [Help us request that this setting is saved within a .band file](TO-BE-CREATED) in order for the track to set the quantization automatically while loading the project
 * To ensure you get the latest version of this file, if it gets improved and adapted to future versions of GarageBand, we suggest that you [fork this repository]() and clone your fork on your Mac with [GitHub Desktop]()
 * Once you retrieved the file, lock it to ensure it doesn't get overwritten. You do that by selecting the file, press Command-i and enable the 'Lock' checkbox. After you open your template in GarageBand, you'll have to select 'Save as', see [the suggested nomenclature rules in yaml](TO CREATE)
* You can maximize the GarageBand display by clicking on the green dot at the top-left of the window, but in doing so you'll lose the ROLI Seaboard audio plugin anymore only GarageBand will be shown. This trick can be used to move from one view to the other
* Before you start recording, you must trigger your external MIDI instrument that needs to be set before the first note is played to ensure a message to set the value in GarageBand is sent and recorded  
* To record your Seaboard performance in an audio file (e.g. .mp3, .acc), I haven't found any better way than by purchasing [Rogue Amoeba's Audio Hijack](http://rogueamoeba.com/audiohijack/) software. [The Soundflower open source software](https://github.com/mattingalls/Soundflower) that should constitute a solution has not been updated since 2014 and failed to work properly for me. [If you're aware of a free and reliable solution, please let the community know here](LINK-TO-A-RELATED-ISSUE)    
 * If you previously recorded your performance in MIDI MPE in GarageBand, you can thus playback and record to an audio file this way


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


TO-DO : Cut a git release once the way to record the audio from a track recorded in MPE MIDI in GarageBand
