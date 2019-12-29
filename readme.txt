C----------------------------------------------------------------------------
C  			          majorBlues                
C----------------------------------------------------------------------------
C
C  This pd patch creates "generative music" in conjunction with an electronic 
C  synthesizer.
C
C  This patch generates fractal melodies with Euclidean rhythms. 
C
C  The fractal melodies are used to generate musical notes.
C
C
C  Please see https://youtu.be/DqQ3ilDy-X4 for an example of it's use.
C
C----------------------------------------------------------------------------
C  Requirements:   Pure Data <https://puredata.info/downloads/pure-data>
C----------------------------------------------------------------------------
C
Usage:  The file majorBlues.pd is the parent patch which contains the 
        rest of the modules.

              Explanation of the primary patches:
midiClockIn:              Generates bangs in sync with an external midi clock 
                          from a synthesiser.
MorseThueSequencex:       Generates a fractal Morse-Thue sequence.
euclidRhythm:             Creates Euclidian rhythms.              

Contributing: Any contributions to this project are welcome.

Acknowledgements: I'd like to thank Acreil for sharing his Pure Data patches. Namely; 
                  pois, rseq, and euclid, to create Euclidian rhythm patches used here.
