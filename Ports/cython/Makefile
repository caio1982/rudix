include ../../Library/Python.mk

Title=		Cython
Name=		cython
Version=	0.20.1
Revision=	0
Site=		http://www.cython.org/
URL=		http://www.cython.org/release
Source=		Cython-$(Version).tar.gz
License=	Apache License

ReadMeFile=	$(SourceDir)/README.txt
LicenseFile=	$(SourceDir)/LICENSE.txt

define test_inner_hook
$(BinDir)/cython --version
endef
