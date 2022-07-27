# DYVAUX Wavesurfer Configurations
These are the config files we use for labeling datasets. Dark theme included as-per request.
LAB transcriptions are saved in the HTK format.

![image](https://user-images.githubusercontent.com/16280813/155665138-3be5b62f-d580-42d9-a117-5c4569216c6f.png)

You can place these configs into the `%USERPROFILE%\.wavesurfer\1.8\configurations` folder.

Note: **DO NOT** set these as default as the pitch plot will cause Wavesurfer to quit at start (due to lack of audio).
Dark themes don't have the power plot as the power plot doesn't save/load it's color.

By default, the range of the pitch plot is set to 60-400Hz. If you expect to label audio that is a higher or lower pitch than this range, you'll need to change this.
1. Right-click the pitch plot
2. Click properties.
4. Change the "plot value bounds" to the desired range.
5. Click the "pitch contour" tab.
6. Change the min/max pitch value range to match.
