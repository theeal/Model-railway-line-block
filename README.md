# Model-railway-line-block

I'm going to link some parts of the project to YouTube

Signal states [main signal (pre signal if combined) 
0 Stopp
1 run (wait stop) 
2 run (wait turn) 
3 run (wait run) 

Funktion.
Distance 1000m nomaly to pre signal 
Staton A | pre signal | block signal/s | Station B

Resting, Line direction (example ->) 
Both stations have Direton memory.
station B sends receiving / clearance signal <-
If the track is occupied this signal is cut.
Block signal read the signal. Lit the green light, (1)
If green light <- sen one block clear. 
Staton A review block clear, sends -> Line clear 
Block signal pass through line clear. 
Station B receives line clear. Is now able to turn block in the other direction. 
