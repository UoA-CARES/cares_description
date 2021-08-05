# cares_description
This package contains common urdf/srdf/xarco files and meshes used across CARES projects.

NOTE: This package is not intended to hold any src or scripts - DO NOT ADD ANY

## Install
This package has no dependencies or other install requirements beyond ROS 1.0: Note - **NONE** should be added.

## Usage
Add to the common xarco for general use xarco types, push a general use mesh, or xarco for a given compoenent and update the README.
**DO NOT** add source code to this package as it is reserved for ROS message types only!!

## Features

### common.xacro
General purpose functions for building robot urdfs - simplify the overall lines required to generate with base xacro. 

### Stereo Mount
The basic stereo mount used for the UR arms

#### urdf
stereo_mount.xacro

#### mesh
stereo_mount.stl

