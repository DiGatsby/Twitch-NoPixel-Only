# Twitch-NoPixel-Only

Install: https://chrome.google.com/webstore/detail/twitch-nopixel-only/jebgklbgelliplemahghgiegfmcobfmk

Once installed, go to https://www.twitch.tv/directory/game/Grand%20Theft%20Auto%20V to use.

![Twitch NoPixel Only Screenshot](https://i.imgur.com/oZIOuVH.jpg)

---

This extension is specifically aimed at NoPixel viewers on Twitch. It has two primary features:
1. Filtering GTAV streams to exclude any non-NoPixel activity.
2. Automatically tagging/customizing NoPixel streams based on:
    1. the active character being played.
    2. the faction (if any) that the character belongs to.

### Filtering

##### "Does this only apply to the GTAV category on Twitch?"

Yes. This extension will only affect the GTAV page linked above. Any other Twitch pages, including "Following", will not be affected.

##### "How do you know if it's a NoPixel stream?"

There are two ways this is checked.

Firstly, this extension contains a large array of NoPixel streamers (currently 332) who are always included.

Secondly, if the stream title contains the term "NoPixel" or some variant of it, such as "NP" or "No Pixel", then the stream is included.
There are several exceptions to this filtering: Streams from a few other RP servers including TFRP and TRP are still included. However, there is no individual tagging/customizing done on these streams; all of them are coloured pale-blue.

### Tagging

##### "What is this 'tagging'?"

Each NoPixel stream has its title and streamer data examined to best deduce which character they are currently playing as. This includes checking for nicknames and faction names in their title. Based on this deduction, the stream is then tagged with the character name and the tag is coloured based on the faction this character belongs to.