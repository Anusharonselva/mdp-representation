# MDP REPRESENTATION

## AIM:
To represent an Elevator Control System using a Markov Decision Process (MDP)
## PROBLEM STATEMENT:
To create a Markov Decision Process (MDP) for an elevator system that moves between floors and serves passengers efficiently.
### Problem Description
To create an elevator system for a building with 4 floors.
The elevator can move, open/close doors, or stay idle.
Using MDP, we want to help the elevator serve passengers quickly and efficiently.### State Space
Write your answer here

### State space 
I   ->>  Floor 1 (Ground Floor)
II  ->>  Floor 2
III ->>  Floor 3
IV  ->>  Floor 4 (Top Floor)
### Sample State
![Screenshot 2025-03-12 144234](https://github.com/user-attachments/assets/5e8b46a5-2906-4351-9a11-a1e8f238d9d4)


### Action Space
The elevator can move up or down one floor at a time, pick up the passenger if it's at the waiting floor, or drop the passenger off if it's at the destination floor.
### Sample Action

### Reward Function
10 points for picking up a passenger.
20 points for dropping off a passenger at the correct floor.
Negative Reward:
-5 points for unnecessary movement (e.g., moving when not needed).
-1 point for invalid actions.

## PYTHON REPRESENTATION:
Elevator Position: 2, Passenger Waiting: 5, Destination: 4, Passenger In Elevator: False, Reward: -1
Elevator Position: 2, Passenger Waiting: 5, Destination: 4, Passenger In Elevator: False, Reward: -1
Elevator Position: 3, Passenger Waiting: 5, Destination: 4, Passenger In Elevator: False, Reward: -1
Elevator Position: 4, Passenger Waiting: 5, Destination: 4, Passenger In Elevator: False, Reward: -1
Elevator Position: 5, Passenger Waiting: 5, Destination: 4, Passenger In Elevator: False, Reward: 10
Elevator Position: 5, Passenger Waiting: 5, Destination: 4, Passenger In Elevator: True, Reward: -1
Elevator Position: 4, Passenger Waiting: 5, Destination: 4, Passenger In Elevator: True, Reward: -1
Elevator Position: 3, Passenger Waiting: 5, Destination: 4, Passenger In Elevator: True, Reward: -1
Elevator Position: 2, Passenger Waiting: 5, Destination: 4, Passenger In Elevator: True, Reward: 20
Passenger successfully delivered!

## OUTPUT:
Write your Python output here
![Screenshot 2025-03-14 143139](https://github.com/user-attachments/assets/875afdc7-726f-4444-92da-4fb96e26d759)

## RESULT:
Thus the given real world problem is successfully represented in a MDP form .


