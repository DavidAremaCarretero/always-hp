# Version 1.0.20
Fixed issues with mass update of tokens.  Due to the nature of some of the changes I'm making I have to wrap a lot of the token updates in an await.  So it leaves an animation of each token updating individually, rather than all at once.  It's annoying but functional.  I'll investigate a solution.

Merged a change (Than you DavidAremaCarretero) to fix a copy and paste error left behind from the 1.0.19 update.

# Version 1.0.19
Added Actor update hook to update the always HP bar when any actor changes are made.

Added setting to clear the text box after making a change.  So if you want to keep the last value, you can.

# Version 1.0.18
Added Death saving throws for DnD5e
Allow other systems than just DnD5e and PF2e by allowing GM's to set the resource that gets changed.

# Version 1.0.17
Added shift-click to the skull to toggle dead status.
Added the ability for the GM to turn off the players dialog.
Changed it so that any healing will remove the dead status.

# Version 1.0.16
Added setting so that players can turn off the dialog if they don't wish to see it.
Added right-click functions to the skull and heart, to change HP without changing the dead status.
Changed workflow so that skull will add the dead status and heart will clear it.

# Version 1.0.14
Added option to not set the defeated status when clicking the skull.

# Version 1.0.10
Fixed a bug, that if you press the up or down arrows and the text box is blank it would remove all HP.

# Version 1.0.9
Added functionality to use the enter key on the text box.  Using a +number will heal, everything else will hurt.  So if you want to remove HP, you don't need to add a - out front.  Just the number will do.

# Version 1.0.8
Added support for Pathfinder v2.  I'd assumed that a specific function of an actor was available across systems.  It was not.  Added my own function that replicated the bavior and adjusted the project settings so that only DnD5e and PFv2 were available.  Technically any system that uses HP could use the application now, but I'm not sure all the systems that use HP.  If you use one that uses the HP attribute, please contact me and I'll add it to the list.

# Version 1.0.7
Fixed a bug that prevented the window from showing if the window had never been moved before.
