# cs4610-worldgen

## Overview

Generating a gazebo worldfile can be a bit tricky. This code simplifies this process, by providing helpful functions to set up a world file, and even generate one from a txt file. 

## Details
The most helpful functions are:
* `setup_world`: Given an XML parent, this function initalizes a default gazebo world with a checkerboard, sun, and tankbot.
* `add_walls`: Given an XML parent, and a txt file, populates the XML object with gazebo walls.  

## Example

1. Try running `python3 gen_world.py` to generate a `.world` file. 
2. Copy the file into your 'worlds' directory. 
3. Execute the `run_world.sh` file in your working directory. You should now see a hexagonal world with your robot. Try commanding it using your `brain.cc` file. 
