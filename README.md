# BunnyhopAPE
An external autobhop prediction enabler for CS:S

Description
--
* This makes autobhop feel a lot less laggy on high ping servers (without allowing you to cheat scroll times like clientside autobhop does).
* Won't work without `-insecure` key in startup parameters (otherwise is very likely to trigger a VAC detection).
* Can be toggled by `Scroll Lock` key.

Changelog
--
* No "Memory Access Violation" once you close BunnyhopAPE.exe after closing CSS
* Automatically reverts to "Waiting for CSS to open" state after CSS closes (no need to close and relaunch bunnyhopape)


How to build
--
1. Open `BunnyhopAPE.vcproj` in Visual Studio.
2. Select `Release` configuration.
3. **`BUILD`**-->**`Build BunnyhopAPE`**
4. `BunnyhopAPE.exe` will appear in the newly created `Release` folder.
