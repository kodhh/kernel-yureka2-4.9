dtb-$(CONFIG_DTB_PIC32_MZDA_SK)		+= pic32mzda_sk.dtb

dtb-$(CONFIG_DTB_PIC32_NONE)		+= \
					pic32mzda_sk.dtb

obj-y				+= $(patsubst %.dtb, %.dtb.o, $(dtb-y))

# Force kbuild to make empty built-in.a if necessary
obj-				+= dummy.o

always				:= $(dtb-y)
clean-files			:= *.dtb *.dtb.S
