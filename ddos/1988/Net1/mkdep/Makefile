#
# Copyright (c) 1988 The Regents of the University of California.
# All rights reserved.
#
# Redistribution and use in source and binary forms are permitted
# provided that the above copyright notice and this paragraph are
# duplicated in all such forms and that any documentation,
# advertising materials, and other materials related to such
# distribution and use acknowledge that the software was developed
# by the University of California, Berkeley.  The name of the
# University may not be used to endorse or promote products derived
# from this software without specific prior written permission.
# THIS SOFTWARE IS PROVIDED ``AS IS'' AND WITHOUT ANY EXPRESS OR
# IMPLIED WARRANTIES, INCLUDING, WITHOUT LIMITATION, THE IMPLIED
# WARRANTIES OF MERCHANTIBILITY AND FITNESS FOR A PARTICULAR PURPOSE.
#
#	@(#)Makefile	5.1 (Berkeley) 10/24/88
#
MAN=	mkdep.0

all mkdep clean depend lint tags:

cleandir:
	rm -f ${MAN}

install: ${MAN}
	install -c -o bin -g bin -m 755 mkdep.sh ${DESTDIR}/usr/bin/mkdep
	install -c -o bin -g bin -m 444 ${MAN} ${DESTDIR}/usr/man/cat1
