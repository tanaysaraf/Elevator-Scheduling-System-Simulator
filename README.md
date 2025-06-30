# Elevator-Scheduling-System-Simulator
A multi-elevator control system simulation in C# that models realistic elevator behavior, direction-aware scheduling, ETA-based prioritization, and fair job assignment using tick-based state updates. Includes support for opposite-direction queuing, dwell time, and starvation prevention.

This is a console based application. 

To Issue a command 
1. Going UP 
U <from> <to>
# example of going from 0th floor to 5th floor. 
 U 0 5 
 
2. Going Down 
D <from> <to?

# example of going from 10th floor to 5th floor. 
 D 10 5 


3. P 
This is for debug purpose, this tells the current states of all elebvatos
