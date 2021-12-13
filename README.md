# plastic-joplin-theme
Theme for Joplin that utilises the standard dark theme and essentially a restyling of [Ohmine-Dark-Theme-For-Joplin](https://github.com/Nacandev/Ohmine-Dark-Theme-For-Joplin). A big thankyou to Nacandev for creating such an amazingly in-depth repository for me to learn from. Using this theme I styled it to a colour scheme that better suits myself and my needs. The colour scheme applied is also borrowed extensively from the [Plastic](https://marketplace.visualstudio.com/items?itemName=will-stone.plastic) theme for VSCode. Having enjoyed both these themes, I took upon blending them together for a vibrant theme that isn't vexing.



## Fonts

### [Montserrat](https://fonts.google.com/specimen/Montserrat)
Is the Sans font we are going with

### [Fira Code](https://github.com/tonsky/FiraCode)
Is the monospaced font.

### [Work Sans](https://fonts.google.com/specimen/Work+Sans?query=work)
Optional third font for this theme is Work Sans which I appear to be using for the plugins. Don't recall why so skip this one and change the font settings in the plugins to Montserrat if you're not too bothered to look like mine.

#### Install the fonts
Download the zip files, extract the truetype font files (ttf), select them all, right-click and hit install.




## Install
I run Windows so if you want it to look the same as mine just follow the following steps:

1. Download and copy the userchrome.css file from the repository to your Joplin config folder (check the header in your settings in Joplin to find out where exactly that is for you). For me it was `C:\Users\User\.config\joplin-desktop` 
2. Set your Joplin theme to 'Dark'
3. Go to the plugins tab and install the following 
    - Quick HTML tags
    - Markdown Table Colorize (most recommend)
    - Spoiler (most recommend) - If Spoiler is useful for you, I would like to tell you that you will get more advanced features when using it with OhmineDT.
    - Outline
    - Note Tabs
    - Menu items, Shortcuts, Toolbar icons
 4. You're good to go! Restart Joplin and get to work!



## My plugin settings
While no doubt your theme does not look exactly like mine, I have additional settings in the specific plugins to better blend these elements into our base theme.

First of all go to View > Change Application Layout and move Notebooks, Notes and Outline all into the single column on the left and the editor and notes on the right, adjust the margins for a good fit and reduce the height of the note tab as much as possible.

- Outline: 
Auto Hide: True
Font Family: Work Sans
Font Size 12
Background Colour: #141414
Disable Linewrap: True
Show Number: True
User Style: .outline-content{padding-left: 1.5em; font-variant: small-caps;}#header{ display:none;} .toc-item-link:hover {   color: #2370A9; font-weight: normal;}

- Note Tabs
Note Tabs height: 41
Minimum Tab width: 50
Maximum Tab width: 150
Font Family: Work Sans
Font size: 14px
Background color: #191919
Hover Background color: #0F283D
Active background color: #1085ff
Divider color: #B87C47


The settings that I haven't explicitly stated, assume that I use the default value.

## Anything extra
Just in case there's anything else I need to add to this. Essentially, I hope you enjoy it and you have no issues installing and getting it running. 
