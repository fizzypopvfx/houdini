# Quixel Megascans to MaterialX
Shelf tools to quickly import Quixel Megascans surfaces into MaterialX for use in Solaris and Karma.

These tools look for `Albedo`, `Roughness`, `Normal`, and `Displacement` maps only. Quixel seems to prefer these four maps in their plugin but more can be manual added of course once the material is set up.

## YouTube Video
https://www.youtube.com/watch?v=4vdZoGIoyUc

## Installation
1. Copy all `.shelf` files to `houdini20.5\toolbar` (usually in Documents on Windows)
2. Launch Houdini
3. Click the `+` icon on the shelf tools
4. Go to `Shelves -> Mega MtlX (FIZZYPOP!)` and tick it
5. A new shelf with the tools will appear

## Megascans Folder to MaterialX
Converts a downloaded surface from FAB.com to MaterialX. Click either tool and select the downloaded folder e.g., `fresh_snow_seylmwd_4k`. Click OK and the new shader will be available in `/mat` and can be copied to your Solaris Material Library node.

## Principled Shader to MaterialX
Two tools that convert the Principled Shaders created by the Megascans Houdini plugin when importing directly from Quixel Bridge. Highlight the Principled Shader and then click on either of these tools to get standard MaterialX Shader or a Hex-Tiled Triplanar Shader.