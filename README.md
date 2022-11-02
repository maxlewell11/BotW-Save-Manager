# Breath of the Wild Save Manager

***This tool is <ins>not</ins> a save <ins>editor</ins>! If you are looking to edit your save, use Marc Robledo's [BOTW save editor](https://www.marcrobledo.com/savegame-editors/zelda-botw/) to modify the contents of your save. This works for both WiiU and Switch files.***

---

**Botw Save Manager** is a fork of [`https://github.com/WemI0/BOTW_SaveConv`](https://github.com/WemI0/BOTW_SaveConv) updated to `DotNET 6` with support for `Windows`, `Linux`, and `MacOS (untested)`.

Converting currently supports BOTW `Switch <-> WiiU` save files that share the same update version (upgrade/downgrade untested).

## Setup

1. Download and install the DotNET 6.0 Runtime for your system: [Windows x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-6.0.10-windows-x64-installer), [Linux](https://learn.microsoft.com/dotnet/core/install/linux?WT.mc_id=dotnet-35129-website), [MacOS Arm64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-6.0.10-macos-arm64-installer), [MacOS x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-6.0.10-macos-x64-installer)
2. Download the [latest release]() of BotwSaveEditor.
3. Run `BotwSaveEditor.exe` and bypass the smartscreen warning. *(This warning is caused by the unsigned **.exe**. Signing applications can become expensive, so it is impractical for community project such as this.)*

## Usage

### Desktop Application

**<ins>Normal Method</ins>:**

1. To open a save, use `File > Open Save Folder (Ctrl + O)` or double click the UI to browse for a WiiU or Switch save folder; alternatively, drag the save folder over the UI.
2. Once the save has opened, click `Convert` and browse for an empty folder to save the converted files to.
3. A debug log will appear and log the converting process.
4. Once it has completed, and there are no errors, a prompt will appear saying the conversion was successful.

**<ins>Quick Method</ins>:**

1. Quickly convert a save by using `File > Convert Save (F3)` and navigating to a WiiU or Switch save folder.
2. In the second folder selection prompt, browse for an empty folder to save the converted files to.
3. A debug log will appear and log the converting process.
4. Once it has completed, and there are no errors, a prompt will appear saying the conversion was successful.


### Console Application

1. Drag and drop a WiiU or Switch save folder over the console window as prompted.
2. Wait for the save to process, then drag an empty folder over the console window to save the converted files to.
3. Wait once more for the completion message.