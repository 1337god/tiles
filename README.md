# Tiles for [dev3map](https://dev3map.github.io/)

Tiles are stored in the format `<tileset name>/z<zoom>/<x>,<z>.png` where `x` and `z` are the coordinates of that region, and `zoom` is 0 for one pixel per block and decreases by 1 every time the viewport width is doubled.

All tiles are 256x256 pixels in size, so at zoom level 0 each tile contains the data from one Minecraft `.mca` region file.

