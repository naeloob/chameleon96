#
# Makefile for the fpga framework and fpga manager drivers.
#

# Core FPGA Manager Framework
fpga_mgr-objs				:= fpga-mgr.o fpga-mgr-debugfs.o
obj-$(CONFIG_FPGA)			+= fpga_mgr.o

# FPGA Manager Drivers
obj-$(CONFIG_FPGA_MGR_SOCFPGA)		+= socfpga.o
obj-$(CONFIG_FPGA_MGR_SOCFPGA_A10)	+= socfpga-a10.o
obj-$(CONFIG_ALTERA_PR_IP_CORE)		+= altera-pr-ip-core.o
obj-$(CONFIG_ALTERA_PR_IP_CORE_PLAT)	+= altera-pr-ip-core-plat.o

# FPGA Bridge Drivers
obj-$(CONFIG_FPGA_BRIDGE)		+= fpga-bridge.o
obj-$(CONFIG_SOCFPGA_FPGA_BRIDGE)	+= altera-hps2fpga.o altera-fpga2sdram.o
obj-$(CONFIG_ALTERA_FREEZE_BRIDGE)	+= altera-freeze-bridge.o
obj-$(CONFIG_ALTERA_FREEZE_BRIDGE_PLAT)	+= altera-freeze-bridge-plat.o

# High Level Interfaces
obj-$(CONFIG_FPGA_REGION)		+= fpga-region.o
