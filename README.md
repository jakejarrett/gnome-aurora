# Gnome Aurora

## Summary
### What is this project?
A very opinionated & crude attempt at redesigning Gnome DE in a Neumorphism / Aurora style with the main criteria being it would be something I'd personally use (Dark theme, has a dock & app indicators and just things I think look generally nice)

### WIP Screenshot (Updated last: March 15th)
![Screenshot](https://raw.githubusercontent.com/jakejarrett/gnome-aurora/main/assets/wip/wip-aurora-v0.png)

## Crude Styleguide (Will convert to a better format later on)

### Why is it blurred & not just opacity?
It looks nicer & opacity is just a piece of the overall puzzle. Blur gives it more of a feel as if whatever is behind is not just part of the current application, it has actual seperation.
(tl;dr- easy to distinguish what is focused & not focused w/o relying ONLY on colour or contrast)

### What elements can be translucent / peak into the background
- The background of the app should be a blank blurred window of whatever is below it (incl other applications excluding anything that could be considered "above" it like the panel, dock, modals & any system dialogs.)
- Inner content should be rendered as another "entity" on this new "plane", components that are interactive must have states to indicate such interactivity (2 shadows, one light on the top left & one dark on the bottom right to indicate it is a level higher on the Z plane)

### What elements should be opaque?
- Visual content eg/ maps, videos, photos
- Web browsers (These display visual content, but you don't want to ruin the UX of existing experiences in favor of your own desktop experience. these are 2 different user experience flows)
- 

### Panel
#### Padding
    Horizontal 40px
    Vertical- 16px

### Applications
#### Padding
    Horizontal - 40px
    Vertical - 40px

#### Borders
    Width - 1px
    Radius - 50px
    Style - Line / Solid