#
# Copyright (C) 2016-2017 GitHub 
#
# This is free software, licensed under the GNU General Public License v3.
# See /LICENSE for more information.

define Package/default-settings
  SECTION:=luci
  CATEGORY:=LuCI
  TITLE:=LuCI support for Default Settings
  PKGARCH:=all
  DEPENDS:=+luci-base +luci +@LUCI_LANG_zh-cn
endef



define Package/default-settings/install
	
	$(INSTALL_BIN) ./files/zzz-default-settings
endef

$(eval $(call BuildPackage,default-settings))
