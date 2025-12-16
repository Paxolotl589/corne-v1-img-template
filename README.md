<h1>Change data in the following places</h1>

build.yaml
zephyr/module.yml

config/corne.conf
config/corne.keymap
config/west.yml

.github/workflows/build.yml

boards/shields/nice_shield_base/CMakeLists.txt
boards/shields/nice_shield_base/Kconfig.defconfig
boards/shields/nice_shield_base/Kconfig.shield
boards/shields/nice_shield_base/nice_shield_base.zmk.yml


<h2>Rotate right side image 180, default image size is 80x69</h2>
boards/shields/nice_shield_base/widgets/draw_right_image.c to adjust position after changing height

80px -> 36 position
Increase height -> decrease position
