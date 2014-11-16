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
