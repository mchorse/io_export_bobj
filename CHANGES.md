Changes made to `io_scene_obj` to form `io_export_bobj`:

* Added code to export armatures, animations and vertex weights within `export_obj.py`
* Changed Triangulate Faces option hardcoded to be enabled by default
* Removed completely importing feature (file `import_obj.py`)
* Removed extra OBJ export options that are unnecessary for BOBJ export: Animation, Apply modifiers, Use Modifiers Render Settings, Include Edges, Smooth Groups, Bitflag Smooth Groups, Write Normals, Include UVs, Write Materials, Triangulate Faces, Curves as NURBS, Polygroups, Objects as OBJ Objects, Objects as OBJ Groups, Material Groups, and Scale
* Renamed `export_obj.py` to `export_bobj.py`

If I compiled the list of changes wrong or violated GPL v3 in any way, please let me know at mchorselessrider@gmail.com, that's the first time I'm doing this. Thank you!