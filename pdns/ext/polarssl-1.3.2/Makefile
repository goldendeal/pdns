
DESTDIR=/usr/local
PREFIX=polarssl_

.SILENT:

all:
	cd library  && $(MAKE) all && cd ..

lib:
	cd library  && $(MAKE) all && cd ..

install:
	
uninstall:

clean:
	cd library  && $(MAKE) clean && cd ..

check:

distdir:
	mkdir -p $(distdir)
	cp ChangeLog LICENSE  Makefile  README.rst  $(distdir)
	mkdir $(distdir)/library
	mkdir -p $(distdir)/include/polarssl
	cp library/Makefile library/*.c $(distdir)/library
	cp include/polarssl/*.h $(distdir)/include/polarssl
