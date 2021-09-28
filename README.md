# DynamiVox Wavesurfer Configurations
These are the config files we use for labeling datasets. Dark theme included as-per request.
LAB transcriptions are saved in the HTK format.

Note: don't set these as default as the pitch plot will cause Wavesurfer to quit at start (due to lack of audio).
Dark themes don't have the power plot as the power plot doesn't save/load it's color.

By default, the range of the pitch plot is set to 60-400Hz. If you expect to label audio that is a higher or lower pitch than this range, you'll need to change this.
1. Right-click the pitch plot
2. Click properties.
4. Change the "plot value bounds" to the desired range.
5. Click the "pitch contour" tab.
6. Change the min/max pitch value range to match.
