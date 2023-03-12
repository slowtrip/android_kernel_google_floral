debugfs-objs	:= inode.o file.o

ifeq ($(CONFIG_DEBUG_KMEMLEAK),y)
ccflags-y	:= -DCONFIG_DEBUG_FS -DCONFIG_DEBUG_FS_ALLOW_ALL
endif

obj-y		+= debugfs.o
