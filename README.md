# HARP Research Category Diagram Inkscape Defaults

This repository contains default settings and tools for Inkscape, specifically configured for HARP Research Inc.

## Installation Instructions

1. Install Inkscape 1.4:

   - Download from [Inkscape&#39;s official website](https://inkscape.org/release/inkscape-1.4/)
   - Run the installer and follow the installation wizard
2. Install TexText Extension:

   - Download the latest version (1.11.0) from [TexText Releases](https://github.com/textext/textext/releases)
   - Follow the installation instructions provided in the TexText documentation

## Contents

- Default Inkscape configuration files
- HARP LaTeX preamble for TexText
- Additional tools and settings

## Tutorial

1. Install Inkscape 1.4
2. Install TexText Extension


### Set default Inkscape font to Times New Roman
   - First, create a text block by clicking on the text tool on the sidebar, then clicking somewhere in the blank document
![1738090830020](image/README/1738090830020.png)
![1738090841789](image/README/1738090841789.png)

   - Press escape to exit text entry mode, then after the cursor changes click back on the text box once to select it as an object. It should have draggable handles around it.
   ![1738090948805](image/README/1738090948805.png)

   - Then, in the Text and Fonts tab, find the `Times New Roman` font as such:
     ![1738090662278](image/README/1738090662278.png)

   - Click on the `Times New Roman` font and click on the `Set as Default` button.


### Defining keyboard shortcut for opening TexText dialog

   - In Inkscape open Edit -> Preferences -> Interface -> Keyboard -> Shortcuts
![1738091018598](image/README/1738091018598.png)
![1738091070054](image/README/1738091070054.png)

   - Search for TexText entry in the Extensions category

   ![1738091097161](image/README/1738091097161.png)

   - Double click on the empty space in the Shortcut column next to the TexText entry. An entry New accelerator appears in the Shortcut column.
   ![1738091147648](image/README/1738091147648.png)

   - Now type the keyboard shortcut you intend to use, e.g. CTRL + T. Inkscape informs you if the shortcut is already in use.
   ![1738091181888](image/README/1738091181888.png)

   - After you have set the shortcut, press escape, then click x to close the dialog.

### Set Render LaTeX to `xelatex`

- After setting the keyboard shortcut, you can now use the shortcut to open the TexText dialog. It will pop up seperately from the Inkscape window. 

**Note:** While the TexText dialog is open, Inkscape will appear to be unresponsive. This is normal. If you can't see the TexText dialog, you can open it by clicking on the TexText icon in the toolbar and selecting the dialogue window.

- After clicking into the dialog, select  the dropdown in the Command column and select `xelatex`

![1738091365197](image/README/1738091365197.png)

![1738091377638](image/README/1738091377638.png)
### Selecting the HARP Research Preamble 

- Under the `Preamble File` column, click on the `default_package.tex` button.
![1738091411349](image/README/1738091411349.png)

- After clicking on the button, a file browser will pop up. Navigate to the `preamble` folder in this repository and select the `HARP Preamble.tex` file.

- **Note:** This will only set the preamble for the current latex text block. If you want to set the preamble for all latex text blocks, you will need to set the preamble for each text block individually. In order to modify the preamble for all text blocks, you will need to modify the global `default_package.tex` file in the `preamble` folder from TexText.

### Adding the Inclusion Morphism Tail

- First select the pen tool on the sidebar.
![1738091665454](image/README/1738091665454.png)

- Press `Ctrl + Shift + F` to open the fill and stroke dialog.

