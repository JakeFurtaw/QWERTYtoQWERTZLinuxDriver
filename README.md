# Making a "QWERTY" to "QWERTZ" Linux Keyboard Driver
## Description: 
- Rewriting the Linux keyboard driver to use the "QWERTZ" keyboard style versus the more common "QWERTY" keyboard style. 
-----------------------------------------------------------------------------------------------------
## How:
- We are scanning the code of the linux keyboard driver to find where the actual keycodes are set for the keyboard.
- Then we are replacing the scancodes in the driver to change key functionality for the different keys required by the QWERTZ driver.
- After this we will test the driver on my laptop to make sure they keys have been changed within the driver code.
