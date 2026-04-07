# Showing the Developer Tab on Mac

Here's how to show the Developer tab on Excel for Mac:

1. Open Excel and click Excel in the top menu bar (top-left of your screen)
2. Click Preferences
3. Click Ribbon & Toolbar
4. On the right side, scroll down the list and find Developer
5. Check the box next to it
6. Click Save

You should now see the Developer tab appear in your Excel ribbon.

Opening the VBA Editor on Mac
Once Developer is enabled, you have two options:

- Click Developer tab → Visual Basic
- Or use the keyboard shortcut Option + F11


Note: On some Mac keyboards you may need to press Fn + Option + F11


# Showing the Developer Tab on Windows

1. Open Excel and click File in the top-left corner
2. Click Options at the bottom of the left sidebar
3. Click Customize Ribbon on the left side of the Options window
4. On the right side panel, scroll down and find Developer
5. Check the box next to it
6. Click OK

The Developer tab will now appear in your Excel ribbon.

## Opening the VBA Editor on Windows
Once Developer is enabled, you have two options:

- Click Developer tab → Visual Basic
- Or use the keyboard shortcut Alt + F11


# ProcessDataLogger

The main way to save your VBA code so it's always available without copy-pasting from GitHub:
## Personal Macro Workbook
### This is a hidden workbook called PERSONAL.XLSB that opens automatically every time you launch Excel. Any macros saved here are available in every workbook you open.
To set it up:

1. In Excel, go to Developer → Record Macro
2. Change "Store macro in" to Personal Macro Workbook
3. Click OK, then immediately click Stop Recording (we just needed to create the file)
4. Press Alt + F11 to open the VBA editor
5. In the Project Explorer on the left, you'll see VBAProject (PERSONAL.XLSB)
6. Expand it, right-click Modules, click Insert → Module
7. Paste your entire ProcessData macro into this module
8. Save with Ctrl + S and close the VBA editor

Now every time you open any Excel file, you can go to Developer → Macros and ProcessData will be there ready to run.

# Things to note

## HIOKI lr8400 was for set hh7001 config test, and HIOKI lr8450 was for set A3 config test

## DataProcessingMaster is dynamic, and able to process both hiokis. 

## Only the data is being processed, the file is not automatically saved as a xlsx file. u have to manually SaveAs the file into an xlsx file.

# Customizing the Code

## To adjust the parameters in the code for hioki lr8450 and hioki lr8400, go to steps 3 and 4 and adjust the cell that you want to copy from, and adjust the rows and columns that you wish to delete.
