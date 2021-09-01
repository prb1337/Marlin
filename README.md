
#Schritte

 1. Marlin ausgecheckt
 2.  Vordefinierte Config ausgecheckt und in Marlin Ordner kopiert
 3. Für BLTouch https://youtu.be/eF060dBEnfs?t=413
	 #define BLTOUCH  
	 #define AUTO_BED_LEVELING_BILINIAR (den anderen Eintrag auskommentiert)  
	 #define Z_SAFE_HOMING  
	 #define Z_MIN_PROBE_USES_Z_MIN_ENDSTOP_PIN <- auskommentiert!!!!  
	 #define USE_PROBE_FOR_Z_HOMING  
	 #define Z_MIN_PROBE_PIN PC14   < Name des Pins, in dem der Sensor eingesteckt ist


##
Unterschiede zu Reddit Guide:  
Feld | Wert Guide | Wert in Config
--- | --- | ---
EXTRUDE_MAXLENGTH  | 200 | 600
CONTROLLER_FAN_PIN | Aktivieren und PC7 | Deaktiviert



## Hilfreiche Links
* https://www.reddit.com/r/ender3/comments/h8y1ia/marlin_20x_guide_skr_mini_e3_v20_ender_3/  
=> PID Autotune:   
https://www.reddit.com/r/3Dprinting/comments/h8xqrn/pid_autotune/  
=> BL Touch  
https://www.reddit.com/r/3Dprinting/comments/hx6ab3/bed_leveling_bltouch_inductive_sensor/


* https://kay3d.com/pages/the-correct-way-to-configure-a-bltouch
* https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3
* https://www.reddit.com/r/ender3/comments/aiebc7/better_cura_start_gcode_for_bltouch/
* https://www.youtube.com/watch?v=y_1Kg45APko


