# New ports collection makefile for: ghostbsd wallpapers
# Date created:        17 may 2015
# Whom:                angelescuo@yahoo.com
#
# $FreeBSD$
#

PORTNAME=	ghostbsd-wallpapers
PORTVERSION=	1.3
CATEGORIES=	x11-themes

MAINTAINER=	angelescuo@yahoo.com
COMMENT= GhostBSD art for mate flavour
LICENSE = BSD

USE_GITHUB=	yes
GH_ACCOUNT=	GhostBSD

NO_BUILD=	yes

do-install:
	@${MKDIR} -p ${STAGEDIR}${PREFIX}/share/backgrounds/ghostbsd 
	@${CP} -PR ${WRKSRC}/*.jpg ${STAGEDIR}${PREFIX}/share/backgrounds/ghostbsd

.include <bsd.port.mk>
