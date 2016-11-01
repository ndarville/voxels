Controls and tools
==================

Camera
-------

Action | Keybind
-------|--------
Rotate | Alt+LMB or RMB
Pan    | Alt+MMB or MMB
Zoom   | Alt+RMB or MMB

Framing
-------

Action             | Keybind
-------------------|--------
Reset framing      | Home
Frame object       | Select and press F
Perpendicular view | Click cube

Drawing
-------
Shift and Ctrl/Cmd alter tool behaviour.

Key   | Tool/Mode
------|----------
B     | Pencil tool
A     | Attach tool
E     | Eraser tool
I     | Eyedropper tool
Space | Slice mode
Ins   | Split selection from object

Tool | Default | Shift | Ctrl/Cmd
-----|---------|-------|---------
Move         | Move | - | Duplicate
Pencil       | Draw voxel | Draw line | Draw rectangle
Attach       | Attach voxel | - | Attach rectangle
Paint        | Paint surface | Paint line | Paint rectangle
Paint bucket | Paints similar voxels | - | -
Freehand     | Paint | Attach | Erase
Object       | Draw | Attach | Erase

Tool | Default | Shift | Ctrl/Cmd
-----|---------|-------|---------
Resize  | Change voxel space | Change symmetrically | -
Extrude | Extend voxel(s) | - | -

Tool | Default
-----|--------
Trace stroke | Connect freehand drawing
Mirror mode  | Symmetric drawing

Some notes:

* Selected areas can't be painted (with Masking on) - which works to protect them if needed.
* You can move in dimensions with arrows instead of clicking the arrows
* Instead of using the Eyedropper tool, you can also hold alt and select a colour
* Slice mode ["2D"] - use slider and hold to slide by "bright edge"
* Assign a keybind by hovering over a setting and pressing the keybind

Menu location | Action | Keybind
--------------|--------|--------
Modify -> Boolean -> Union   | Join objects | -
Modify -> Other -> Split off | Separate selection from object | Ins

Primitive tools
---------------
Arrows and PgUp and PgDown.

Selection
---------

Tool | Default | Shift | Ctrl/Cmd
-----|---------|-------|---------
Select | Highlight | Add to current selection | Deselect

^

* Box select:
    - Good for deleting
* Magic wand
    - Select contriguous voxels with same colour
    - "Contiguous" can be turned off
* Paint selection
* Move

Images
------
* Linear Projection: Projects an image onto a given side of a matrix
* Linear Snapshot: Saves a side view of an object to an image file
