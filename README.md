# MDP REPRESENTATION

## AIM:
To represent Markov's Decision Process using a real time problem statement.
## PROBLEM STATEMENT:
### Problem Description
To develop an environment where a person has to reach his destination appropriately.
### State Space
{0,1,2,3,4,5}
### Sample State
3
### Action Space
1.{0} --> MOVING DOWN
2.{1} --> MOVING LEFT
3.{2} --> MOVING UP
4.{3} --> MOVING RIGHT
### Sample Action
MOVING UP
### Reward Function
To reach goal { +1(Reward) 
                Otherwise ->0


### Graphical Representation

![WhatsApp Image 2023-09-12 at 12 47 28 PM](https://github.com/Archana2003-Jkumar/mdp-representation/assets/93427594/761c50f9-7ac9-4228-b520-b9ddbf5b6b80)

## PYTHON REPRESENTATION:
```PYTHON
P = {
    0 : {
        0 : [(0.23, 0, 0.0, False)],
        1 : [(0.52, 1, 0.0, False)],
        2 : [(0.78, 3, 0.0, False)],
        3 : [(0.12, 0, 0.0, False)]
    },
    1 : {
        0 : [(0.16, 1, 0.0, False)],
        1 : [(0.35, 2, 0.0, False)],
        2 : [(0.58, 4, 0.0, False)],
        3 : [(0.29, 0, 0.0, False)]
    },
    2 : {
        0 : [(0.23, 2, 0.0, False)],
        1 : [(0.34, 2, 0.0, False)],
        2 : [(0.78, 5, 0.0, False)],
        3 : [(0.50, 0, 0.0, False)]
    },
    3 : {
        0 : [(0.23, 0, 0.0, False)],
        1 : [(0.45, 1, 0.0, False)],
        2 : [(0.76, 4, 0.0, False)],
        3 : [(0.12, 3, 0.0, False)]
    },
    4 : {
        0 : [(0.23, 0, 0.0, False)],
        1 : [(0.45, 2, 0.0, False)],
        2 : [(0.76, 4, 0.0, False)],
        3 : [(0.12, 3, 0.0, False)]
    },
   5 : {
        0 : [(0.23, 2, 0.0, False)],
        1 : [(0.63, 5, 0.0, False)],
        2 : [(0.76, 3, 0.0, False)],
        3 : [(0.76, 0, 0.0, False)]
    }
}
```
## OUTPUT:
![image](https://github.com/Archana2003-Jkumar/mdp-representation/assets/93427594/f6e8a434-0972-4b6d-8aa1-a86c7bdf637a)

## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:

Graphical Representation
Python Representation
