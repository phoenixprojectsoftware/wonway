Resolution patch for WON Half-Life


About this patch:

This unofficial patch is intended to use only with original WON version of Half-Life (old retail version shipped on CD). It should not be used with Steam version of Half-Life. You should have WON version of Half-Life installed on your PC and patched with latest WON patch (1.1.1.0). Also, this patch will work only for OpenGL renderer and will not work for Software or Direct3D mode.


How to use:

This archive contains 5 versions of hl.exe, main Half-Life executable. One of them is original hl.exe, from WON patch version 1.1.1.0, without any changes. The only thing changed in other 4 versions is replacing of some of initial values of OpenGL resolutions (with 4:3 screen aspect ratio) with few commonly used modern ones. You just should choose that one modified hl.exe which is most suitable (by available with it resolutions) for your needs. Another file included is autoexec.cfg, which contains an optimized FOV (field of view) value, depending on specific aspect ratio of modified resolutions. This file will set this value automatically on every game launch. Copy any hl.exe that you wish in your WON Half-Life folder over existing one. And copy corresponding autoexec.cfg to the "valve" folder.

After copying files launch the game normally and choose preferred resolution via Configuration -> Video -> Video modes -> OpenGL menu. Warning! Do not try to set in the game that resolution which is not compatible with your display. Also, if you want to have a better color quality of picture in the game, add this parameter to hl.exe shortcut:
 -32bpp


Resolutions in executables:

4:3 (original)	800x600   1024x768  1152x864  1280x960   1600x1200
16:9 (1360)	1024x576  1280x720  1360x768  1600x900   1920x1080
16:9 (1366)	1024x576  1280x720  1366x768  1600x900   1920x1080
16:10		960x600   1280x800  1440x900  1680x1050  1920x1200
1280x1024	800x600   1024x768  1280x768  1280x1024  1600x1024

Lower resolutions (640x480 and below) are not changed in any of executables. There are two versions of executable for 16:9 aspect ratio, which differ only by one modified resolution. The executable for 1280x1024 resolution also allows to choose 2 additional resolutions which are not conform nor to 16:9, nor to 16:10 aspect ratio (they added just in case). Please note, that autoexec.cfg attached with this executable contains a value that suits only for 1280x1024 resolution, so for 2 other resolutions you need to set suitable FOV value manually.


Credits and additional information:

http://www.wsgf.org/dr/half-life-non-steam


Have a nice game!