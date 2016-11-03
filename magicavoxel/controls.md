Controls, tools, and interface
==============================

Exporting and importing
-----------------------
The right-most list are pre-made templates stored under `/vox/` in your MagicaVoxel folder. One of them is **monu9**:

![The initial model in MagicaVoxel](../_screenshots/magicavoxel-to-qubicle-initial.png)

Importing this to Qubicle comes with problems, as not all information like colour and orientation is exported.

![The uncoloured result when imported to Qubicle](../_screenshots/magicavoxel-to-qubicle-vox.png)

So what you have to do instead is:

1. Load a template in MagicaVoxel
2. Go to the bottom right and click “Export”
3. Export as “qb” (Qubicle Binary)

This should result in the following:

![The original MagicaVoxel model rendered in Qubicle](../_screenshots/magicavoxel-to-qubicle-qb-fixed.png)

You might get this instead, however:

![A big black box surrounding the imported model in Qubicle](../_screenshots/magicavoxel-to-qubicle-qb-error.png)

This is fixed by selecting the black area with Magic Wand and deleting it, which will reveal the original model.

You might have noticed that the orientation is still off between the two screenshots. To fix that we, flip around the x-axis (“Flip X”).

![The model now matches its MagicaVoxel counterpart perfectly](../_screenshots/magicavoxel-to-qubicle-qb-flipped.png)

You can then go to `Swatches -> Add Used Swatches` to import the model’s colours as a swatch.
