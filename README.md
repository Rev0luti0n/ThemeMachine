# ThemeMachine
Enables various themes hidden on OS X Yosemite and above. This software hack only currently enables the OS X Yosemite "Dark Mode", but further changes will be committed that allow for both custom colours on NSControls and for legacy appearances to be used.

# Usage
This software is highly experimental and is in an unfinished form, so keep that in mind when attempting to utilise "ThemeMachine". ThemeMachine also has a nasty habit of crashing programs injected into and while this will be sorted out in time, I would not recommend running this on a production machnine.

To use, compile the dylib, and in a terminal type the following:
DYLID_INSERT_LIBRARIES=(Path to compiled Dylib) (Path to Application)

So if the dylib was stored at /Users/ThemeMachine/Desktop/theme.dylib (and you wanted to theme Finder.app) you would type DYLIB_INSERT_LIBRARIES=/Users/ThemeMachine/Desktop/theme.dylib /System/Library/CoreServices/Finder.app/Contents/MacOS/Finder

# Disclaimer
ThemeMachine comes with no warranty, expressed or implied. Use at your own risk.

Thanks
Rev0luti0n
