#
# Makefile for ACPM.
#

obj-$(CONFIG_EXYNOS_ACPM)    += acpm.o acpm_ipc.o
obj-$(CONFIG_EXYNOS_ACPM_MFD)	+= acpm_mfd.o
obj-$(CONFIG_EXYNOS_ACPM_S2D)	+= acpm_s2d.o
CFLAGS_acpm.o += $(DISABLE_LTO_CLANG)
KBUILD_CFLAGS   += -Os
