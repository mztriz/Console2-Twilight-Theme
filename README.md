Console2-Twilight-Theme
=======================

A Twilight theme for [Console2] (http://sourceforge.net/projects/console/)

<img src="https://raw.github.com/mztriz/Console2-Twilight-Theme/master/preview.png">

Installing the theme
----
The easiest way to install this theme is to edit your `console.xml` file found in your Console2 directory.

Open `console.xml` in your favorite text editor and erase all of the text between the `<color></color>` found tags near the top of the file.

After its been erased paste the following between the `<color></color>` tags:
`````xml
<color id="0" r="20" g="20" b="20"/>
<color id="1" r="207" g="106" b="76"/>
<color id="2" r="131" g="144" b="97"/>
<color id="3" r="206" g="168" b="105"/>
<color id="4" r="117" g="135" b="166"/>
<color id="5" r="155" g="133" b="157"/>
<color id="6" r="5" g="166" b="179"/>
<color id="7" r="215" g="215" b="215"/>
<color id="8" r="102" g="102" b="102"/>
<color id="9" r="117" g="135" b="166"/>
<color id="10" r="89" g="164" b="77"/>
<color id="11" r="10" g="230" b="230"/>
<color id="12" r="216" g="10" b="82"/>
<color id="13" r="230" g="0" b="139"/>
<color id="14" r="225" g="238" b="62"/>
<color id="15" r="230" g="230" b="230"/>
`````


My console.xml file is here for reference:
[console.xml] (https://github.com/mztriz/Console2-Twilight-Theme/blob/master/console.xml)
You probably don't want to just replce yours with mine as it will overwrite all of your other custom settings. 

Settings
---
### Colors
<img src="https://raw.github.com/mztriz/Console2-Twilight-Theme/master/colors.png">

Custom LSCOLORS for cgywin `.bashrc`: 
`CLICOLOR=1 # Enables color in the terminal bash shell export
LSCOLORS=gxfxcxdxbxegedabagacad # Sets up the color scheme for list export
export LSCOLORS
export TERM=xterm-color # Enables color for iTerm
alias ls='ls --color'`

### Font
Inconsolata by Raph Levien.
http://code.google.com/p/googlefontdirectory/source/browse/inconsolata/