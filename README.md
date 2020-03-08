# mconfetti
This is a standalone executable java jar file that will accept as input a folder containing mp4 files and produces a ".mlt" file.
The output file can be opened in Shotcut and will produce a single play list with progressively incremented segments of a 
chosen length. The input files are selected at random from the list of valid files in the selected folder, and the order of the output segments is also random.

Requirements: 
You need ffmpeg (free) installed and configured to run in any folder. This will involve adding ffmpeg to your default path
list for programs.
You need shotcut (free).
This should work on a windows computer, and may work on a mac. I've not tested it.
No warranties or guarantees of performance are made or implied.
