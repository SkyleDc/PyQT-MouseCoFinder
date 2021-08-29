This software was developped by SkyleDc under Python 3.9.6 with PyCharm.

# ------------------------------ #

You will need PyQt5 :

pip install PyQt5

# ------------------------------ #

If you want to run the executable directly, go into the "Executable" folder and run "MouseCoFinder.exe".

# ------------------------------ #

To build the executable, install Pyinstaller :

pip install pyinstaller

(Optional) If you want to re-convert the .qrc file, use this command :

pyrcc5 images.qrc -o images_qrc.py

Then run the following command :

pyinstaller --onefile --windowed --icon=MouseCoFinder.ico MouseCoFinder.py

The executable will be created in the "dist" folder.
You can now take the .exe and run it anywhere.

# ------------------------------ #

Feel free to use this app as you want, you have full rights on it.