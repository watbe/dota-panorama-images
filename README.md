# dota-econ-items
Extracted Images from pak01/panorama/images/econ/

# How to update this repo

1. Extract vtex_c files from pak01_dir.vpk using [VIDE](http://www.riintouge.com/VIDE/) or your favourite extraction tool.
2. Use `Decompiler.exe` from https://github.com/SteamDatabase/ValveResourceFormat to recursively convert the vtex_c files to PNG or whatever format they're supposed to be in.
3. `Decompiler.exe -i {input_folder} --recursive -i {output_folder}`
4. Run the morgify script to generate JPEGs (and fix weird image outputs by cropping them...)
