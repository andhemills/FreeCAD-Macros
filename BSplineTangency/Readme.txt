#########################################################
# BSpline Tangency
#
# USAGE
#   Works in Sketcher.
# - Select 2 BSplines They actually don't need to be attached, but advised to be.
# - Click the button for the macro.
#   NOTE: This macro only works from a button assigned to the macro.
#
# SETUP INSTRUCTIONS
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
# - Choose the BSplineTangency.svg icon (this is optional, if no icon, text will appear in toolbar)
#	If you can't find it, click Icon Folders button at the bottom and add
#	...<FreeCAD path>\Macro\Icons
#
# Then, in Toolbars, you can add the macro.
# - Choose Category: Macros
# - Ensure Sketcher is selected on the right dropdown.
# - You may need a New [custom toolbar]. Call it anything, e.g. "CustomSketch"
# - Select "Toggle 3D to Tree" from the left list, click the right arrow
#
#   And you should now have a button with text or icon to facilitate easier BSpline Tangency.
#
#########################################################