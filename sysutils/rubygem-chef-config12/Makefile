# Created by: Po-Chuan Hsieh <sunpoet@FreeBSD.org>
# $FreeBSD$

PORTNAME=	chef-config
PORTVERSION=	12.22.5
CATEGORIES=	sysutils rubygems
MASTER_SITES=	RG
PKGNAMESUFFIX=	12

MAINTAINER=	zi@FreeBSD.org
COMMENT=	Default configuration and config loading library for Chef

LICENSE=	APACHE20
LICENSE_FILE=	${WRKSRC}/LICENSE

BROKEN=		Please use sysutils/rubygem-chef-config instead
EXPIRATION_DATE=	2021-01-31

RUN_DEPENDS=	rubygem-addressable>=0:www/rubygem-addressable \
		rubygem-fuzzyurl>=0:www/rubygem-fuzzyurl \
		rubygem-mixlib-config>=2.0:devel/rubygem-mixlib-config \
		rubygem-mixlib-shellout>=2.0:devel/rubygem-mixlib-shellout \
		rubygem-tomlrb>=1.2:textproc/rubygem-tomlrb

CONFLICTS_INSTALL=	rubygem-chef-config \
			rubygem-chef-config[0-9]*

NO_ARCH=	yes
USE_RUBY=	yes
USES=		gem

.include <bsd.port.mk>
