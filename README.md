# This is an old project
I haven't made any changes to this in 2 years.
For any new projects I make, check [here](https://github.com/tomharristech) or [tomharris.tech](https://www.tomharris.tech).

# MLG Soundboard
MLG Soundboard is a Python-based soundboard that uses the `winsound` module to play sounds from the console.

# How it works
Using the `winsound` module, sounds are played directly from the Python shell.  No IDLE required.  Sounds are in the .wav format.
```
import os
os.system("title mlg soundboard w/ montageparodies 420 m8")
os.system("color f0")
import winsound

while True:
    print("1.  Sad music")
    print("2.  Sad music with airhorn")
    print("3.  Airhorn sonata")
```
```
print("50. Dum de dum (23 seconds long)")
    print('"exit" to close.')
    print()
    sound=input("Enter sound number:  ")
    if sound == "1":
        winsound.PlaySound("2sad4me.wav",winsound.SND_FILENAME)
    elif sound == "2":
```

# Compatibility isn't great right now
It's not worth pretending that compatibility is really good with MLG Soundboard right now.  **It isn't.**  It runs only on Windows, primarily because of the use of the `winsound` module (the name speaks for itself) and also because it relies on the `os` module which isn't always present on non-Windows machines.

# Download
To download this, click "Clone or Download" button, then "Download ZIP".  Extract the zip to somewhere where you can keep the soundboard, and don't rename or move any of the files in the folder.  Keep everything in the same place as it is, but you can change the relative directory.
