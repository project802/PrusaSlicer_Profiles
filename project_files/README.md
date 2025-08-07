# PrusaSlicer Project Files

Project files are provided here if there are settings changed related to filaments but are outside of the filament configuration. One can make them as separate ini files for print settings, but I find this method more convenient and portable so that any configuration updates to stock print settings are preserved without manual diffs.

## Fiberon PA6-CF20
In addition to the filament profile, the print settings benefit from some tuning. So far I've changed the following from the defaults:
 - "Infill/perimeters overlap" to 45%. PA6-CF20 is not gloopy/runny so at the default of 15%, there are small gaps between perimeters and infill. This closes the gaps well and doesn't push out the perimeters.
 - "Bridge flow ratio" to 0.95. Since the cooling fan is not used, this helps "stretch" out the filament a bit and make for cleaner bridges. Don't bridge too far without supports but for shorter things, this works well.
