<h1>Change file name</h1>
nice_shield_base.zmk.yml<br>
nice_shield_base.overlay<br>
nice_shield_base.conf<br>


<h1>Change data in the following places</h1><br>
build.yaml<br>
zephyr/module.yml<br>
config/corne.conf<br>
config/corne.keymap<br>
config/west.yml<br>



.github/workflows/build.yml<br>
boards/shields/nice_shield_base/CMakeLists.txt<br>
boards/shields/nice_shield_base/Kconfig.defconfig<br>
boards/shields/nice_shield_base/Kconfig.shield<br>
boards/shields/nice_shield_base/nice_shield_base.zmk.yml




<h2>Rotate right side image 180, default image size is 80x69, max 126x69</h2><br>
boards/shields/nice_shield_base/widgets/draw_right_image.c to adjust position after changing height<br>
80px -> 36 position<br>
Increase height -> decrease position

