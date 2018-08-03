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

Configure iTerm2 -> Preferences -> Profiles -> Colors with freeCodeCamp colors from the style guide

- [design-style-guide.freecodecamp.org](https://design-style-guide.freecodecamp.org/)
