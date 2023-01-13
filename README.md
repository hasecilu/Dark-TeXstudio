# Dark Theme for [TeXstudio](https://texstudio.org/)

## Introduction

This theme is based on the theme provided by [Master Prodigy](https://www.youtube.com/@masterprodigy9441) user on YouTube.  
The math mode is intact and I tweaked some colors, mainly: put text to `#E9E9E9` ![#E9E9E9](https://placehold.co/15x15/E9E9E9/E9E9E9.png), comments to  `#8FAE90` ![#8FAE90](https://placehold.co/15x15/8FAE90/8FAE90.png), keywords to `#FF5E2B` ![#FF5E2B](https://placehold.co/15x15/FF5E2B/FF5E2B.png), extra-keywords to `#537E9A` ![#537E9A](https://placehold.co/15x15/537E9A/537E9A.png), environment to `#C69500` ![#C69500](https://placehold.co/15x15/C69500/C69500.png) ...

## Before you start !!!

Backup your TeXstudio settings.   
Go to menu bar -> Click in `Options`  -> Click on `Save Profile...`


## Dark IDE !!!

Firstly, this repo was intended for only helping to replace the text editor colors but as soon as I realize that `TeXstudio` have various dark IDE themes I decided to add it.  
Basically you could only change the text editor colors or change the text editor colors + the IDE theme  
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

## How to Install via *.txsprofile file

This method could overwrite your shortcuts, recommended if you have not tweaked any configuration.

1. [Download the latest release.](https://github.com/hasecilu/Dark-TeXstudio/archive/master.zip)
2. Open TeXstudio.
3. Go to menu bar -> Click in `Options`  -> Click on `Load Profile...` and select the file "Dark-TeXstudio-text-editor.txsprofile" for change only the text editor colors or select the file "Full-Dark-TeXstudio.txsprofile" for change both IDE and text editor.
4. Restart TeXstudio.
5. Enjoy!

## Preview

#### Inserting commands and text

<details>
<summary>Click to view/hide colors</summary>

- background `#131313` ![#131313](https://placehold.co/15x15/131313/131313.png)
- keyword `#FF5E2B` ![#FF5E2B](https://placehold.co/15x15/FF5E2B/FF5E2B.png)
- structure `#00AAFF` ![#00AAFF](https://placehold.co/15x15/00AAFF/00AAFF.png)
- comment `#8FAE90` ![#8FAE90](https://placehold.co/15x15/8FAE90/8FAE90.png)
- text `#E9E9E9` ![#E9E9E9](https://placehold.co/15x15/E9E9E9/E9E9E9.png)

</details>

![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/v1.1/Keywords_and_text.png)

#### Inserting math equations, using green and blue colors

<details>
<summary>Click to view/hide colors</summary>
  
- background `#131313` ![#131313](https://placehold.co/15x15/131313/131313.png)
- keyword `#FF5E2B` ![#FF5E2B](https://placehold.co/15x15/FF5E2B/FF5E2B.png)
- extra-keyword `#537E9A` ![#537E9A](https://placehold.co/15x15/537E9A/537E9A.png)
- environment `#C69500` ![#C69500](https://placehold.co/15x15/C69500/C69500.png)
- structure `#00AAFF` ![#00AAFF](https://placehold.co/15x15/00AAFF/00AAFF.png)
- comment `#8FAE90` ![#8FAE90](https://placehold.co/15x15/8FAE90/8FAE90.png)
- math-delimiter `#399900` ![#399900](https://placehold.co/15x15/399900/399900.png)
- math-keyword `#268BD2` ![#268BD2](https://placehold.co/15x15/268BD2/268BD2.png)
- number `#33C7BB` ![#33C7BB](https://placehold.co/15x15/33C7BB/33C7BB.png)
- align-ampersand `#DC322F` ![#DC322F](https://placehold.co/15x15/DC322F/DC322F.png)
- text `#E9E9E9` ![#E9E9E9](https://placehold.co/15x15/E9E9E9/E9E9E9.png)
</details>

![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/v1.1/Math_mode.png)

#### Inserting a table + math mode, very colorful

File available to [download](https://github.com/hasecilu/Dark-TeXstudio/blob/master/Greek_letters.tex). 

<details>
<summary>Click to view/hide colors</summary>
  
- background `#131313` ![#131313](https://placehold.co/15x15/131313/131313.png)
- keyword `#FF5E2B` ![#FF5E2B](https://placehold.co/15x15/FF5E2B/FF5E2B.png)
- extra-keyword `#537E9A` ![#537E9A](https://placehold.co/15x15/537E9A/537E9A.png)
- environment `#C69500` ![#C69500](https://placehold.co/15x15/C69500/C69500.png)
- structure `#00AAFF` ![#00AAFF](https://placehold.co/15x15/00AAFF/00AAFF.png)
- comment `#8FAE90` ![#8FAE90](https://placehold.co/15x15/8FAE90/8FAE90.png)
- math-delimiter `#399900` ![#399900](https://placehold.co/15x15/399900/399900.png)
- math-keyword `#268BD2` ![#268BD2](https://placehold.co/15x15/268BD2/268BD2.png)
- number `#33C7BB` ![#33C7BB](https://placehold.co/15x15/33C7BB/33C7BB.png)
- align-ampersand `#DC322F` ![#DC322F](https://placehold.co/15x15/DC322F/DC322F.png)
- text `#E9E9E9` ![#E9E9E9](https://placehold.co/15x15/E9E9E9/E9E9E9.png)
</details>

![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/v1.1/Table.png)

#### Inserting a figure, references are in magenta

<details>
<summary>Click to view/hide colors</summary>
  
- background `#131313` ![#131313](https://placehold.co/15x15/131313/131313.png)
- keyword `#FF5E2B` ![#FF5E2B](https://placehold.co/15x15/FF5E2B/FF5E2B.png)
- extra-keyword `#537E9A` ![#537E9A](https://placehold.co/15x15/537E9A/537E9A.png)
- environment `#C69500` ![#C69500](https://placehold.co/15x15/C69500/C69500.png)
- structure `#00AAFF` ![#00AAFF](https://placehold.co/15x15/00AAFF/00AAFF.png)
- referencePresent `#D70170` ![#D70170](https://placehold.co/15x15/D70170/D70170.png)
- referenceMissing `#FF859E` ![#FF859E](https://placehold.co/15x15/FF859E/FF859E.png)
- referenceMultiple `#734967` ![#734967](https://placehold.co/15x15/734967/734967.png)
- text `#E9E9E9` ![#E9E9E9](https://placehold.co/15x15/E9E9E9/E9E9E9.png)
</details>

![Preview](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/v1.1/References.png)

For making easier to look at the errors & find/replace highlightnings I changed:  
Line highlighting

- line:error   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-> from `#FFC9BF` ![#FFC9BF](https://placehold.co/15x15/FFC9BF/FFC9BF.png) to `#FF8269` ![#FF8269](https://placehold.co/15x15/FF8269/FF8269.png)
- line:warning -> from `#FFFABF` ![#FFFABF](https://placehold.co/15x15/FFFABF/FFFABF.png) to `#FFF569` ![#FFF569](https://placehold.co/15x15/FFF569/FFF569.png)
- line:badbox  &nbsp;-> from `#BFD6FF` ![#BFD6FF](https://placehold.co/15x15/BFD6FF/BFD6FF.png) to `#69A0FF` ![#69A0FF](https://placehold.co/15x15/69A0FF/69A0FF.png)

Search

- replacement  -> from `#FFDEDE` ![#FFDEDE](https://placehold.co/15x15/FFDEDE/FFDEDE.png) to `#FF6969` ![#FF6969](https://placehold.co/15x15/FF6969/FF6969.png)

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

We can change background and foreground colors in our document using the the [xcolor package](https://www.ctan.org/pkg/xcolor).  
Type `texdoc xcolor` in your terminal for help.  
Note that this method does not inverts colors of hyperlinks, pictures and some other graphical elements like boxes.  
Recommendation: For better readability try using colors in the scale of gray that are not so far apart of each other, the contrast should not be very high as in the black background & white foreground combination.

- `#111111` ![#111111](https://placehold.co/15x15/111111/111111.png)
- `#EEEEEE` ![#EEEEEE](https://placehold.co/15x15/EEEEEE/EEEEEE.png)

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
If you just want the internal pdf viewer does the job follow the next steps, thanks to ZeliTheZealot for the advice.  
This method inverts colors of **everything**.

1. Go to menu bar -> Click in `Options`  -> Click on `Configure TeXstudio...`
2. In the Configure TeXstudio window clic on `Internal PDF Viewer` tab
3. In the `Paper Color` box choose a light gray color, `#D1CFCF` ![#D1CFCF](https://placehold.co/15x15/D1CFCF/D1CFCF.png) for example
4. Switch to Windowed Viewer (right next to internal viewer `Close` button)
5. Compile and view the changes
6. In the Windowed Viewer go to menu bar, do `Configure` -> `Invert Colors`
7. Switch back to Embedded Viewer

When you open the pdf with an external pdf viewer you will see the typical black & white document.

![Dark theme + invert color](https://raw.github.com/hasecilu/Dark-TeXstudio/master/images/Full_Dark3.png)

### Welcome to the dark side!

#### Interested in more dark profiles for TeXstudio?

[TexStudio Profiles](https://gitlab.com/adin/texstudio-profiles) repo from adin in gitlab have a few more themes. Check it out!

Also check the [Tips and Tricks](https://github.com/texstudio-org/texstudio/wiki/Tips-And-Tricks#dark-mode) section in the TeXstudio wiki.
