# Align underlines in hyperlinks plugin for Sketch.app
Properly align hyperlink underline layers regardless of their text in Sketch

## Update

Version 1.1:

- [add]  Support vertical align


## Demo

**From this**
![demo][demo1-image]

**To this**
![demo][demo2-image]

## Description

If you underline links in your design templates, then it maybe hard to align underlines when text links changes.
The plugin aligns underlines with the width of their corresponding text link.

This plugin has been tested on Sketch v3.3.2


## Install

1. Download ZIP of this repo.
2. Extract and rename folder to suit your taste.
3. Put the folder in your Sketch plugin folder (Use `Plugins>Reveal Plugins Folder` to find it).

Folder name and plugin filename will show up as items in Sketch `Plugins` menu.


## Usage

1. Your links should be groups of text and line layers. Line layer should be named "**underline:0**".
2. `Alt + Cmd + L` or use `Plugins` menu.
3. Demo of usage https://vimeo.com/144720669

## Changing the Default Keyboard Shortcut

1. Open Sketch's plugins folder. You can do it by choosing
   custom script from the Plugins menu, then click the gear icon and
choose "Open Plugins Folder".
2. Open the file "Align underlines.sketchplugin" in text
   editor.
3. The shortcut is on the first line:

    ```
    // Align underlines (alt cmd l)
    ```
    
    Change it.



[demo1-image]: http://i.imgur.com/9PL2oSM.png
[demo2-image]: http://i.imgur.com/2lbzsiq.png
