AUTOMAKE_OPTIONS = gnu

SUBDIRS = \
	aio-grab \
	devinit \
	evremote2 \
	fp_control \
	fbshot \
	showiframe \
	streamproxy \
	stfbcontrol \
	ustslave \
	gitVCInfo \
	hotplug \
	vfdctl \
	hd-idle \
	libmme_host \
	libmme_image \
	ipbox_eeprom \
	wait4button

if BOXTYPE_TF7700
SUBDIRS += \
	tffpctl \
	tfd2mtd
endif

if ENABLE_EPLAYER3
SUBDIRS += \
	libeplayer3
endif

if ENABLE_SPF
SUBDIRS += \
	spf_tool
endif
