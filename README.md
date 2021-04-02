
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
