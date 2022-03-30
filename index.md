---
title: Gideon Miller
---

## Agent Based Model

This website contains the links to the Agent-Based-Model produced as part of the GEOG5990 module. The three files necessary to run the model are:  [Final model.py](https://github.com/gideonmiller1998/Geog5990/blob/main/model.py), [Final Agentframework.py](https://github.com/gideonmiller1998/Geog5990/blob/main/agentframework.py) and [In.txt](https://github.com/gideonmiller1998/Geog5990/blob/main/in.txt). All other files in the [Repository](https://github.com/gideonmiller1998/Geog5990) show the progress made at each step to these final files. The agents in the model randomly move around the environment and eat away at the data, sharing  with the other agents in their neighbourhood when certain thresholds are met, and finally depositing back into the environment. In real life  terms this can be thought of as sheep wandering around a field eating  grass and returning it back to the environment as animal waste. The GUI  allows the user to give a number of agents, a number of iterations and a stopping condition. The stopping condition is a number between 0 and 1. At each iteration a random number is created and if the stopping  condition specified in the GUI is lower than the random number the model will end. If this stopping condition is not reached the model will run until the number of iterations is met. The code has been appropriately  licensed. The GIFF below shows an example of the output of the model.

![Example model](docs\Assets\agents_animation.gif)