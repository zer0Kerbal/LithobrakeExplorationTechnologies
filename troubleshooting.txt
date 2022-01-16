Troubleshooting:

 

Problem: Parts flash different colors, with glitchy "z-fighting":

Usually it boils down to one of a few different things. Now that I've seen probably most of them, I can give you a good list:

1. Everything is installed correctly, but ModuleManager's cache hasn't noticed the changes yet.

   Fix: This is a great one to try first. Delete the file called "ModuleManager.ConfigCache" in GameData. ModuleManager recreates it on the next KSP start.

2. ModuleManager isn't installed, or is too badly out of date.

   Fix: Install it, or upgrade it. :)

3. This mod is installed incorrectly, or you've deleted the color-change ModuleManager configs.

   Fix: Reinstall the mod correctly, and in its entirety.

4. Missing dependency.

   Fix: Make sure either Firespitter or InterstellarFuelSwitch is installed. The "core" DLL alone is OK, as you only need the functionality it provides for mesh-switching. The entirety of those mods is not necessary.

5. Broken dependency.

   Fix: Make sure Firespitter or InterstellarFuelSwitch are actually working. The version could be out of date and not working, or partially installed, or corrupted somehow. Delete it and re-install with the latest version.
