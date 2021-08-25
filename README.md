# Dark Theme for [TeXstudio](https://texstudio.org/)

## Introduction
This theme is based on the theme provided by Master Prodigy user on YouTube. [Check out his amazing beginner LaTeX tutorials.](https://www.youtube.com/watch?v=TWRP_94eock&list=PLknjcpwMhvSgauKyhScPiQGW9H4V0EKj5)<br/><br/>
The math mode is intact and I tweaked some colors, mainly: put text to `#E9E9E9` ![#E9E9E9](https://via.placeholder.com/15/E9E9E9/000000?text=+), comments to  `#8FAE90` ![#8FAE90](https://via.placeholder.com/15/8FAE90/000000?text=+), keywords to `#FF5E2B` ![#FF5E2B](https://via.placeholder.com/15/FF5E2B/000000?text=+), extra-keywords to `#537E9A` ![#537E9A](https://via.placeholder.com/15/537E9A/000000?text=+), environment to `#C69500` ![#C69500](https://via.placeholder.com/15/C69500/000000?text=+) and ...<br/><br/>

## Before you start !!! 
Backup your TeXstudio settings.  
Go to menu bar -> Click in `Options`  -> Click on `Save Profile...`


## Dark IDE !!! 
Firstly, this repo was intended for helping to replace the text editor colors but as soon as I realize that TeXstudio have various dark IDE themes I decided to add it.<br/>
Basically you can only change the text editor colors or change the text editor colors + the IDE theme<br/>
To change to the dark IDE theme:
1. Go to menu bar -> Click in `Options`  -> Click on `Configure TeXstudio...`
2. In the Configure TeXstudio window clic on `General` tab.
3. In the `Appereance` group choose the style of your preference
4. In `Color Scheme` select `Modern - dark`
5. Clic OK, most times no need to restart TeXstudio
6. If TeXstudio does not look full dark repeat step 1 and continue with the next steps, if does restart TeXstudio
7. In the left-bottom corner mark the `Show Advanced Options` checkbox
8. In the `General` tab, in the `Appereance` group mark the `Ignore Most System Colors` checkbox
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
8. Go to menu bar -> Click in `Options`  -> Click on `Load Profile...` and select the file your *.txsprofile file.
9. Restart TeXstudio.
10. Enjoy!

## How to Install via .txsprofile file

This method could overwrite your shortcuts, recommended if you have not tweaked any configuration.

1. [Download the latest release.](https://github.com/hasecilu/Dark-TeXstudio/archive/master.zip)
2. Open TeXstudio.
3. Go to menu bar -> Click in `Options`  -> Click on `Load Profile...` and select the file "Dark-TeXstudio-text-editor.txsprofile" for change only the text editor colors or select the file "Full-Dark-TeXstudio.txsprofile" for change both IDE and text editor.
4. Restart TeXstudio.
5. Enjoy!

## Preview

#### Inserting commands and text
<details>
<summary>Colors</summary>

- background `#131313` ![#131313](https://via.placeholder.com/15/131313/000000?text=+)<br/>
- keyword `#FF5E2B` ![#FF5E2B](https://via.placeholder.com/15/FF5E2B/000000?text=+)<br/>
- structure `#00AAFF` ![#00AAFF](https://via.placeholder.com/15/00AAFF/000000?text=+)<br/>
- comment `#8FAE90` ![#8FAE90](https://via.placeholder.com/15/8FAE90/000000?text=+)<br/>
- text `#E9E9E9` ![#E9E9E9](https://via.placeholder.com/15/E9E9E9/000000?text=+)<br/>

</details>

![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/v1.1/Keywords_and_text.png)

#### Inserting a maths equations, using green and blue colors
<details>
<summary>Colors</summary>
  
- background `#131313` ![#131313](https://via.placeholder.com/15/131313/000000?text=+)<br/>
- keyword `#FF5E2B` ![#FF5E2B](https://via.placeholder.com/15/FF5E2B/000000?text=+)<br/>
- extra-keyword `#537E9A` ![#537E9A](https://via.placeholder.com/15/537E9A/000000?text=+)<br/>
- environment `#C69500` ![#C69500](https://via.placeholder.com/15/C69500/000000?text=+)<br/>
- structure `#00AAFF` ![#00AAFF](https://via.placeholder.com/15/00AAFF/000000?text=+)<br/>
- comment `#8FAE90` ![#8FAE90](https://via.placeholder.com/15/8FAE90/000000?text=+)<br/>
- math-delimiter `#399900` ![#399900](https://via.placeholder.com/15/399900/000000?text=+)<br/>
- math-keyword `#268BD2` ![#268BD2](https://via.placeholder.com/15/268BD2/000000?text=+)<br/>
- number `#33C7BB` ![#33C7BB](https://via.placeholder.com/15/33C7BB/000000?text=+)<br/>
- align-ampersand `#DC322F` ![#DC322F](https://via.placeholder.com/15/DC322F/000000?text=+)<br/>
- text `#E9E9E9` ![#E9E9E9](https://via.placeholder.com/15/E9E9E9/000000?text=+)<br/>
</details>

![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/v1.1/Math_mode.png)

#### Inserting a table + math mode, very colorful
<details>
<summary>Colors</summary>
  
- background `#131313` ![#131313](https://via.placeholder.com/15/131313/000000?text=+)<br/>
- keyword `#FF5E2B` ![#FF5E2B](https://via.placeholder.com/15/FF5E2B/000000?text=+)<br/>
- extra-keyword `#537E9A` ![#537E9A](https://via.placeholder.com/15/537E9A/000000?text=+)<br/>
- environment `#C69500` ![#C69500](https://via.placeholder.com/15/C69500/000000?text=+)<br/>
- structure `#00AAFF` ![#00AAFF](https://via.placeholder.com/15/00AAFF/000000?text=+)<br/>
- comment `#8FAE90` ![#8FAE90](https://via.placeholder.com/15/8FAE90/000000?text=+)<br/>
- math-delimiter `#399900` ![#399900](https://via.placeholder.com/15/399900/000000?text=+)<br/>
- math-keyword `#268BD2` ![#268BD2](https://via.placeholder.com/15/268BD2/000000?text=+)<br/>
- number `#33C7BB` ![#33C7BB](https://via.placeholder.com/15/33C7BB/000000?text=+)<br/>
- align-ampersand `#DC322F` ![#DC322F](https://via.placeholder.com/15/DC322F/000000?text=+)<br/>
- text `#E9E9E9` ![#E9E9E9](https://via.placeholder.com/15/E9E9E9/000000?text=+)<br/>
</details>
File available for [download](https://github.com/hasecilu/Dark-TeXstudio/blob/master/Greek_letters.tex). <br/>

![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/v1.1/Table.png)

#### Inserting a figure, references are in magenta
<details>
<summary>Colors</summary>
  
- background `#131313` ![#131313](https://via.placeholder.com/15/131313/000000?text=+)<br/>
- keyword `#FF5E2B` ![#FF5E2B](https://via.placeholder.com/15/FF5E2B/000000?text=+)<br/>
- extra-keyword `#537E9A` ![#537E9A](https://via.placeholder.com/15/537E9A/000000?text=+)<br/>
- environment `#C69500` ![#C69500](https://via.placeholder.com/15/C69500/000000?text=+)<br/>
- structure `#00AAFF` ![#00AAFF](https://via.placeholder.com/15/00AAFF/000000?text=+)<br/>
- referencePresent `#D70170` ![#D70170](https://via.placeholder.com/15/D70170/000000?text=+)<br/>
- referenceMissing `#FF859E` ![#FF859E](https://via.placeholder.com/15/FF859E/000000?text=+)<br/>
- referenceMultiple `#734967` ![#734967](https://via.placeholder.com/15/734967/000000?text=+)<br/>
- text `#E9E9E9` ![#E9E9E9](https://via.placeholder.com/15/E9E9E9/000000?text=+)<br/>
</details>

![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/v1.1/References.png)

For making easier to look at the errors & find/replace highlightnings I changed:<br/>
Line highlighting<br/>
- line:error   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-> from `#FFC9BF` ![#FFC9BF](https://via.placeholder.com/15/FFC9BF/000000?text=+) to `#FF8269` ![#FF8269](https://via.placeholder.com/15/FF8269/000000?text=+)
- line:warning -> from `#FFFABF` ![#FFFABF](https://via.placeholder.com/15/FFFABF/000000?text=+) to `#FFF569` ![#FFF569](https://via.placeholder.com/15/FFF569/000000?text=+)
- line:badbox  &nbsp;-> from `#BFD6FF` ![#BFD6FF](https://via.placeholder.com/15/BFD6FF/000000?text=+) to `#69A0FF` ![#69A0FF](https://via.placeholder.com/15/69A0FF/000000?text=+)<br/>

Search<br/>
- replacement  -> from `#FFDEDE` ![#FFDEDE](https://via.placeholder.com/15/FFDEDE/000000?text=+) to `#FF6969` ![#FF6969](https://via.placeholder.com/15/FF6969/000000?text=+)<br/>

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
Recommendation: For better readability try using colors in the scale of gray, the contrast should not be very high as in the black background & white foreground combination.<br/>
`#111111` ![#111111](https://via.placeholder.com/15/111111/000000?text=+)<br/>
`#EEEEEE` ![#EEEEEE](https://via.placeholder.com/15/EEEEEE/000000?text=+)<br/>
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
This method inverts colors of everything, including pictures and elements like boxes.
1. Go to menu bar -> Click in `Options`  -> Click on `Configure TeXstudio...`
2. In the Configure TeXstudio window clic on `Internal PDF Viewer` tab
3. In the `Paper Color` box choose a light gray color, `#D1CFCF` ![#D1CFCF](https://via.placeholder.com/15/D1CFCF/000000?text=+) for example
4. Switch to Windowed Viewer (right next to internal viewer `Close` button)
5. Compile and view the changes
6. In the Windowed Viewer go to menu bar, do `Configure` -> `Invert Colors`
7. Switch back to Embedded Viewer
When you open the pdf with an external pdf viewer you will see the typical black & white document.

![Dark theme + invert color](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Full_Dark3.png)

### Welcome to the dark side!

#### Interested in more dark profiles for TeXstudio?

[TexStudio Profiles](https://gitlab.com/adin/texstudio-profiles) repo from adin in gitlab have a few more themes. Check it out!
