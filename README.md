# Steam-Local-Game-Importer
A utility to assist in importing non-steam games to the Steam library.

The Steam client allows users to add their own software to the launcher, but configuring it can be tedious. I worked to reverse-engineer the internal file structure to automate it from the command line, greatly short-cutting the workflow of adding multiple games.

Most of the files were simple enough, as JSON was rather easy to read and write. However, the “shortcuts.vdf” configuration file that handled the icon was not in a human-readable format. What I did notice, however, is that the various data bits were labeled in the file. Using that, I was able determine the exact structure of the file and give my program the ability to modify it.

This project took approximately 12 hours to complete.
