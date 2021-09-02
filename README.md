# Mouse Coordinates Finder

This tool will allow you to track your mouse onscreen position and will return x and y position.
This software was developped by SkyleDc under Python 3.9.6 with PyCharm.

# Dependencies

You will need PyQt5 :

`pip install PyQt5`

# Running the executable

If you want to run the executable directly, go into the "Executable" folder and run "MouseCoFinder.exe".

# Build the executable

To build the executable, install Pyinstaller :

`pip install pyinstaller`

(Optional) If you want to re-convert the .qrc file, use this command :

`pyrcc5 images.qrc -o images_qrc.py`

Then run the following command :

`pyinstaller --onefile --windowed --icon=MouseCoFinder.ico MouseCoFinder.py`

The executable will be created in the "dist" folder.
You can now take the .exe and run it anywhere.

# "Pseudo-License" (This is worth nothing but I'm too lazy to make a real license file)

Feel free to use this app as you want, you have full rights on it.