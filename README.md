# mconfetti
This is a standalone executable java jar file that will accept as input a folder containing mp4, avi, jpeg and png files 
and produces a shotcut ".mlt" file. The output file can be opened in Shotcut and will produce a single play list 
with the selected clips combined.

By default, the application produces progressively incremented segments of a 
chosen length which are selected randomly from the input files. The order of the output segments is also random.
Optionally, you can chose to join clips intact, and either have them appear in random or alphabetical order. To 
use all the clips in a folder, specify a larger number of desired clips and the application will use all available.
Instead of a single time segment length, users can also specify a text file containing one number of seconds per line.
The app will use these values to set segment lengths and loop through them. This does not apply to joining whole clips.

Requirements: 
You need ffmpeg (free) installed and configured to run in any folder. This will involve adding ffmpeg to your default path
list for programs.
You need shotcut (free).
This should work on a windows computer, and may work on a mac. I've not tested it.
No warranties or guarantees of performance are made or implied.

Log:

3-14-202: Added support for selection of a text file containing time values for segment lengths.

3-12-2020: Added help feature and support for image files.
