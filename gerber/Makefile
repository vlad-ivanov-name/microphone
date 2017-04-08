all:
	/opt/gerbmerge/gerbmerge/gerbmerge.py -s gerbmerge.cfg placement.txt
	rm merged/pcb.zip || true
	cd merged && zip pcb.zip pcb.*

