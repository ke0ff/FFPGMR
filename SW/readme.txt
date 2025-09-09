This is a Tiva TM4C123GH6PM Project, bare-metal, CLI-based programmer engine that communicates via a UART-serial (USB-COM port) terminal emulator.
The CCS6 base-project is zipped, then source files are committed daily as work progresses. Unzip the archive, then place all of the individual
source-file commits into the appropriate folder (replacing the existing source files).

MCU: TM4C123GH6PM (on a TI LaunchPad eval board)
Build settings:
-mv7M4 --code_state=16 --float_support=FPv4SPD16 -me -g --gcc --define=ccs="ccs" --define=PART_TM4C123GH6PM --diag_wrap=off --diag_warning=225 --display_error_number --abi=eabi -z -m"FFPGMR.map" --stack_size=5120 --heap_size=2560 -i"C:/ti/ccsv6/tools/compiler/arm_15.12.3.LTS/lib" -i"C:/ti/ccsv6/tools/compiler/arm_15.12.3.LTS/include" --reread_libs --diag_wrap=off --warn_sections --display_error_number --xml_link_info="FFPGMR_linkInfo.xml" --rom_model
