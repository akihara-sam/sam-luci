#
# Copyright (C) 2008-2014 The LuCI Team <luci@lists.subsignal.org>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=Luci for Apple Airplay2 Receiver
LUCI_DEPENDS:=+alsa-utils +shairport-sync-openssl
LUCI_PKGARCH:=all

PKG_NAME:=luci-app-airplay2
PKG_VERSION:=1
PKG_RELEASE:=10

#include ../../luci.mk
include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
