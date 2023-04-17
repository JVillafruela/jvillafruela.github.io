all: adresses-osm.html 

adresses-osm.html : adresses-osm.md
	pandoc -t revealjs  -V theme=beige --slide-level=0 -s adresses-osm.md -o adresses-osm.html 