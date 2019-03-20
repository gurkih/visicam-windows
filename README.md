# visicam-windows
scripts required to easily set up visicam on windows

# setup
- clone the repository from https://github.com/t-oster/VisiCam
- DO NOT install the requirements listed there, install them using the provided choco.bat
- build visicam using ant (as described on the VisiCam page)
- move the documents folder to %USERPROFILE%\Documents
- move the desktop folder to %USERPROFILE%\Desktop

# configuration
- set the path in %USERPROFILE%\Documents\visicam.bat to your VisiCam directory
- configure VisiCam to use a user-defined image command
- determine how your webcam shows up in ffmpeg by using "ffmpeg -list_devices true -f dshow -i dummy" in a command line
- enter the "alternative name" into %USERPROFILE\Documents\grabimage.bat
- set the command to %USERPROFILE%\Documents\grabimage.bat
- set the image name to img.jpg

# running visicam
- run the batch file on your desktop :-)
