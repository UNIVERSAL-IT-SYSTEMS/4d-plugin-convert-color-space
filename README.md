# 4d-plugin-convert-color-space
Convert RGB obtained from picker to generic RGB

Converts the RGB value returned from ```Select RGB color``` to its equivalent device RGB (what you'd pass to ```OBJECT SET RGB COLORS```).

```
$color:=Convert color space ($color;To picker color)
$color:=Convert color space ($color;From picker color)
```

**Note**: The conversion is lossy and not symmetrical.
