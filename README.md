# MaxMetronome
This app was written with the need of practicing contemporary music where time signature changes are frequent.  Therefore, this app uses a "score" to distinguish the measures and there time signatures. At this time the Metronome is written in Max/MSP but would like to create a web, mobile, and desktop app with these features and a community of scores.

The interesting thing here is that not traditional time signatures can be used as well, such as 3/5, 9/7, 13/24, etc.. This will ultimately make practicing more complicated scores (Ferneyhough) more precise.

Always remember that you must load the score into the app before using.  At this time there is no "save" feature and you must edit the score outside of the app (in TextEdit) and then load it again.

#Using the App
1. Open the Metronome app
2. Load in your .txt score file (instructions below)
3. Click the large speaker icon to enable DSP
4. Push space bar or click the large box to start the metronome

#The Score
***A sample score is included.***
Scores should be saved into a .txt file in this format.
```
0, 4 4;
1, 3 8;
2, 2 4;
3, 3 16;
4, 2 4;
5, 4 10;
6, stop;
```
To Explain: 
```
0, 4 4; 
```
Measure 0 is measure 1. A 4/4 measure
```
1, 3 8; 
```
A 3/8 measure.
```
5, 4 10; 
```
This is more complicated.  The bottom number is always the amount of notes inside a WHOLE note. This is sixteenth-note quintuplets
```
6, stop;
```
Stop the Metronome.

*** Please remember that the numbers in the score and in the app are always 1 off.  Ex.  Measure 2 in the .txt score is going to be your **3rd** measure on the app.



