include ../../Library/GNU.mk

Title=		Libpcap
Name=		libpcap
Version=	1.5.3
Revision=	0
Site=		http://www.tcpdump.org
URL=		http://www.tcpdump.org/release
Source=		$(Name)-$(Version).tar.gz
License=	BSD

LicenseFile=	$(SourceDir)/LICENSE

define test_inner_hook
$(BinDir)/pcap-config --cflags --libs | grep $(Prefix)
endef
