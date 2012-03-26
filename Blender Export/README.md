Blender Header file Export Script
==================================

Requirements
-------------
* Tested on Blender 2.62 for Mac

Installation
--------------
Installing the Blender Objective-C Export Script:

    1. Launch Blender
    2. Select "User Preferences" from the File menu
    3. Navigate to the "Add-Ons" tab
    4. In the lower-left corner of the window, click the button that reads "Install Add-On…"
    5. Find io_export_objective_c_header.py in your file system and select it
    6. Click the "Import/Export" button on the left side to show only the Import/Export add-ons
    7. Look for an item called "Import/Export: Export Objective-C Header (.h)". Click the checkbox associated with that row to enable the script
    8. Close the User Preferences window
    9. Select "Save User Settings" from the File menu

Usage
------
Now, under the File->Export menu, there will be an option to export the selected object as an Objective-C header file.

When you add the add-on to the application, it will copy the script into the application's bundle, however whether a script is enabled is stored in Blender's user settings, which is why it's important to save the user settings as a final step. When adding an add-on, you should make sure not to change anything else besides the steps above until you've saved the user settings. Any other changes you make will get saved as the default Blender step as well.


License
--------
### Modifications ###
Some patches added by David Gavilan. Check revision history.

### Original licence ###
Copyright (c) 2010 ['Jeff LaMarche']

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
