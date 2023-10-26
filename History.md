### AFMiJ v 0.1.7 (25/10/2023)
Main changes:
- added filter based on file size when reading multiple files with the "AFM data dir" tool
- "AFM data dir" tool GUI reorganised
- added progression bar when reading multiple files with the "AFM data dir" tool
- added Drag&Drop of AFM image files in the ActionBar window
- added two ActionBar buttons:
	1) propagate height scale from the active image (only from a 32 bits per pixel image) to all other open (32 bits per pixel) images
	2) propagate LUT from the active image (only if image has LUT) to all other open (32 bits per pixel only) images
- added table to log the following image events:
	1) loading images using the "AFM data dir" tool
	2) Drag&Drop of images in the ActionBar window
	3) lbl levelling
	4) plane subtraction
	5) polynomial fit
	6) subtraction of minimum/average value
	7) manual tilt
	(info: image name, slice number, [slice label], event, [value])
- added file to log the same events as above (filename: AFMiJlogTable_YYYYMMDD_HHMMSS.txt, saved in the home directory - $HOME in Linux/OSX, in Windows is C:\Users\<user>)
- added prefs for enabling/disabling table and file log
- added some checks on the prefvars file content, added automatic rebuild with default values if severe problems are detected
- internal changes in the prefs system
- bug corrections
- ij.jar version 1.54f

### AFMiJ v 0.1.4c (03/11/2022)
First release
