# A JSFL that could do batch export from the library for Flash/Animate

This file is inspired by THIS LINK：http://oldsite.abitofcode.com/2011/11/export-flash-library-items-as-pngs-with-jsfl/<br/>
This jsfl file is ONLY be tested under Animate CC 2019

# What I did:
1) Fixed the problem that the component has no linkageIdentifier(use name instead).
2) Could save the png file to any directory.
3) Will check if the directory exists before export, if not, it will create one.
4) Add scale support for export

# How to use
1) Download batch_export_single_folder.jsfl
2) Open .fla file
3) Drag the jsfl to the opened windows, select "Run as Command".
4) Just wait.

# Note
If you want to change the scaleFactor, just change the line 36
exportItemAsPng(currentItem, 2.0)
change "2.0" to any scale number.

