# powerlevel9k-freeCodeCamp
custom setup for Powerlevel9k for a freeCodeCamp theme

![Screenshot](images/terminal-freecodecamp-powerlevel9k.png)

## Custom prompt segment

This adds the freeCodeCamp icon (from Nerd Fonts) along with the word freeCodeCamp as a segment in the terminal prompt

```
POWERLEVEL9K_CUSTOM_FREECODECAMP="echo -n $'\uE242' freeCodeCamp"
POWERLEVEL9K_CUSTOM_FREECODECAMP_BACKGROUND="cyan"
POWERLEVEL9K_CUSTOM_FREECODECAMP_FOREGROUND="white"
```

## Color scheme

Add the freeCodeCamp color scheme by downloading this repo (or just the [freeCodeCamp.itermcolors](freeCodeCamp.itermcolors) file).  

iTerm2 -> Preferences -> Profiles -> Colors -> import -> freeCodeCamp.itermcolors  

Alternatively you can customise it yourself and then save it by selecting the export option.  

freeCodeCamp's style guide has more on its brand colors, logo and typography -   [design-style-guide.freecodecamp.org](https://design-style-guide.freecodecamp.org/)  

For a wide selection of color schemes, checkout [iterm2colorschemes.com](https://iterm2colorschemes.com/)  
