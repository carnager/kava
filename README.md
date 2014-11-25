# kʌvə - create wallpaper from current mpd album cover

kʌvə uses imagemagick to generate a wallpaper with an image of current album
playing in mpd embedded into.

## Dependencies:

* imagemagick
* get-cover (https://github.com/DirectorX/get-cover)
* mpc
* wget

## Install

Just install the needed dependencies and clone this repository
Then copy config.example to $HOME/.config/kava/config
and edit it to your liking

## Usage:

Simply run "kava" - it will change background on each track change.
run "kava reset" to delete current artwork and replace it with a newly downloaded one

## CAUTION!!!
Right now this script will delete folder.jpg files, because whatever
software downloaded these, chose extremly low quality files.
Instead I re-download covers for these.
Also i convert cover.jpg to cover.png, because transparency is needed for
this particular use-case.
While this could be done in a termporary file, I just chose to just convert
the actual cover file. This way the conversion is a one-time thing.
