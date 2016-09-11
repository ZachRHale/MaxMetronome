# MaxMetronome
A Metronome App written in Max/MSP
#Using the App
This app was written with the need of practicing contemporary music where time signature changes are frequent.  Therefore, this app uses a "score" to distinguish the measures and there time signatures.

The interesting thing here is that not traditional time signatures can be used as well, such as 3/5, 9/7, 13/24, etc.. This will ultimately make practicing more complicated scores (Ferneyhough) more precise.

#The Score
Scores should be saved into a .txt file in this format
0, 4 4;
1, 3 8;
2, 2 4;
3, 3 16;
4, 2 4;
5, 4 10;
6, stop;

To Explain: 
0, 4 4; <-- measure 0 is measure 1. A 4/4 measure
1, 3 8; <-- a 3/8 measure.
5, 4 10; <-- more complicated.  The bottom number is always the amount of notes inside a WHOLE note. This is sixteenth-note quintuplets
6, stop; <-- stop the Metronome.

A this sample score is included.

