# ender3-v2-neo
Configs and notes on my Ender 3 v2 Neo setup with Mainsail/Klipper

## Cura Start G-code:
```
; M190 S{material_bed_temperature_layer_0}
; M109 S{material_print_temperature_layer_0}
start_print BED_TEMP={material_bed_temperature_layer_0} EXTRUDER_TEMP={material_print_temperature_layer_0}
prime_line
```

## Cura End G-code:
```
end_print
power_off_printer
```
