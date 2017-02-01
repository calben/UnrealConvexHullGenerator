# UnrealConvexHullGenerator

This is a Blender addon that generates convex collision hulls for concave objects in Unreal Engine.


## How to Use

1. Clone this repository
1. Clone hte v-hacd submodule
1. Copy the Python script in the top directory to your Blender addons directory.  For Blender 2.78 this directory will be "Blender Foundation/Blender/2.78/scripts/addons/".  You're at the right place if you see other scripts prefixed with object\_.
1. The addon must be enabled before use.  After copying the script to the addons directory, open Blender and navigate to File > User Preferences > Add-ons.  Object: V-HACD will be featured on the list.  Check its mark to enable the addon and save user settings.
1. Use the addon as instructed for the sister addon in the v-hacd submodule.  This version is convenient for use with Unreal Engine.
