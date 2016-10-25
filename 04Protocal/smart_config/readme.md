##SDK Version : esp8266_nonos_sdk_v2.0.0_16_07_19
##Requirement: ESP-LAUNCHER BOARD

##Purpose:
Example of ESP-touch or Airkiss.

##Procedure:
1.Copy the examples next to bin/ folder in the SDK folder. THe SDK folder should have folders inside it like : bin, examples, third party...Enter example folder, select the example you want to , run ./gen_misc.sh, and follow the tips and steps.

2.Select 1,1,2,0,2 during compiling step 1 to 5. Then bin files will generate in BIN_PATH folder which is bin/upgrade.


3.Download bin files to ESP-LAUNCHER as below sittings.Download address of each bin files

	blank.bin						0xFE000
	esp_init_data_default.bin		0xFC000
	boot_v1.6.bin					0x00000
	user1.2048.new.2.bin			0x01000
	
	Flash download tool settings.
	CrystalFreq: 26M
	SPI SPEED: 40MHz
	SPID MODE: QIO
	FLASH SIZE: 8Mbit

##Result:
1.Boot up.

2.Connect your phone to router.
#####For ESP-touch,
3.Open ESP-touch APP and configure your device to router.
#####For Airkiss,
4.You can scan the two-dimension code in your wechat.(You can find the two-dimension code in "model two-dimension code.rar.).You can make the board connect to a router in the wechar after scanning the two-dimension code.

##Uart0 log:

	Take Airkiss as an example.
	
	ets Jan  8 2013,rst cause:1, boot mode:(3,2)
