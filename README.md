<h1>Change file name</h1>
nice_shield_base.zmk.yml<br>
nice_shield_base.overlay<br>
nice_shield_base.conf<br>


<h1>Change data in the following places</h1>

build.yaml<br><br>
zephyr/module.yml<br><br>
config/corne.conf<br>
config/corne.keymap<br>
config/west.yml<br>
<br>
.github/workflows/build.yml<br>
<br>
boards/shields/nice_shield_base/CMakeLists.txt<br>
boards/shields/nice_shield_base/Kconfig.defconfig<br>
boards/shields/nice_shield_base/Kconfig.shield<br>
boards/shields/nice_shield_base/nice_shield_base.zmk.yml




<h1>Adjusting the image</h1>

<h3>
<i>
Left side top should face to the right<br>
Rotate right side image 180<br>
Default image size is 80x69, max is 126x69
</i>
  <br>
</h3>
  
boards/shields/nice_shield_base/widgets/draw_right_image.c to adjust position after changing height<br>
Default: 80px -> 36 position<br>
To increase height, decrease the position value<br><br>

https://javl.github.io/image2cpp/
