include ../../Library/GNU.mk

Title=		PNG
Name=		libpng
Version=	1.5.14
Revision=	0
Site=		http://www.libpng.org/pub/png/
URL=		http://downloads.sourceforge.net/libpng
Source=		$(Name)-$(Version).tar.xz
License=	BSD

LicenseFile=	$(SourceDir)/LICENSE

define test_inner_hook
$(BinDir)/libpng-config --version
endef
