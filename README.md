# Easy Displacement Bake HDA for Houdini 19.5

The Easy Displacement Bake HDA for Houdini is a fast, user-friendly tool designed to streamline and automate the process of baking displacement maps from geometry.

This HDA is implemented in pure VEX, and should also see major speed-up times vs baking in renderers, and the normal conventional baking tools.

## Key Features
- **One-Click Solution**: Just plug in your geometry and hit bake. No need to adjust any settings unless you want to.
- **Automatic Scaling**: The HDA automatically scales based on the scene size and intersection distance, saving you from having to manually adjust parameters.
- **Mesh Analysis**: Advanced users can enable and adjust various masks that give precise, localised smoothing in areas that you may not want displacement to occur.
- **Visualization Options**: Extensive real-time visualization options in the viewport.

## Usage
Just plug in your low-resolution geometry, high-resolution geometry and cage geometry (if any), set your output file path and resolution, adjust the parameters as needed, and hit the bake button. The HDA will take care of the rest!

## Installation
Download the HDA file and install in your `houdini19.5/otls/` folder. For detailed instructions, please refer to the [Houdini documentation](https://www.sidefx.com/docs/houdini/assets/install.html).

## Feedback
If you have any feedback or run into issues, please feel free to open an issue on this GitHub project. I really appreciate your support!

This tool is perfect for artists who need a quick and efficient way to generate displacement maps in Houdini. Enjoy baking!