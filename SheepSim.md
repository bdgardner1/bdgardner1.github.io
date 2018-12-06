## Python Coursework - Sheep Simulator
![A typical scene on one of my hiking trips](sheep_resize.jpg)

As part of my Data Analytics Master's course I created a 'Sheep Simulator' using Python.

[Sheep Simulator Code in GitHub](https://github.com/bdgardner1/Python-Coursework)

**NOTE:** The final model is  **_model_Additional.py_**

In my simulator 10 agents (white sheep) roam around an enviornment (field) consuming and storing data (grass) as go.

When the agents encounter each other in the field they add together the grass they've gained and share it out equally among themselves (these are thoughtful sheep!).  

There are also three sheepdog (black dots), who move around and 'scare' the sheep back to the centre of the field if they come within a certain distance of them. The sheep are so scared that they move instantaneously!!

### Here is a brief overview of the code flow:
1. The evironment is loaded into the programme via a .txt file. 
2. 10 sheep are created and located randomly within the field.
3. Three sheepdog are created in the centre of the field (with 500 energy). 
4. Each sheep agent moves twice and consumes some of the environment and checks to see if there is a nearby sheep agent to share with. 
5. Each sheepdog agent moves twice, depleting its energy. 
6. A check is done to see if the sheepdog agent is now within a certain distance of any sheep agents. If so the sheep moves to the centre of the field and the sheepdog receives additional energy.  
7. The position of each sheep agent is loaded into matplot along with the new environment. 
8. The position of each sheepdog agent is loaded into matplot.
9. Steps 4-8 is repeated 1,000 times. 
10. The matplot data is animated, showing the movement of the two agent types and depletition of the environment. 
11. The final environment state is saved to a file. 


