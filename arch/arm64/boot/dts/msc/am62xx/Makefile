#
# Copyright (C) 2023 Avnet Embedded GmbH
#
# This program is free software; you can redistribute it and/or
# modify it under the terms of the GNU General Public License as
# published by the Free Software Foundation version 2.
#
# This program is distributed "as is" WITHOUT ANY WARRANTY of any
# kind, whether express or implied; without even the implied warranty
# of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#


dtb-$(CONFIG_ARCH_K3) += msc-sm2s-am62x-qc-02N0270E-module.dtb
dtb-$(CONFIG_ARCH_K3) += msc-sm2s-am62x-qc-14402C1I-module.dtb

dtb-$(CONFIG_ARCH_K3) += overlay-lvds-ama-070a04.dtb
dtb-$(CONFIG_ARCH_K3) += overlay-lvds-ama-101a07.dtb
dtb-$(CONFIG_ARCH_K3) += overlay-lvds-ama-121a01.dtb
dtb-$(CONFIG_ARCH_K3) += overlay-baseboard-ep1.dtb
dtb-$(CONFIG_ARCH_K3) += overlay-baseboard-vebo.dtb

#Enable support for device-tree overlays
DTC_FLAGS_msc-sm2s-am62x-qc-02N0270E-module += -@
DTC_FLAGS_msc-sm2s-am62x-qc-14402C1I-module += -@
DTC_FLAGS_overlay-lvds-ama-070a04 += -@
DTC_FLAGS_overlay-lvds-ama-101a07 += -@
DTC_FLAGS_overlay-lvds-ama-121a01 += -@
DTC_FLAGS_overlay-baseboard-ep1 += -@
DTC_FLAGS_overlay-baseboard-vebo += -@


always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
