# QWERTYtoQWERTZLinuxDriver
Description: 
-Rewriting the Linux keyboard driver to use the "QWERTZ" style versus the more common "QWERTY" style. 
-----------------------------------------------------------------------------------------------------
# How:
-We are scanning the code to find where the actual keycodes are set for the keyboard.
-Then we are replacing the scancodes in the driver to change key functionality.
-After this we will test on a VM to ensure the driver functions as we intend.
