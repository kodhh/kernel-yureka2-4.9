# All DTBs
dtb-$(CONFIG_ATH79)			+= ar9132_tl_wr1043nd_v1.dtb
dtb-$(CONFIG_ATH79)			+= ar9331_dpt_module.dtb
dtb-$(CONFIG_ATH79)			+= ar9331_dragino_ms14.dtb
dtb-$(CONFIG_ATH79)			+= ar9331_omega.dtb
dtb-$(CONFIG_ATH79)			+= ar9331_tl_mr3020.dtb

# Force kbuild to make empty built-in.a if necessary
obj-				+= dummy.o

always				:= $(dtb-y)
clean-files			:= *.dtb *.dtb.S
