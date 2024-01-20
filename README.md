# EventDrivenSimulation
This Project allows the simulation of balls within a confined space with initial velocities specified for a given time period.
It uses event based simulation to fast track the calculation process.
This is done using heap data structure over pointer to future collision events, and then the most recent future event is picked and the balls involved are recalculated for future collisions.

Steps to Use:
1) Input File:
60(Bound area x-axis)
60(Bound area x-axis)
6(Number of Balls)
(Initial X-Position,Y-Position, Radius, X-Veloctiy,Y-Velocity)
32.5 11.5 1.6 -3.5 2.0
13 24 3.0 2.5 -2.0
23 17 4.5 0 0
4 5 3.5 8 12
25 31 5 6.3 4.5
21 57 3 2.0 3.9
40(Time period for which collision needs to be simulated)

2) After creating input file as desired run "EventDrivenSimulator.exe".

3) Visual.exe will be automatically run. If visual is needed it can be run, it will skip the calculations.