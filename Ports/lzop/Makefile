BuildRequires += $(LibDir)/liblzo2.la # static-liblzo

include ../../Library/GNU.mk

Title=		Lzop
Name=		lzop
Version=	1.03
Revision=	0
Site=		http://www.lzop.org
URL=		http://www.lzop.org/download
Source=		$(Name)-$(Version).tar.gz
License=	GPL

define test_inner_hook
$(BinDir)/lzop --version | grep $(Version)
endef
