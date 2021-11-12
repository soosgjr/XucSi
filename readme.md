# XucSi for SoulFu

![XucSi Logo](Graphics/logo.png?raw=true)

Xuln's Ultimate Character Saving: Improvements is a patch for a mod of Secret of
Ultimate Legendary Fantasy: Unleashed.


## Features

- The loading feature now works without the devtools, but requires the full
  version to be unlocked.
- Saves are now stored in individual files without modifying the SDF archive.
- The save slots now show the occupying characters' name.
- The characters' companions are now also saved.
- The characters' HP, MP, and Hunger are now refilled upon loading them.
- Fixed the bug where the characters would lose a level when loaded.
- Fixed the bug where the characters' experience would overflow and be capped at
  255 when loading them.
- Fixed the bug where the characters' progress to unlocking mana wasn't saved.


## Installation

 1. Copy everything from the `Source` folder to `C:\SoulFu\` or wherever you
    installed the game.
 2. Start the game through the `SoulFu DEVTOOL.exe` executable.
 3. Hold down the C key and press the "Tools" button that appears in place of
    the "Be Nice!" button.

    ![DevTools Screenshot](Documentation/devtools.png?raw=true)

 4. Open the File Util.

    ![File Util Screenshot](Documentation/file-util.png?raw=true)

 5. Enter "SAVE.SRC" into the "File" textbox and press the "Import" button.

    ![File Importing Screenshot](Documentation/file-importing.png?raw=true)

 6. Repeat the previous step using the following filenames:
    - CPLAYER.SRC
    - WFADER.SRC
    - WSAVE.SRC
    - WSPAWN.SRC
    - WSTATUS.SRC
 7. While "WSTATUS.SRC" is still in the textbox, press the "Text Edit" button.

    ![Text Edit Screenshot](Documentation/text-edit.png?raw=true)

 8. Press the "Recompile" button.

    ![Recompile Screenshot](Documentation/recompile.png?raw=true)

 9. Press the "SDF Save" button.

    ![SDF Save Screenshot](Documentation/sdf-save.png?raw=true)

10. Restart the game using the regular executable.


## Usage

### Saving

 1. While you're in a town, press the ESC key.
 2. Press the "Save Game" button that appears in place of the "Continue" button.

    ![Town Menu Screenshot](Documentation/town-menu.png?raw=true)

 3. Select the desired save slots from the drop-downs for each player.

    ![Save Slot Screenshot](Documentation/save-slot.png?raw=true)

 4. Press the "Save Game" button.

    ![Save Game Screenshot](Documentation/save-game.png?raw=true)


### Loading

 1. Make sure the full version is unlocked.
 2. Start a new game.
 3. Press the "Human" button at the top right corner of your character window to
    switch to load mode.

    ![Load Mode Screenshot](Documentation/load-mode.png?raw=true)

 4. Select the desired save slot from the drop-down.

    ![Load Slot Screenshot](Documentation/load-slot.png?raw=true)

5. The game can now be started as usual.

    ![Start Game Screenshot](Documentation/start-game.png?raw=true)


## Compatibility

The mod and its patch was made for SoulFu Version 1.5 NICEWARE.


## License

The SoulFu licensing terms are available in [the game's manual](Manual.htm).


## Credits

SoulFu was developed by [Aaron Bishop](http://www.aaronbishopgames.com). The
original Character Saving mod was developed by Xuln. The version this patch is
made for might have seen some edits from Captain Innocuous, but since the
original forums are long gone and without an archive, there's no way to confirm
this. The additional fixes and modifications were made by Gabor Soos.

The mod's logo was designed using the following free fonts, all created by
[Typodermic Fonts](https://typodermicfonts.com):

  - [Cretino](https://typodermicfonts.com/cretino-for-fancy-lads/)
  - [Green Fuz](https://typodermicfonts.com/green-fuz/)
  - [Living by Numbers](https://typodermicfonts.com/living-by-numbers/)


## Version History

- Version 0.1.0, November 11th, 2021
  - The initial release.
