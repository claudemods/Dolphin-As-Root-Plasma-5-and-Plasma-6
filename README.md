Dolphin-As-Root-Plasma-5-and-Plasma-6
simple service menu

v1.4
support for plasma 5 and 6 now working

v1.3
plasma 6 support

since i Create a taskbar i use on my distributions
based on debian ubuntu and arch kde under the name claudemods
i had an issue on plasma 6 arch
i created this to fix the issues i was having with copying my distributions necessities to locked root directories
now you can open the dolphin as root with just one downloaded .desktop file
it Works with plasma 5 and plasma 6


Attention:
Please read up on root and system files before changing anything with this add-on!!

Please note, the black-themed tab that I have open in my photo will be your default root account's desktop theme color. I just so happen to have mine customized as Breeze Dark and on my main account its as Breeze Light.
The is the defaults on my distributions i create


How to install:
- Dolphin -> Preferences -> Services -> Download New Services...
...or
For kde5
- move the downloaded open-dolphin-as-root.desktop file to
~/.local/share/kservices5/ServiceMenus (create the folder if it's missing)
Also use right click on the file > Properties > Permissions >
And mark the checkbox next to the text "Is executable".
For kde6
- move the downloaded/open-dolphin-as-root.desktop file to
~/.local/share/kio/servicemenus/ (create the folder if it's missing)
Also use right click on the file > Properties > Permissions >
And mark the checkbox next to the text "Is executable".
or use $ chmod +x ./open-dolphin-as-root.desktop

support me and others with the button below to keep projects like this going
