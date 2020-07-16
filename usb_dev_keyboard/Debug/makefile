################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/ti/ccs1000/ccs/tools/compiler/ti-cgt-arm_20.2.0.LTS

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./startup_ccs.obj" \
"./usb_dev_keyboard.obj" \
"./usb_keyb_structs.obj" \
"./usbdhidkeyb.obj" \
"./device/usbdaudio.obj" \
"./device/usbdbulk.obj" \
"./device/usbdcdc.obj" \
"./device/usbdcdesc.obj" \
"./device/usbdcomp.obj" \
"./device/usbdconfig.obj" \
"./device/usbddfu-rt.obj" \
"./device/usbdenum.obj" \
"./device/usbdhandler.obj" \
"./device/usbdhid.obj" \
"./device/usbdhidgamepad.obj" \
"./device/usbdhidmouse.obj" \
"./device/usbdmsc.obj" \
"./drivers/buttons.obj" \
"./drivers/pinout.obj" \
"./utils/uartstdio.obj" \
"../usb_dev_keyboard_ccs.cmd" \
$(GEN_CMDS__FLAG) \
-llibc.a \
-l"C:/ti/TivaWare_C_Series-2.2.0.295/driverlib/ccs/Debug/driverlib.lib" \
-l"C:/ti/TivaWare_C_Series-2.2.0.295/usblib/ccs/Debug/usblib.lib" \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include device/subdir_vars.mk
-include drivers/subdir_vars.mk
-include utils/subdir_vars.mk
-include subdir_rules.mk
-include device/subdir_rules.mk
-include drivers/subdir_rules.mk
-include utils/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
usb_dev_keyboard.out \

EXE_OUTPUTS__QUOTED += \
"usb_dev_keyboard.out" \

BIN_OUTPUTS += \
usb_dev_keyboard.bin \

BIN_OUTPUTS__QUOTED += \
"usb_dev_keyboard.bin" \


# All Target
all: usb_dev_keyboard.out

# Tool invocations
usb_dev_keyboard.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: "$@"'
	@echo 'Invoking: ARM Linker'
	"C:/ti/ccs1000/ccs/tools/compiler/ti-cgt-arm_20.2.0.LTS/bin/armcl" -mv7M4 --code_state=16 --float_support=FPv4SPD16 -me --define=ccs="ccs" --define=PART_TM4C1294NCPDT --gcc --abi=eabi -z -m"app_TM4C1294NCPDT_ccs.map" --heap_size=0 --stack_size=512 -i"C:/ti/ccs1000/ccs/tools/compiler/ti-cgt-arm_20.2.0.LTS/lib" -i"C:/ti/ccs1000/ccs/tools/compiler/ti-cgt-arm_20.2.0.LTS/include" -i"C:/engineering/usbhidexample/usb_dev_keyboard" --reread_libs --warn_sections --rom_model -o "usb_dev_keyboard.out" $(ORDERED_OBJS)
	@echo 'Finished building target: "$@"'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

usb_dev_keyboard.bin: $(EXE_OUTPUTS)
	@echo 'Building files: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo 'Invoking: ARM Hex Utility'
	"C:/ti/ccs1000/ccs/tools/compiler/ti-cgt-arm_20.2.0.LTS/bin/armhex"  -o "usb_dev_keyboard.bin" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(BIN_OUTPUTS__QUOTED)$(EXE_OUTPUTS__QUOTED)
	-$(RM) "startup_ccs.obj" "usb_dev_keyboard.obj" "usb_keyb_structs.obj" "usbdhidkeyb.obj" "device\usbdaudio.obj" "device\usbdbulk.obj" "device\usbdcdc.obj" "device\usbdcdesc.obj" "device\usbdcomp.obj" "device\usbdconfig.obj" "device\usbddfu-rt.obj" "device\usbdenum.obj" "device\usbdhandler.obj" "device\usbdhid.obj" "device\usbdhidgamepad.obj" "device\usbdhidmouse.obj" "device\usbdmsc.obj" "drivers\buttons.obj" "drivers\pinout.obj" "utils\uartstdio.obj" 
	-$(RM) "startup_ccs.d" "usb_dev_keyboard.d" "usb_keyb_structs.d" "usbdhidkeyb.d" "device\usbdaudio.d" "device\usbdbulk.d" "device\usbdcdc.d" "device\usbdcdesc.d" "device\usbdcomp.d" "device\usbdconfig.d" "device\usbddfu-rt.d" "device\usbdenum.d" "device\usbdhandler.d" "device\usbdhid.d" "device\usbdhidgamepad.d" "device\usbdhidmouse.d" "device\usbdmsc.d" "drivers\buttons.d" "drivers\pinout.d" "utils\uartstdio.d" 
	-@echo 'Finished clean'
	-@echo ' '

post-build:
	-"C:/ti/ccs1000/ccs/utils/tiobj2bin/tiobj2bin" "usb_dev_keyboard.out" "usb_dev_keyboard.bin" "C:/ti/ccs1000/ccs/tools/compiler/ti-cgt-arm_20.2.0.LTS/bin/armofd" "C:/ti/ccs1000/ccs/tools/compiler/ti-cgt-arm_20.2.0.LTS/bin/armhex" "C:/ti/ccs1000/ccs/utils/tiobj2bin/mkhex4bin"
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

