# PandaProps

Resin-style supports for FDM prints, checked in your own copy of Bambu Studio or OrcaSlicer.

## Download

Get the newest version from the [download page](https://pandaprops.github.io/releases/) or from [Releases](https://github.com/pandaprops/releases/releases/latest). It saves a plain 3MF that any slicer opens, and on Windows and Mac it can also check every layer in your own Bambu Studio or OrcaSlicer.

**Windows.** Download `PandaProps-Setup-<version>.exe` and run it. It is not signed yet, so Windows shows a "Windows protected your PC" screen first: click **More info**, then **Run anyway**. After that it updates itself.

**Mac.** Download the zip for Apple silicon (`arm64`) or Intel (`x64`), unzip it and drag PandaProps into Applications. It is not signed either, so the first time you open it macOS says it cannot check it. Click **Done**, open System Settings › Privacy & Security, scroll down to the note about PandaProps and click **Open Anyway**. The Mac version tells you when a new one is out but does not update itself: download it and drag it over the old one.

**Linux.** Download `PandaProps-<version>-linux-x64.AppImage`, for 64-bit Intel or AMD PCs. There is nothing to install: allow it to run as a program in its Properties (or `chmod +x` it) and open it. It updates itself. On Linux it checks every layer itself and saves a plain 3MF for any slicer; checking in Bambu Studio or OrcaSlicer comes later.

## Privacy

PandaProps works on your computer. It sends nothing about you, your computer or your models unless you press Send in Help › Send feedback. The only thing it fetches by itself is the version list on this page, to see whether a newer app or engine is out, and you can turn that off in Settings › Updates.

Not affiliated with Bambu Lab.
