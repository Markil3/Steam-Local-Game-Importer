# Steam-Local-Game-Importer
A utility to assist in importing non-steam games to the Steam library.

The Steam client allows users to add their own software to the launcher, but configuring it can be tedious. I worked to reverse-engineer the internal file structure to automate it from the command line, greatly short-cutting the workflow of adding multiple games.

Most of the files were simple enough, as JSON was rather easy to read and write. However, the “shortcuts.vdf” configuration file that handled the icon was not in a human-readable format. What I did notice, however, is that the various data bits were labeled in the file. Using that, I was able determine the exact structure of the file and give my program the ability to modify it.

The initial build of this project took approximately 12 hours to complete. It took another 12 hours to reach a Windows-compatible build that can build a shortcuts file from scratch.

# A Message on the Future of this Application.
*To anyone who finds this useful.*

*I've recently taken on a new job, and, due to the demands of a full-time developer job, I will no longer be able to maintain this project. I've had a lot of fun with it, but continuing it for the future is simply unfeasible.*

*With that said, this application is fully open-source, and anyone is available to freely use it, modify it, or maintain their own copy. The only thing I require is that the copyright and license is preserved. I hope that you find this useful.*

*May God bless you all,*

*Markil 3*
