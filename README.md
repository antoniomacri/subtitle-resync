# Subtitle resync

A simple page to help resynchronize subtitles (i.e. srt files).

This utility can perform linear adjustments, that is:

 * shift subtitles by a specified amount of milliseconds;
 * adjust speed by a given ratio, useful when the subtitle is slower or faster than the video.

Currently, it has only been tested with `.srt` files.


## How to use it

The preferred way to adjust subtitles is to open the movie with a player capable of showing subtitles and moving them back and forth on the fly (e.g. VLC). Then:

 1. find the correct shift to apply to the first subtitle of the movie by shifting the subtitles back or forth as needed;
 2. similarly, find the shift to apply to the last subtitle of the movie (this may be the same as the first);
 3. use "Subtitle resync" to generate the resulting subtitle file by providing it with the input `.srt` and the two values determined.

In order to use "Subtitle resync", download the file `subtitle-resync.html` and open it with any browser or preview it [here](https://htmlpreview.github.io/?https://github.com/antoniomacri/subtitle-resync/blob/master/subtitle-resync.html).
