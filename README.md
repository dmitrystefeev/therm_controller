therm_controller
================

1. ABOUT
therm_controller is my first microcontroller-based project.
It's application for STM32VLDISCOVERY board measures temperature using DS18b20 sensor and prints results to LCD (HD44780-compatible, Winstar wh1602o is used for testing)

2. COMPILATION

- extract ./3rdparty/libs.tar.bz2 to ./3rdparty (./3rdparty/libs direcorty should appear)
- install Sourcery CodeBench Lite for ARM EABI
- edit Makefile:
	set Sourcery CodeBench tools path to TOOLS_PATH, e.g.:
	TOOLS_PATH=/home/user/CodeSourcery/Sourcery_CodeBench_Lite_for_ARM_EABI
	
- type "make" in colsole

3. LOADING TO DEVICE
TBD