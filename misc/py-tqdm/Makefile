# $FreeBSD$

PORTNAME=	tqdm
PORTVERSION=	4.54.1
CATEGORIES=	misc
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	sunpoet@FreeBSD.org
COMMENT=	Fast, extensible progress bar for Python

LICENSE=	MIT MPL20
LICENSE_COMB=	multi
LICENSE_FILE_MIT=	${WRKSRC}/LICENCE

BUILD_DEPENDS=	${PYTHON_PKGNAMEPREFIX}setuptools_scm>=3.4:devel/py-setuptools_scm@${PY_FLAVOR}

USES=		python
USE_PYTHON=	autoplist concurrent distutils

NO_ARCH=	yes

.include <bsd.port.mk>
