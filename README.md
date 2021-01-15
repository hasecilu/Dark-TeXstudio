# Dark Theme for [TeXstudio](https://texstudio.org/)

## Introduction
This theme is based on the theme provided by Master Prodigy user on YouTube. [Check out his amazing LaTeX tutorials.](https://www.youtube.com/watch?v=TWRP_94eock&list=PLknjcpwMhvSgauKyhScPiQGW9H4V0EKj5)<br/><br/>
The math mode is intact and I tweaked some colors, mainly: put text to white, comments to green, keywords to orange, extra-keywords to blue, environment to yellow and ...<br/><br/>
For making easier to look at the errors & find/replace highlightnings I changed:<br/>
Line highlighting<br/>
   line:error   -> from HSV(10,64,255) #FFC9BF to HSV(10,150,255) #FF8269<br/>
   line:warning -> from HSV(56,64,255) #FFFABF to HSV(56,150,255) #FFF569<br/>
   line:badbox  -> from HSV(218,64,255) #BFD6FF to HSV(218,150,255) #69A0FF<br/>
Search<br/>
   replacement  -> from HSV(0,33,255) #FFDEDE to HSV(0,150,255) #FF6969<br/>


## Before you start !!! 
Backup your TeXstudio settings.  
Go to menu bar -> Click in 'Options'  -> Click on 'Save Profile...'


## Dark IDE !!! 
Firstly, this repo was intended for helping to replace the text editor colors but as soon as I realize that TeXstudio have various dark IDE themes I decided to add it.<br/>
Basically you can only change the text editor colors or change the text editor colors + the IDE theme<br/>
To change to the dark IDE theme:
1. Go to menu bar -> Click in 'Options'  -> Click on 'Configure TeXstudio...'
2. In the Configure TeXstudio window clic on 'General' tab.
3. In the 'Appereance' group choose the style of your preference
4. In 'Color Scheme' select 'Modern - dark'
5. Clic OK, most times no need to restart TeXstudio
6. If TeXstudio does not look full dark repeat step 1 and continue with the next steps, if does restart TeXstudio
7. In the left-bottom corner mark the 'Show Advanced Options' checkbox
8. In the 'General' tab, in the 'Appereance' group mark the 'Ignore Most System Colors' checkbox
9. Restart TeXstudio

Now we can proceed to change the text editor colors.


## How to Install via copying text to file (recommended)

1. [Download the latest release.](https://github.com/hasecilu/Dark-TeXstudio/archive/master.zip)
2. Open TeXstudio.
3. Export your actual profile (same procedure as backup).
4. Open your *.txsprofile file on any text editor.
5. Find the "[formats]" string or "[formatsdark]" string if applies.
6. Copy the content from "Dark-TeXstudio.txt" under the "[formats]"/"[formatsdark]" string, if it there is any text under overwrite it.
7. Save the file.
8. Go to menu bar -> Click in 'Options'  -> Click on 'Load Profile...' and select the file your *.txsprofile file.
9. Restart TeXstudio.
10. Enjoy!

## How to Install via .txsprofile file

This method could overwrite your shortcuts, recommended if you have not tweaked any configuration.

1. [Download the latest release.](https://github.com/hasecilu/Dark-TeXstudio/archive/master.zip)
2. Open TeXstudio.
3. Go to menu bar -> Click in 'Options'  -> Click on 'Load Profile...' and select the file "Dark-TeXstudio-text-editor.txsprofile" for change only the text editor colors or select the file "Full-Dark-TeXstudio.txsprofile" for change both IDE and text editor.
4. Restart TeXstudio.
5. Enjoy!

## Preview

#### Inserting a text, keywords are orange
![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Text.png)
#### Inserting a maths equations, using green and blue colors
![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Maths.png)
#### Inserting a table + math mode, very colorful
File available for download. <br/>
![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Table.png)
#### Inserting a figure, references are in magenta
![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Figure.png)

## Comparison: Light IDE theme vs Dark IDE theme

#### Light theme
![Light theme](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Light.png)
#### Dark theme
![Dark theme](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Dark.png)

### Dark theme + black page color
There are 2 methods: 
1. Creating the document itself with a dark page color and light font color
2. Making the internal pdf viewer invert colors.
#### Change colors from source
We can change colors in our document using the the [xcolor package](https://www.ctan.org/pkg/xcolor).<br/>
Type `texdoc xcolor` in your terminal for help.<br/>
This method does not inverts colors of pictures and some elements like boxes.<br/>
Recommendation: For better readability try using colors in the scale of gray, the contrast should not be very high as in the black background & white foreground combination.
```latex
% To join the dark side add these lines to the preamble (before \begin{document})
\usepackage{xcolor}
\pagecolor[HTML]{111111} % dark color
\color[HTML]{EEEEEE} % light color
```
At the end you will need to comment those lines to get a typical black & white document.

![Dark theme + dark page color](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Full_Dark2.png)

#### Invert colors with built-in pdf viewer
<!--- Recommendation by ZeliTheZealot --->
If you just want the internal pdf viewer does the job follow the next steps, thanks to ZeliTheZealot for the advice.<br/>
This method inverts colors of everything, including pictures and some elements like boxes.
1. Go to menu bar -> Click in 'Options'  -> Click on 'Configure TeXstudio...'
2. In the Configure TeXstudio window clic on 'Internal PDF Viewer' tab
3. In the 'Paper Color' box choose a light gray color, #D1CFCF for example
4. Switch to Windowed Viewer (right next to internal viewer 'Close' button)
5. Compile and view the changes
6. In the Windowed Viewer go to menu bar, do Configure -> Invert Colors
7. Switch back to Embedded Viewer
When you open the pdf with an external pdf viewer you will see the typical black & white document.

![Dark theme + invert color](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Full_Dark3.png)

### Welcome to the dark side!
