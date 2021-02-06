################################################################################
# Automatically-generated file. Do not edit!
################################################################################

export WINEDEBUG=-all

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include zcl-framework-core/subdir.mk
-include update-tc-link-key/subdir.mk
-include strong-random/subdir.mk
-include simple-main/subdir.mk
-include serial/EFR32/subdir.mk
-include serial/subdir.mk
-include scan-dispatch/subdir.mk
-include nvm3/EFR32/subdir.mk
-include nvm3/subdir.mk
-include network-steering/subdir.mk
-include mbedtls/EFR32/subdir.mk
-include hal-library/EFR32/subdir.mk
-include emlib/subdir.mk
-include emdrv/subdir.mk
-include ember-minimal-printf/subdir.mk
-include efr32/subdir.mk
-include debug-jtag/EFR32/subdir.mk
-include debug-basic-library/EFR32/subdir.mk
-include coexistence-stub/EFR32/subdir.mk
-include ccm-encryption/subdir.mk
-include antenna-stub/subdir.mk
-include subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(MSA_UPPER_DEPS)),)
-include $(MSA_UPPER_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S79_DEPS)),)
-include $(S79_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(MSA_DEPS)),)
-include $(MSA_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(S79_UPPER_DEPS)),)
-include $(S79_UPPER_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: pre-build main-build

# Main-build Target
main-build: ZigbeeMinimalSoc.out

# Tool invocations
ZigbeeMinimalSoc.out: $(OBJS) $(USER_OBJS)
	@echo 'Building target: $@'
	@echo 'Invoking: IAR Linker for ARM'
	ilinkarm $(OBJS) $(USER_OBJS) -o "ZigbeeMinimalSoc.out" --config "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//platform/base/hal/micro/cortexm3/efm32/iar-cfg.icf" --config_def NULL_BTL=1 --config_def FLASH_SIZE=262144 --config_def RAM_SIZE=32768 --config_def SIMEEPROM_SIZE=36864 --config_def LOCKBITS_IN_MAINFLASH_SIZE=0 --config_def EMBER_MALLOC_HEAP_SIZE=0 --config_def HEADER_SIZE=256 --config_def PSSTORE_SIZE=0 --config_def LONGTOKEN_SIZE=0 --config_def BTL_SIZE=16384 --no_wrap_diagnostics "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/source-route-stub-library-cortexm3-iar-efr32mg1b-rail/source-route-stub-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//platform/emdrv/nvm3/lib/libnvm3_CM4_iar.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/debug-extended-stub-library-cortexm3-iar-efr32mg1b-rail/debug-extended-stub-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/debug-basic-library-cortexm3-iar-efr32mg1b-rail/debug-basic-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/cbke-library-dsa-verify-283k1-stub-cortexm3-iar-efr32mg1b-rail/cbke-library-dsa-verify-283k1-stub.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//platform/radio/rail_lib/autogen/librail_release/librail_efr32xg1_iar_release.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/install-code-library-stub-cortexm3-iar-efr32mg1b-rail/install-code-library-stub.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/zigbee-r22-support-stub-library-cortexm3-iar-efr32mg1b-rail/zigbee-r22-support-stub-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/cbke-163k1-stub-library-cortexm3-iar-efr32mg1b-rail/cbke-163k1-stub-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/zll-stub-library-cortexm3-iar-efr32mg1b-rail/zll-stub-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/packet-validate-library-cortexm3-iar-efr32mg1b-rail/packet-validate-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/multi-network-stub-library-cortexm3-iar-efr32mg1b-rail/multi-network-stub-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/gp-stub-library-cortexm3-iar-efr32mg1b-rail/gp-stub-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/cbke-library-dsa-sign-stub-cortexm3-iar-efr32mg1b-rail/cbke-library-dsa-sign-stub.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/binding-table-library-cortexm3-iar-efr32mg1b-rail/binding-table-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/zigbee-pro-stack-cortexm3-iar-efr32mg1b-rail/zigbee-pro-stack.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/cbke-library-dsa-verify-stub-cortexm3-iar-efr32mg1b-rail/cbke-library-dsa-verify-stub.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/security-library-link-keys-stub-cortexm3-iar-efr32mg1b-rail/security-library-link-keys-stub.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/end-device-bind-stub-library-cortexm3-iar-efr32mg1b-rail/end-device-bind-stub-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/cbke-stub-library-cortexm3-iar-efr32mg1b-rail/cbke-stub-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/sim-eeprom2-to-nvm3-upgrade-stub-library-cortexm3-iar-efr32mg1b-rail/sim-eeprom2-to-nvm3-upgrade-stub-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/cbke-283k1-stub-library-cortexm3-iar-efr32mg1b-rail/cbke-283k1-stub-library.a" "D:/SiliconLabs/SimplicityStudio/v4/developer/sdks/gecko_sdk_suite/v2.7//protocol/zigbee/build/hal-library-cortexm3-iar-efr32mg1b-rail/hal-library.a" --entry __iar_program_start --map "D:/ZigBee/ZigbeeMinimalSoc/IAR ARM - Default - EFR32MG1B232F256GM48/ZigbeeMinimalSoc.map" --log_file "D:/ZigBee/ZigbeeMinimalSoc/IAR ARM - Default - EFR32MG1B232F256GM48/ZigbeeMinimalSoc.log" --log initialization,modules,sections,veneers --diag_suppress=Lp012 --redirect _Printf=_PrintfSmallNoMb --redirect _Scanf=_ScanfFullNoMb  
	ielftool --srec --verbose "ZigbeeMinimalSoc.out" "ZigbeeMinimalSoc.s37"  
	ielftool --ihex --verbose "ZigbeeMinimalSoc.out" "ZigbeeMinimalSoc.hex"  
	ielftool --bin --verbose "ZigbeeMinimalSoc.out" "ZigbeeMinimalSoc.bin"
	@echo 'Finished building target: $@'
	@echo ' '
	$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(ASM_UPPER_DEPS)$(MSA_UPPER_DEPS)$(EXECUTABLES)$(OBJS)$(ASM_DEPS)$(S79_DEPS)$(S_DEPS)$(S_UPPER_DEPS)$(MSA_DEPS)$(C_DEPS)$(S79_UPPER_DEPS) ZigbeeMinimalSoc.out
	-@echo ' '

pre-build:
	-cmd //c 'D:\ZigBee\ZigbeeMinimalSoc/ZigbeeMinimalSoc-prebuild.bat' 'ZigbeeMinimalSoc' 'D:/ZigBee/ZigbeeMinimalSoc' 'C:/Program Files (x86)/IAR Systems/Embedded Workbench 8.0/arm' 'D:\SiliconLabs\SimplicityStudio\v4'
	-@echo ' '

post-build:
	-cmd //c 'D:\ZigBee\ZigbeeMinimalSoc/ZigbeeMinimalSoc-postbuild.bat' 'ZigbeeMinimalSoc' 'D:/ZigBee/ZigbeeMinimalSoc' 'C:/Program Files (x86)/IAR Systems/Embedded Workbench 8.0/arm' 'D:\SiliconLabs\SimplicityStudio\v4'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY: main-build pre-build post-build

-include ../makefile.targets
