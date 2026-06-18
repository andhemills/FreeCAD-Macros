#########################################################
# Toggle 3D2TreeExpand  (diagnostic build v2)
#
# Toggles Preferences > General > Selection > "Auto switch to the 3D view
# containing the selected item" (TreeView/SyncSelection) with one click, and
# updates the toolbar button icon to reflect the new state.
#
# Button lookup now matches across several action attributes (tooltip, text,
# whatsThis, objectName) since a macro button's tooltip is often empty unless
# set manually in the Customize dialog. MATCH_TOKEN is the substring to look
# for; set a matching Tooltip on the button in Tools > Customize > Macros if
# nothing is found.
#
# INSTRUCTIONS
# - Copy Toggle3D2TreeExpand.FCMacro to your FreeCAD Macro folder.
#   Likely: C:\Users\<user>\AppData\Roaming\FreeCAD\v1-1\Macro\
# - Create an Icons folder in the Macro folder if it doesn't exist already and
# - Copy the icons Toggle3D2TreeOff.svg and Toggle3D2TreeOn.svg into ...\Macro\Icons
#
#   The Macro should now appear in your FreeCAD Macro page. Macros Menu > Macros.
#
#   To add the button:
# - Go to Tools > Customize
# - Click on Macros tab
# - Select Toggle3D2TreeExpand.FCMacro from the Macro dropdown
# - Give the Macro Menu text = "Toggle 3D to Tree" (this is important!)
# - Choose the Toggle3D2TreeOff.svg icon
#	If you can't find it, click Icon Folders button at the bottom and add
#	...<FreeCAD path>\Macro\Icons
#
#########################################################