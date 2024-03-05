# Name : Kamesh D
# REG NO : 212222240043

# MDP REPRESENTATION

## AIM:
To represent any one real-world problem in MDP form.
## PROBLEM STATEMENT:
To develop a game application the role of the agent is to promote if the level is cleared or depromote if the game is loss 

### State Space:
```
{A1,A2,A3}--> {0,1,2}
A1--> LEVEL 1
A2--> LEVEL 2 
A3--> LEVEL 3
```
### Sample State
A1--> 0 --> LEVEL 1

### Action Space:
```
{W,L}-->{0,1}
W-->True
L-->False
```
### Sample Action
W--> 0 --> True

### Reward Function:
```
R = { +1 , if we come closer to the winning
       0 , if not
```
### Graphical Representation
![WhatsApp Image 2024-03-05 at 14 46 24_99d5510e](https://github.com/KameshLeVI/mdp-representation/assets/120780633/5c4a275b-08fc-40db-8a2f-910af6157499)


## PYTHON REPRESENTATION:
```
P = {
    0:{
        0: [(0,1,1,True)],
        1: [(1.0,0,1.0,False)]
    },
    1:{
        0: [(0,2,1,True)],
        1: [(1,0,1,False)]
    },
    2:{
        0: [(0,2,1,True)],
        1: [(1,1,1,False)]
    }
}
P
```
## OUTPUT:
![image](https://github.com/KameshLeVI/mdp-representation/assets/120780633/dcffe530-8eeb-4c06-b79f-4a4dfdf3cb4e)


## RESULT:
Thus the given real world problem is successfully represented in a MDP form .

