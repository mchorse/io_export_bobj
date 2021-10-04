This is source code of BOBJ exporter add-on for **Blender 2.7.\***. **BOBJ** is an extension of OBJ format that provides also vertex weights, armature information and bone animations (in form of keyframes). It's used by [S&B Minecraft mod](https://github.com/mchorse/snb).

This add-on is based (i.e. modified to suit my format needs) on the bundled `io_scene_obj` Blender add-on (written by Campbell Barton and Bastien Montagne) which is under **GPL license** (see Python source code for license header). To comply with GPL license, the list of changes from the original source code is available in `CHANGES.md`. 

## Installing

To install this add-on, click on Code 🔽 button on [GitHub](https://github.com/mchorse/io_export_bobj), click **Download ZIP**, open Blender 2.7.\*, File > User Preferences > Add-ons > **Install Add-on From File...** and pick the ZIP you downloaded in Blender's file browser.

After that, the exporter menu item should be available under File > Export. If it's not, make sure **that the add-on is enabled** in Add-ons tab of User Preferences!