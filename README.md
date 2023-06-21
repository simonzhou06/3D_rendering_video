# 3D_rendering_video
List of different repos to create 3d from videos
## [BlenderNeuralangelo](https://github.com/mli0603/BlenderNeuralangelo)
### Results
When I try to work implement this project everything was working until steps 3 and 4, which are the loading and inspecting the COLMAP data, and the following errors were presented:
Python: Traceback (most recent call last):
File "\neuralangelo_addon.py", line 1095, in execute
load_camera(colmap_data, context)
File "\neuralangelo_addon.py", line 950, in load_camera
bpy.ops.image.open(filepath=blender_img_path, directory=blender_img_path, files=blender_file_names_formatted,
File "C:\Program Files\WindowsApps\BlenderFoundation.Blender_3.5.1.0_x64__ppwjx1n5r4v9t\Blender\3.5\scripts\modules\bpy\ops.py", line 113, in call
ret = _op_call(self.idname_py(), None, kw)
TypeError: Converting py args to operator properties: IMAGE_OT_open.files error converting a member of a collection from a dicts into an RNA collection, failed with: TypeError: Converting a Python list to an RNA collection: keyword "type" missing
