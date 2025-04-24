# HDRP-URP-Textures-Converter
A tool used to convert HDRP texture maps to URP compatible texture maps
# Overview
A simple tool I made using Substance Designer to automate the remapping process of the HDRP mask map to URP texture maps instead of using the traditional remapping in Photoshop or things like that.

# How it works
1. Download Substance Player, a free software
2. Drag and drop the SBSAR file to Player
3. Choose whether you want to convert from HDRP maps to URP maps or vice versa
4. Upload the required texture maps
5. Press F10 or export the converted textures
6. Don't forget to choose the desired output format uncheck the unneeded maps while exporting
# Limitations
* Due to SBSAR format constraints, all outputs technically export regardless of visibility in the UI. I made a workaround using logic switches to ensure unused outputs are black during export, but it is always recommended to neglect the unwanted exported maps, like the exported HDRP mask map, even if you set the type of conversion to "HDRP to URP".
* The tool lacks batch conversion for multiple textures at once and only works one by one.
