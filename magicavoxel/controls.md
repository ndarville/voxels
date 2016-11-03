Controls, tools, and interface
==============================

Exporting and importing
-----------------------
The right-most list are pre-made templates stored under `/vox/` in your MagicaVoxel folder.

Importing this into Qubicle comes with problems, as not all information like colour and orientation is exported.

![The initial model in MagicaVoxel](../_screenshots/magicavoxel-to-qubicle-initial.png)

![The uncoloured result when imported to Qubicle](../_screenshots/magicavoxel-to-qubicle-vox.png)

so what you have to do instead is:

1. Load a template in MagicaVoxel
2. Go to the bottom right and click “Export”
3. Export as “qb” (Qubicle Binary)

This should result in the following:

![The original MagicaVoxel model rendered in Qubicle](../_screenshots/magicavoxel-to-qubicle-qb-fixed.png)

You might get this instead, however:

![A big black box surrounding the imported model in Qubicle](../_screenshots/magicavoxel-to-qubicle-qb-error.png)

This is fixed by selecting the black area with Magic Wand and deleting it, which will reveal the original model.

You can then go to `Swatches -> Add Used Swatches` to import the model colours as a swatch.
