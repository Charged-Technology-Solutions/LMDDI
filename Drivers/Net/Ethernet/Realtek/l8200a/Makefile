#
# Makefile for Realtek® L8200A (standalone module)
#

# Kernel build directory (adjust if different)
KDIR ?= /lib/modules/$(shell uname -r)/build

# Module name
MODULE_NAME := l8200a

# Source files
obj-m := $(MODULE_NAME).o
$(MODULE_NAME)-objs := l8200a.o l8200a_phy.o l8200a_hw.o l8200a_ethtool.o

# Build target
all:
	$(MAKE) -C $(KDIR) M=$(PWD) modules

# Clean target
clean:
	$(MAKE) -C $(KDIR) M=$(PWD) clean
