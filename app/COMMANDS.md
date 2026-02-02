# Build Commands for Corne ZMK split keyboard

**central (left) half**
west build -d build/left -b nice_nano -- -DSHIELD="corne_left nice_view_adapter nice_view"

**peripheral (right) half**
west build -d build/right -b nice_nano -- -DSHIELD="corne_right nice_view_adapter nice_view"
