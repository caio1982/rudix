include ../../Library/GNU.mk

Title=		Ragel State Machine Compiler
Name=		ragel
Version=	6.8
Revision=	0
Site=		http://www.complang.org/ragel/
URL=		http://www.complang.org/ragel/
Source=		$(Name)-$(Version).tar.gz
License=	GPL

define check_inner_hook
cd $(BuildDir)/test ; ./runtests
endef

define test_inner_hook
$(BinDir)/ragel --version | grep $(Version)
endef
