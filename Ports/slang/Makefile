include ../../Library/GNU.mk
ifeq ($(OSXVersion),10.6)
RUDIX_UNIVERSAL=no
endif

Title=		S-Lang
Name=		slang
Version=	2.2.4
Revision=	2
Site=		http://www.jedsoft.org/slang/
URL=		ftp://space.mit.edu/pub/davis/slang/v2.2
Source=		$(Name)-$(Version).tar.gz
License=	GPL

MakeFlags=

define install_post_hook
mv $(InstallDir)$(SysConfDir)/slsh.rc \
	$(InstallDir)$(SysConfDir)/slsh.rc.default
endef

define test_inner_hook
$(BinDir)/slsh --version
endef
