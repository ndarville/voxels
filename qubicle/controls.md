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

* Move tool
    - Ctrl: Duplicate
* Pencil
    - Default: Draw voxel
    - Shift: Draw line
    - Ctrl: Draw rectangle
* Paint tool - paints without drawing new voxels
* Paint bucket tool - paints contiguous voxels with same colour
* Freehand tool
    - Default: Paint
    - Shift: Attach
    - Ctrl: Erase
* Object tool
    - Default. Draw
    - Shift: Attach
    - Ctrl: Erase

^

* Resize tool
    - Changes available voxel space
    - Shift: Change evenly (symmetrically)
* Extrude tool

^

* Trace stroke
    - Connects freehand drawing
* Mirror mode
    - Symmetric drawing

^

* Selected areas can't be painted (with Masking on) - which works to protect them if needed.
* You can move in dimensions with arrows instead of clicking the arrows
* Instead of using the Eyedropper tool, you can also hold alt and select a colour
* Slice mode ["2D"] - use slider and hold to slide by "bright edge"
* Assign a keybind by hovering over a setting and pressing the keybind

^

Menu location | Action | Keybind
--------------|--------|--------
Modify -> Boolean -> Union   | Join objects | -
Modify -> Other -> Split off | Separate selection from object | Ins

Primitive tools
---------------
Arrows and PgUp and PgDown.

Selection
---------
* Shift: Add to current selection
* Ctrl: Deselect

^

* Box select tool
    - Good for deleting
* Magic wand tool
    - Select contriguous voxels with same colour
    - "Contiguous" can be turned off
* Paint selection tool
* Move tool

Images
------
* Linear Projection: Projects an image onto a given side of a matrix
* Linear Snapshot: Saves a side view of an object to an image file
