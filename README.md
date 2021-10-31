# prusaslicer-ratrig

PrusaSlicer settings for RatRig V-Core 3 printer.

## Install

### Using npm

There is `npm` script to copy the distribution files to the PrusaSlicer.
You can run it like this:

```bash
npm run copy $PRUSA_SLICER_PROFILE_FOLDER
```

Replace `$PRUSA_SLICER_PROFILE_FOLDER` with the full path to the PrusaSlicer folder + `resources/profiles`.
For example, if you have installed the application in an `opt` folder in the home directory:

```bash
npm run copy ~/opt/resources/profiles/
```

### Manually

Just copy the content of the `dist` folder to the `resources/profiles` directory in your PrusaSlicer application folder.

## Update

### Using npm

There is `npm` script to update the distribution file in your PrusaSlicer config folder.
Just run:

```bash
npm run update
```

### Manually

Copy the `RatRig.ini` file from the `dist` folder to `$HOME/.config/PrusaSlicer/vendor`.
