# Foundry Token Patrol
This module allows GMs (and optionally players) to set patrol points for their tokens, making the tokens move between the set points without input.

### Reasoning

Using this mod, you will be able to set up "Patrol Routes" which tokens will move to based on a timing of your choice. This can give certain scenes a more life like appearance! Make your markets full of life and give your castles that patrolling retinue they've always needed!

### FVTT Version
- Tested on FVTT v0.3.8
- No known module incompatibilities. 

### IMPORTANT / BUGS
**Remember to back up your world before using mods**

Bugs are inevitable, despite my best efforts to remove all that I could find. If you happen to locate any or if something doesn't appear to work as intended, please don't hesitate to contact me on Discord at (JacobMcAuley#3461). I will correct the issue and push it out as soon as possible. 

That being said here are all the known issues at the moment:
1. Group selecting tokens for deletion while patrolling is active *sometimes* results in an error message occuring. Hit F5 to refresh to fix.
2. Games with two or more GM or assistant permissions will find unexpected behavior. 
3. Creating nodes with a great distance and setting the delay between movements will result in the token never reaching any destination.

### It's a feature not a bug!
1. Tokens moving through linear mode on a diagonal may take an unexpect route to reach the point. This is how the function currently works. Future updates will adjust this.

### Planned features
1. A loiter mode: Tokens will move about after stopping at a node
2. Player use mode: Allow players to set patrols for their owned tokens.

### Installation Instructions

To install Foundry-patrol, do the following:

1. [Download the zip file](https://github.com/JacobMcAuley/foundry-patrol/archive/master.zip)
2. Extract the folder to your 'public/modules' in Foundry VTT.
3. Reload your application.

Auto-Installation Instructions:

1. Copy this link: https://github.com/JacobMcAuley/foundry-patrol/raw/master/module.json
2. Open FoundryVTT and navigate to Add-On Modules
3. Select "Install Module" and paste link into textbox.
4. Click "Install" and watch as the mod is installed!

### Usage

1. Download and install the mod, then enable it on Foundry.
2. Right click a token to view the tokenHUD.
3. Refer to the following image for descriptions of icons.


### Keys

Workflow short cuts:
Starts with : SHIFT - Q
1. R -> Adds a plot point (Think Route)
2. C -> Clears routes (Think Clear)
3. T -> Changes all assigned route colors
4. G -> Starts routes (Think Go) 
5. H -> Halts all routes (Think Halt)

Additional Note: Using SHIFT - Q - 1(one) - KEY will result in only the highlighted tokens being affected opposed to globally.

### Examples

![example_picture1](imgs/examples/example1.png)
![example_picture2](imgs/examples/example1.png)

Watch the video:
[![Watch the video](https://img.youtube.com/vi/zR6ut3gglZ4/maxresdefault.jpg)](https://www.youtube.com/watch?v=zR6ut3gglZ4)

### Feedback

If you have any suggestions, please let me know on discord! (JacobMcAuley#3461)


### Attributions

Linear Walk found at: https://www.iconfinder.com/icons/214663/arrow_points_icon
Normal Walk found at: https://www.iconfinder.com/icons/2639849/chart_line_icon

### Special Thanks
Special thanks to: Felix, Jasaplay, Moerill, Gen Kitty, Guaccamole, errational, and any others I missed for providing much needed feedback.

# Donations
If you liked this project and want to support future ones, consider donating! 
This module and all previous and future modules, as always, will be free to use an download. Any donations are warmly received and appreciated!
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=723SW7WMD8YR6&item_name=Thank+you+for+your+tip%21&currency_code=USD&source=url)