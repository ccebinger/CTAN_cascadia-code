ttf2otf:
	./ttf2otf.py *.ttf

change_fontnames:
	fontforge -lang=py -script change_fontnames.py *.otf

autoinst:
	autoinst -target=texmf -vendor=public -typeface=cascadia-code -encoding=OT1,T1,TS1,LY1 CascadiaCod3-*.otf
