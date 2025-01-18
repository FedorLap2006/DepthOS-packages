CC?=gcc

init: init.c
	$(CC) -std=c11 init.c -o init

install: init
	mkdir -p $(DESTDIR)/sbin/
	install -p init $(DESTDIR)/sbin/

