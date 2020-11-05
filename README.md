# AgentAssistance

![](Gridworld8direction.gif) 


Reinforcement learning Q Learning  Grid-World 8 directions.
Change number of grids, position of trap, goal in the gridworld.py

One of the reasons people love playing games is the sense of agency. They have control over their choices and the outcomes are instantaneous, causation obvious. For an average human who makes thousands of choices, causations are poorly understood as the processes can be abstract. Simple everyday nuances can compound over time. Even if people know the cause and effect, do they have the power to change it?

 For a person who is disabled their choices are fundamentally restricted by sensorimotor impairment, causing low sense of agency, in everyday activities. Especially in stroke where they were once independent. Competence, Autonomy or sense of agency/control are fundamental psychological needs. With increase of perceived competence, intrinsic motivation increases, yet competence alone is not enough as the perception that they won the game by their effort is vital, which is the feeling of agency. As feeling of agnecy decreases, intrinsic motivation decreases

The main rational is to give assistance without compromising the sense of agency/control. 
In this simulation a simple gridworld game was agent trained using Q-learning algorithm, the assistance is compromised between the sense of agency/control and competence(score). Sense of agency in this case depends when the assistance is made. If the optimal angle is entirely opposite to subject's angle and yet the assistance is given the sense of agency will be low, competence (score) is high. We would like to increase sense of agency/control and competence at the same time, which are two opposite parameters when assistance comes into play. A tradeoff between the sense of agency and competence is vital for keeping subject engaed in the game. 


Here three different weights simulations results are shown,  
Assist As Needed = Competence 1.0 + Autonomy .75
![Alt text](100c75a.PNG?raw=true "Title")


Assist As Needed = Competence 1.0 + Autonomy 1.0
![Alt text](100c100a.PNG?raw=true "Title")


Assist As Needed = Competence 0.75 + Autonomy 1.0
![Alt text](75c100a.PNG?raw=true "Title")


P.S: The Qtable_gridworld.ipynb is in a raw unrefined stage, will upload a clean code in the near-future. 
Simulated weighted assistance vs game score 
