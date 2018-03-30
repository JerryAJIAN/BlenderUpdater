![Screenshot](https://raw.githubusercontent.com/overmindstudios/BlenderUpdater/master/screenshot.png)

# BlenderUpdater
A small crossplatform (Linux, Windows, OSX) Python3 GUI application to check <https://builder.blender.org/download> for
the latest buildbot version. Download and install nightly builds with one click.

## Usage
Specify a folder on your system (e.g. C:\Blender) where the Blender build will be copied to. The tool will not create a new directory by itself, so make sure you create one first.
Then click on the "Version Check" button to see a list of currently available builds. The ones matching your operating system will be highlighted. Click on the desired version to download and copy to your specified folder.
When everything has finished, you'll see a "Start Blender" button to start the new version right away.
<<<<<<< HEAD

![Screenshot](https://raw.githubusercontent.com/overmindstudios/BlenderUpdater/master/run_blender.png)

=======
![Screenshot](https://raw.githubusercontent.com/overmindstudios/BlenderUpdater/master/run_blender.png)
>>>>>>> 93cbf9ab8fc2d51c83af02f81589f09e6b1a2fca
In case there is an update for BlenderUpdater, you'll see a button in the top right corner to go to the download page.
![Screenshot](https://raw.githubusercontent.com/overmindstudios/BlenderUpdater/master/app_update.png)

## Compiled releases
### Windows
You can grab the release .zip, extract it and execute BlenderUpdater.exe.

### Linux & OSX
Frozen binary files for Linux and OSX coming soon. As of now, just run "python BlenderUpdater.py" on your system (make sure that the dependencies are met).

## Known limitations
Due to UAC starting in Windows Vista, you cannot use the "C:\Program Files\" directory as a
normal user. Please choose some other destination on your hard drive OR right-click
the application and choose "Run as Administrator" to be able to access those special folders.

## Freezing
Freezing is done via pyinstaller (`pyinstaller --icon=icon.ico --onefile --windowed BlenderUpdater.py`)

## Dependencies
Built with PyQt5 for the UI and Beautiful Soup for HTML parsing.

## Download
<<<<<<< HEAD
Here's the latest release: <https://github.com/overmindstudios/BlenderUpdater/releases/latest>

## Disclaimer
This application was developed for in-house usage at
=======
Here's the latest release: https://github.com/overmindstudios/BlenderUpdater/releases/latest
>>>>>>> 93cbf9ab8fc2d51c83af02f81589f09e6b1a2fca
