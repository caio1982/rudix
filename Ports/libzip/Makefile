include ../../Library/GNU.mk

Title=		libzip
Name=		libzip
Version=	0.10.1
Revision=	1
Site=		http://nih.at/libzip/
URL=		http://nih.at/libzip/
Source=		$(Name)-$(Version).tar.bz2
License=	BSD

LicenseFile=	$(SourceDir)/LICENSE

define test_inner_hook
/usr/local/bin/zipcmp -h
/usr/local/bin/zipmerge -h
endef
