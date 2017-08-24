Experiments around work of Sony CSL, Pachet et. al.

Best results come from editing /etc/timidity/timidity.cfg

and using 

source /etc/timidity/fluidr3\_gm.cfg

instead of the default 

source /etc/timidity/freepats.cfg

This may require the fluid-soundfont package, which can be installed with

sudo apt-get install fluidsynth

Requirements:
numpy
music21
pretty\_midi
python 2.7 (3 may work, not tested)

References:
https://arxiv.org/abs/1609.05152
https://www.csl.sony.fr/downloads/papers/2011/pachet-09c.pdf
http://francoispachet.fr/texts/12BarBluesOmnibook.txt
https://www.csl.sony.fr/downloads/papers/uploads/pachet-02f.pd
