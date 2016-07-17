# CymaSpace Arts & Accessibility Event Series
Files and Tech Resources for CymaSpace Arts &amp; Accessibility Event Series

Hello Artists!
Welcome to the centralized Github repository to store assets and files for the Arts & Accessibility Event Series. This system is used to allow us to easily keep files in sync as well as to integrate with our automated Creative Captioning display system. If you are not familiar with Github, don't worry, a CymaSpace technician is available to work with you and ensure you can provide everything needed for a successful event.

CREATIVE CAPTIONING SYSTEM
For most artists who have word-based lyrical or poetical content, the Creative Captioning System is a very important feature that in addition to providing ASL Interpreters with study materials, will allow the projection to be automated and easily displayed during events themselves. Please take a look inside one of the existing artist directors such as Artists/Giddy Up to see their lyrics.txt file and how it is formatted. For most part it is straight forward, here is an example:

SONG TITLE 1
First line to be projected
Second line to be projected
Third line to be projected
Fourth line to be projected.

Firth line to be projected
Sixth line to be projected
Seventh line to be projected
Eigth line to be projected.

============================

SONG TITLE 2
First line to be projected
Second line to be projected
.... etc


Via this formatting, the Creative Captioning System uses the modular patching software vuo.org to automatically parse your lyric.txt file, displaying only one line at a time. The projectionist (ideally someone familiar with your work) can easily move forward and backward through each line by pressing the forward and arrow keys on the computer being used for projection.
The ======= line is a divider which helps the system know where to break-up your performances into songs/sets.

The system will also automatically assigning each song to a number key on the keyboard to easily allow the projectionist to skip to the beginning of the song which can be handy for changes to the set or to find their place. i.e. keyboard key "1" will jump to the first line of SONG TITLE 1, keyboard key "2" will jump to the first line of SONG TITLE 2 etc.

Vuo Notes:
When creating custom nodes from the /Vuo Templates/.../modules directory, Vuo will want to relocate the files out of your Github repo, ensure that a copy remains in Github when importing to Vuo!
