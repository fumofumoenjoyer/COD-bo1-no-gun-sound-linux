# COD-bo1-sound-and-mouse-issues-linux
I took this from [this reddit comment](https://www.reddit.com/r/wine_gaming/comments/x42esq/comment/lwicm1i/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) so credits to u/Outrageous_Welder_78

Basically you need to install these through winetricks/protontricks

dx9 (the one with ?? As the desc)

vcrun2005, vcrun2008 & vcrun2010 (I found these to be the redists bo1 uses)

xact 

So if you own the game on steam fire up protontricks and add these with the gui, if you own the game from "other methods" you can add them through lutris or heroic, (i used and tested heroic only but lutris should work too)

As a bonus, if you have some weird mouse movement try using these launch options:

DXVK_ASYNC=1 PROTON_NO_FSYNC=1 PROTON_NO_ESYNC=1 %command% 

if you're using heroic untick these:

![image](https://github.com/user-attachments/assets/d7e8f1a0-e840-4257-97a4-f1dcb2c65f36)


i use plutonium, but should also work for the standalone game.
