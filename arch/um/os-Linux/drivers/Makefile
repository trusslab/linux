# SPDX-License-Identifier: GPL-2.0
# 
# Copyright (C) 2000, 2002 Jeff Dike (jdike@karaya.com)
#

ethertap-objs := ethertap_kern.o ethertap_user.o
tuntap-objs := tuntap_kern.o tuntap_user.o
octopos_mailbox_interface-objs := octopos_mailbox_interface_user.o

obj-y = 
obj-$(CONFIG_UML_NET_ETHERTAP) += ethertap.o
obj-$(CONFIG_UML_NET_TUNTAP) += tuntap.o
obj-y += octopos_mailbox_interface.o

include arch/um/scripts/Makefile.rules
