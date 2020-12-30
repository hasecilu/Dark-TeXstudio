# Dark Theme for [TeXstudio](https://texstudio.org/)

### Introduction
This theme is based on the theme provided by Master Prodigy user on YouTube. [Check out his amazing LaTeX tutorials.](https://www.youtube.com/watch?v=TWRP_94eock&list=PLknjcpwMhvSgauKyhScPiQGW9H4V0EKj5)<br/>
I tweaked some colors, mainly: put text to white, comments to green, keywords to orange, extra-keywords to blue, environment to yellow and ...
For making easier to look at the errors & find/replace highlightnings I changed:
Line highlighting
  line:error -> from HSV(10,64,255) to HSV(10,150,255)
  line:warning -> from HSV(56,64,255) to HSV(56,150,255)
  line:badbox -> from HSV(218,64,255) to HSV(218,150,255)
Search
  replacement -> from HSV(0,33,255) to HSV(0,150,255)


### Before you start !!! 
Backup your TeXstudio settings.  
Go to menu bar -> Click in 'Options'  -> Click on 'Save Profile...'

### How to Install via copying text to file (recommended)

1. [Download the latest release.](https://github.com/hasecilu/Dark-TeXstudio/archive/master.zip)
2. Open TeXstudio.
3. Export your actual profile (same procedure as backup).
4. Open your .txsprofile file on any text editor.
5. Find the "[formats]" string.
6. Copy the content from "Dark-TeXstudio.txt" under the "[formats]" string, if it there is any text under overwrite it.
7. Save the file.
8. Go to menu bar -> Click in 'Options'  -> Click on 'Load Profile...' and select the file your .txsprofile file.
9. Restart TeXstudio.
10. Enjoy!

### How to Install via .txsprofile file

This method could overwrite your shortcuts, recommended if you have not tweaked any configuration.

1. [Download the latest release.](https://github.com/hasecilu/Dark-TeXstudio/archive/master.zip)
2. Open TeXstudio.
3. Go to menu bar -> Click in 'Options'  -> Click on 'Load Profile...' and select the file "Dark-TeXstudio.txsprofile".
4. Restart TeXstudio.
5. Enjoy!

### Preview

#### Inserting a text, keywords are orange
![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Text.png)
#### Inserting a maths equations, using green and blue colors
![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Maths.png)
#### Inserting a table + math mode, very colorful
File available for download. 

![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Table.png)
#### Inserting a figure, references are in magenta
![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Figure.png)
