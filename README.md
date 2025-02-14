This addon activates several render settings for optimal Blender 4.3+ performance. 

---- FEATURES ----
bpy.context.scene.render.use_border = True
bpy.context.scene.render.engine = 'CYCLES'
bpy.context.scene.cycles.device = 'GPU'
bpy.context.scene.cycles.samples = 300
bpy.context.scene.cycles.use_animated_seed = True
bpy.context.scene.cycles.max_bounces = 3
bpy.context.scene.cycles.filter_width = 1.1
bpy.context.scene.render.use_persistent_data = True
bpy.context.scene.render.compositor_device = 'GPU'
bpy.context.scene.cycles.denoising_use_gpu = True
bpy.context.scene.cycles.preview_samples = 100
bpy.context.scene.cycles.use_preview_denoising = True
bpy.context.scene.view_settings.view_transform = 'Khronos PBR Neutral'
bpy.context.scene.view_settings.look = 'Medium High Contrast'


---- INSTALL ----
1. Open Blender
2. Edit > Preferences > Add-on
3. On the dropdown menu, click install from file 
