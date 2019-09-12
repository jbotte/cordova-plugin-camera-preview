# Cordova Plugin Camera Preview Test Fork

This is a test fork of Cordova PLugin Camera Preview, in this fork I will attempt to add option flags which will allow the camera to be hidden by default. 

Current Status

Working on iOS added a parameter hideOnStart bool

On andriod the hide works, but you cannot show it later. If you call the CameraPreview.show() the preview does not show unless i click on the app switcher and then bring the app back to the forfront. I'm assuming this does some sort of ui refresh but I am not an Java Android Developer. Any insight on getting this to work on android is appreciated.
