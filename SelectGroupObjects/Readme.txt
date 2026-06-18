#########################################################
# Select Group Objects
#
# USAGE
#  Can be useful for selecting all the objects in a group and/or subgroups.
#  This was developed in response to videos made by the Silk Workbench's creator.
#  - Select a group.
#  - Execute the macro from Macro menu or assigned button.
#
# SETUP INSTRUCTIONS
# - Copy SelectGroupObjects.FCMacro to your FreeCAD Macro folder.
#   Likely: C:\Users\<user>\AppData\Roaming\FreeCAD\v1-1\Macro\
# - (optional) Create an Icons folder in the Macro folder if it doesn't exist already and
# - (optional) Copy the icon SelectGroupObjects.svg a folder. You may use any folder to host the icon.
#   You may find it helpful to use ...\FreCAD\v1-1\Macro\Icons. You can create it if it
#   doesn't already exist.
#
#   SelectGroupObjects.FCMacro should now appear in your FreeCAD Macro page. Macros Menu > Macros.
#
#   To add the button:
# - Go to Tools > Customize
# - Click on Macros tab
# - Select SelectGroupObjects.FCMacro from the Macro dropdown
# - Give the Macro Menu Text anything like  "Select Group Objects"
# - Choose the SelectGroupObjects.svg icon (this is optional, if no icon, text will appear in toolbar)
#	If you can't find it, click Icon Folders button at the bottom and add
#	...<FreeCAD path>\Macro\Icons
#	or any folder you choose to hold icon(s)
#
# Then, in Toolbars, you can add the macro.
# - Choose Category: Macros
# - Advise Global is selected on the right dropdown.
# - You may need a New [custom toolbar]. Call it anything, e.g. "CustomGlobal"
# - Select "Select Group Objects" from the left list, click the right arrow
#
#   And you should now have a button with text or icon to facilitate easier object selection, esp.
#   if you're working in Silk!
#
#########################################################