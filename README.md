# My Lua scripts:

## after-playback
Sends commands to nircmd (windows only) on playback finish. Commands include sleep, hibernate, shutdown, lock. Full list is in the file

## change-refresh

Uses nircmd (windows only) to change the resolution and refresh rate of the monitor to match the playing video.

Saves the original monitor resolution and reverts changes on exit and when hotkey is pressed.

Full description in file.

## coverart
Automatically scans the directory of the currently loaded file and loads any valid cover art into mpv as additional video tracks.
Has options for selecting what file names and types are considered valid.

## cycle-commands
Cycles through a series of commands on a keypress. Each iteration of the cycle can contain as many commands as one wants. Syntax details are at the top of the file.

## cycle-profile
Cycles through a list of profiles sent via a script message and prints the profile-desc to the OSD. More details at the top of the file

## display-profiles
Automatically applies profiles when the mpv window is moved to a new display

## editions-notification
Prints a message on the OSD if editions are found in the file, and temporarily switches the osd-playing-message to the editions-list property when switching. This makes it easier to tell the number and names while navigating editions.

## ftp-compat
Changes some options when using the ftp protocol for better user experience

## keep-session
Automatically saves the current playlist on exit and allows the user to reload it next time they boot mpv

## music-mode
Switches to a music profile when an audio file is being played and switches back when a non-audio file is played

## onedrive-hook
Automatically converts a onedrive share link into a direct path which mpv can play, Windows only.

## playlist-shuffle
shuffles the playlist and moves the current file to the start of the playlist

## show-errors
Prints error messages onto the OSD

## syncplay-compat
Changes some settings to work well with [Syncplay](https://syncplay.pl/). Currently designed to provide support for local playlists.

# Other scripts

[betterchapters](https://github.com/mpv-player/mpv/issues/4738#issuecomment-321298846)