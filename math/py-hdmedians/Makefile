# $FreeBSD$

PORTNAME=	hdmedians
PORTVERSION=	0.14.1
CATEGORIES=	math python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	yuri@FreeBSD.org
COMMENT=	High-dimensional medians

LICENSE=	APACHE20

BUILD_DEPENDS=	${PYNUMPY} \
		${PYTHON_PKGNAMEPREFIX}nose>=1.0:devel/py-nose@${PY_FLAVOR}
RUN_DEPENDS=	${PYNUMPY}

USES=		python:3.6+
USE_PYTHON=	autoplist cython distutils

post-install:
	@${STRIP_CMD} ${STAGEDIR}${PYTHON_SITELIBDIR}/hdmedians/geomedian*.so

.include <bsd.port.mk>
