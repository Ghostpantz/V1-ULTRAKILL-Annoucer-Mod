--THIS IS A MOD FOR THE ANNOUCER MOD-- BEPINEX

I added files to the annoucer mod which the link for the mod is https://www.nexusmods.com/ultrakill/mods/54

BIG DISCLAMER:
The dll and how it works belongs to this mod.


And also I am not that good of a modder.

This plays sound files that announce the style rank in overkill just like in DMC 5. The audio files are loaded in at runtime meaning you can swap them out with whatever you choose.

INSRTUCTIONS:

BEPINEX INSTALLATION:
1. Again, this requires BepInEx. Extract the bepinex zip inside steamapps\common\ULTRAKILL
2. Run Ultrakill to the title screen. This is required for BepInEx to intialize itself.
3. Extract the mod and place Announce.dll inside steamapps\common\ULTRAKILL\BepInEx\plugins
4. This is where it gets a little extra. Take the Audio folder (that is extracted from the mod zip file) and place it in steamapps\common\ULTRAKILL\ULTRAKILL_Data
5. Go into the Audio folder. So the full path is steamapps\common\ULTRAKILL\ULTRAKILL_Data\Audio and you should see 8 .wav files. These are the voicelines. You can replace them with whatever you want, just remember to rename the file so it matches what you are replacing.
6. Run the game. It should work fine.


MELONLOADER INSTALLATION:
1. Install MelonLoader. Im not sure if you need a specific version, but for testing I used V0.5.5
2. Boot up the game once so MelonLoader can initalize
3. Extract the mod and place MelonAnnouncer.dll inside steamapps\common\ULTRAKILL\Mods
4. This is where it gets a little extra. Take the Audio folder (that is extracted from the mod zip file) and place it in steamapps\common\ULTRAKILL\ULTRAKILL_Data
5. Place announcerConfig in the ULTRAKILL/Mods directory and ensure the announce.cfg file is in ULTRAKILL/Mods/announcerConfig
6. Go into the Audio folder. So the full path is steamapps\common\ULTRAKILL\ULTRAKILL_Data\Audio and you should see 8 .wav files. These are the voicelines. You can replace them with whatever you want, just remember to rename the file so it matches what you are replacing.
7. Run the game. It should work fine.


CONFIG INSTRUCTIONS BepInEx:

The config file is located in Bepinex/config/Announce.cfg

The two configs are cooldownTimer and announceDescendingRanks. cooldownTimer
will override announceDescendingRanks. To disable cooldownTimer change the value
to 0.

Also, the mod needs to run once to generate the config file, so launch the game once
with the mod before you try to edit the config file.

CONFIG INSTRUCTIONS Melon Loader:

The config file comes with the mod download because Melon Loader does not support configs
as far as I am aware. Place the announceConfig folder in the ULTRAKILL/Mods directory. IT
MUST BE HERE OR THE MOD WILL NOT WORK. You can then edit the configs in announceConfig/announce.cfg

The two configs are cooldownTimer and announceDescendingRanks. cooldownTimer
will override announceDescendingRanks. To disable cooldownTimer change the value
to 0.
