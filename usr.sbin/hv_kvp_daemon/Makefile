# $FreeBSD: release/9.1.0/usr.sbin/hv_kvp_daemon/Makefile  $

HV_KVP_DAEMON_DISTDIR?= ${.CURDIR}/../../contrib/hv_kvp_daemon
.PATH: ${HV_KVP_DAEMON_DISTDIR}

PROG=	hv_kvp_daemon
MAN= 	hv_kvp_daemon.8	

${PROG}: ${PROG}.c
	${CC} -o ${PROG}  ${HV_KVP_DAEMON_DISTDIR}/${PROG}.c 

.include <bsd.prog.mk>
