# Created by: Antonio Carlos Venancio Junior (<antonio@inf.ufsc.br>)
# $FreeBSD$

PORTNAME=	Image_Barcode
PORTVERSION=	1.1.3
CATEGORIES=	graphics www pear

MAINTAINER=	joneum@bsdproject.de
COMMENT=	PEAR class for barcode generation

USE_PHP=	gd
USES=		pear php

OPTIONS_DEFINE=		PEAR_PHP_COMPAT
PEAR_PHP_COMPAT_DESC=	PEAR::PHP_Compat support

PEAR_PHP_COMPAT_RUN_DEPENDS=	${PEARDIR}/PHP/Compat.php:devel/pear-PHP_Compat

.include <bsd.port.mk>
