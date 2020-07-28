# PunchMeInTheFace  Color Scheme

>  A beautiful color scheme for Sublime Text 3 that will punch you in the face. Optimized for [typescript]([babel-sublime](https://github.com/babel/babel-sublime) , C/C++, Python (needs more testing)

# Install

## - Manual

> Clone or copy this folder into your packages folder. (In Sublime hit `Preferences -> Browse Packages` to find packages folder location). 
> 
> Note: You can also create a Themes folder in your package folder location, and copy this theme's folder into the newly created Themes Folder

## - Automatic

> You can now install the theme via package control https://packagecontrol.io/packages/PunchMeInTheFace%20Color%20Scheme

# Screenshots
The theme on Typescript React, C/C++ projects

<img src="https://github.com/tashrifsanil/PunchMeInTheFace-Color-Scheme/blob/master/Screenshots/punchmeintheface-tsx.png"/>
<img src="https://github.com/tashrifsanil/PunchMeInTheFace-Color-Scheme/blob/master/Screenshots/punchmeintheface-c-cpp.png"/>

# Companion UI
I haven't really found a good UI to go along with this theme, but that being said I like the deafult adaptive theme that comes with sublime text and I just wanted to modify the sidebar and tab colors of the default theme to match this color scheme. To achieve that create a file called `Adaptive.sublime-theme` and paste the following into it. This will override the Adaptive UI theme's colors to match the color scheme

```
[
    {
        "class": "sidebar_tree",
        "row_padding": [8, 3],
        "indent": 12,
        "indent_offset": 17,
        "indent_top_level": false,
        "layer0.tint": [15, 15, 15],
        "layer0.opacity": 1.0,
        "dark_content": false
    },
    {
        "class": "sidebar_heading",
        "color": "#2A7D9F",
        "font.bold": true,
        // "shadow_color": [29, 29, 22],
        "shadow_offset": [0, 1]
    },
    {
        "class": "sidebar_label",
        "color": "#F9F9F9"
        // , "shadow_color": [250, 250, 250], "shadow_offset": [0, 0]
    },
    {
        "class": "sidebar_label",
        "parents": [{"class": "tree_row", "attributes": ["selected"]}],
        "color": "#00FFFF"
        // , "shadow_color": [60, 60, 60], "shadow_offset": [0, 1]
    },
    // Tab color override
    {
        // inactive tab color
        "class": "tab_control",
        "tint_modifier": "#0f0f0f",
    },
    // selected tab color override
    {
        "class": "tab_control", "attributes": ["selected"],
        "tint_modifier": "#000000",
    },
]
```

# Credits
Special thanks to https://www.linkedin.com/in/thechristina/ for the theme name




