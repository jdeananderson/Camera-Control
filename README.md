# Camera Control
Lumens Camera Control Software (Electron App)

This project is a new fork of counteragent / Camera-Control for Lumens IP cameras.
It will be tested with the Lumens VC-A50P

This project is on hold while an alternative is investigated...

Note:  This does NOT use the Lumens C++ SDK API that allows complete control of the camera.  With this project, control of the pan, tilt and zoom speeds could not be found using the vb.htm file on the camera, and so ptz control is limited to minimum speed.  However, speed to presets is set to maximum speed.  This means that the workflow using this software would suggest using presets to get to a camera location, and ptz controls are only used to make fine adjustments to the presets during a live production.

Follow these instructions to install npm on Windows:
https://www.guru99.com/download-install-node-js.html

Go to the project folder.  
Type “npm install”
Once the “package.json” is fixed for the architecture you are on (windows doesn’t have rm, etc)
Type “npm run dist”
That will build the project

Look for the executable in the "dist" folder of the project.

