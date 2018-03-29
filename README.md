## OBS Studio Recording Dot

see README-original.md for the original author's readme.

The original "red dot" plugin was only built for 32 bit systems, I needed 64bit and more up-to-date build tools.

This fork adds a cmake file and windows batch script for easy building of both 32 and 64 bit versions without having to have a full visual studio install. It's also configured to use the visual studio 2017 build tools (unlike the original plugin which uses vs2013).

*Needs a working obs studio development environment, and a currently built version of the source code for certain obs library includes*

As the code is not mine, no support will be given by me if it doesn't work for you once compiled. All I've done in this fork / branch is add the ability to build it "automatically" using command line tools instead of having to fiddle around with visual studio's IDE. I also will not be providing any binary releases (sorry).


