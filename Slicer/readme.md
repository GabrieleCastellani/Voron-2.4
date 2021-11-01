# Start Gcode

    START_PRINT EXTRUDER=[first_layer_temperature] BED=[first_layer_bed_temperature]
    M190 S[first_layer_bed_temperature] ;Wait for bed to reach temp before proceeding
    M109 S[first_layer_temperature]  ;Wait for extruder to reach temp before proceeding


# End Gcode

    End_Print ;end script from macro
