# Audio Equalizer

### an eq plugin for frequency manipulation
  
![screenshot](screenshots/screenshot.png)

## Features:
- sliding knobs to modify the tonal quality of audio recordings
- notch slider to amplify or reduce specific frequency ranges

## building the VST3 file:

* [ ] [Download JUCE](https://juce.com/download/) if you don't already have it.

* [ ] `git clone` this repo and open the .jucer file in Projucer.

* [ ] Under the exporters tab, create an export target for your system/IDE.

* [ ] Open the exported project in your IDE and build a Release version.
> [!NOTE]
> If you're building a Debug version, you may need to disable "copy plugin step" under debug settings. This can cause issues if the IDE does not have permission to write to the VST3 Binary Location.

* [ ] The VST3 file should now be available to use under Builds > (your IDE) > ... > Release