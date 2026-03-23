This is a qmk firmware for a modified version of a cygnus split keyboard (3x5 version) (https://github.com/tupinikeebs/cygnus/tree/main/Cygnus%20v1.0)

Changes include: <br>
	-adding an LED to each half for layer indication <br>
	-using a promicro rp2040 <br>
	-the columns are connected to the board starting one pin lower than normal: <br>
		[ "GP27", "GP26", "GP22", "GP20", "GP23" ], instead of [ "GP28", "GP27", "GP26", "GP22", "GP20" ] (by accident) <br>

The keymap in this config is placeholder and needs to be modified according to your liking.
	
To build place the folder in qmk_firmware/keyboards and run 
	"qmk compile -kb cygnus_mod -km default"
	
Then flash as normal for a rp2040 board (https://github.com/mechboardsguides/flashing-rp2040-promicro)
