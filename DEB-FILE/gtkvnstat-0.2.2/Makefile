DESTDIR ="/home/manos/Desktop/gtkvnstat-0.2.2/"

build:

install:
	mkdir -p $(DESTDIR)/usr/bin/ 
	cp gtkvnstat $(DESTDIR)/usr/bin/
	cp GTKvnstat.glade $(DESTDIR)/usr/bin/
	mkdir -p $(DESTDIR)/usr/share/applications/
	cp gtkvnstat.desktop $(DESTDIR)/usr/share/applications/
	mkdir -p $(DESTDIR)/usr/share/pixmaps/
	cp gtkvnstat.png $(DESTDIR)/usr/share/pixmaps/
	cp gtkvnstat_sad.png $(DESTDIR)/usr/share/pixmaps/
	cp gtkvnstat_happy.svg $(DESTDIR)/usr/share/pixmaps/
	
clean:

tar:
	tar cvzf gtkvnstat_0.2.2.tar.gz Makefile gtkvnstat*	

uninstall:
	rm -f $(DESTDIR)/usr/bin/gtkvnstat
	rm -f $(DESTDIR)/usr/bin/GTKvnstat.glade
	rm -f $(DESTDIR)/usr/share/applications/gtkvnstat.desktop
	rm -f $(DESTDIR)/usr/share/pixmaps/gtkvnstat.png
	rm -f $(DESTDIR)/usr/share/pixmaps/gtkvnstat_sad.png
	rm -f $(DESTDIR)/usr/share/pixmaps/gtkvnstat_happy.svg
	
