subdir-ccflags-y += -Werror -Wno-error=date-time -Wno-date-time

ccflags-y += -I$(srctree)/drivers/media/platform/tegra
ccflags-y += -I$(srctree)/drivers/video/tegra/camera

obj-$(CONFIG_VIDEO_IMX412) += imx412.o
#obj-$(CONFIG_VIDEO_camera_common) += camera_common.o

obj-$(CONFIG_VIDEO_IMX219) += imx219.o
#obj-$(CONFIG_VIDEO_camera_common) += camera_common.o

obj-$(CONFIG_I2C_IOEXPANDER_PCA9570) += pca9570.o
obj-$(CONFIG_I2C_IOEXPANDER_SER_MAX9295) += max9295.o
obj-$(CONFIG_I2C_IOEXPANDER_DESER_MAX9296) += max9296.o

