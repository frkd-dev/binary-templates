# 010 Editor Binary Templates

## Apple Keyboard Layout

**Description**

macOS uses a proprietary format for keyboard layouts that has some features not available for other formats like `.keylayout` XML files created by Ukelele app.

For instance, a proprietary format supports a monochrome Retina-friendly vector alpha-numerical indicators rather than a raster icons. Understanding a format would allow to create layout bundles which would have no such restrictions.

**DONE**

- ✅ File header
- ✅ Array of information about layouts
- ✅ Sorted array of layouts by their names
- ✅ Sorted array of layouts by their IDs
- ✅ Unicode ranges
- ✅ Detection of binary plists with info for a vector alpha-numerical indicators
- ✅ Detection of icons

**TODO**

- Decode binary plists. Used for vectored layout indicators
- Decode icons
- A per language keyboard layout data remains undecoded as its format requires further analysis
- Some fields remain unclear in a layout information structure

NOTE: 010 Editor has a template for bplist, so it should be properly imported and used.