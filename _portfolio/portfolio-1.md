---
title: "Distributed Secondary Control of Inverter-based Microgrid"
excerpt: "A DNMPC method for restoring voltage in an autonomous microgrid<br/><img src='/images/simulink_plant.jpg'>"
collection: portfolio
---
For my undergraduate capstone, I chose to work on an independent project supervised by Patricia-Hidalgo Gonzalez
(PhD Candidate EECS/Energy and Resources Group University of California Berkeley). The result was this project on
secondary control of voltage in a microgrid setting. Here I include some of the basics of it.

__Abstract__:
In this paper, a voltage restoration scheme for droop-controlled inverter-based islanded microgrids is proposed.
A distributed model predictive control (DMPC) method is designed to be run at each inverter, which only communicates
with its immediate neighbors. The DMPC aims to solve a reference tracking problem in order to restore the voltages of
all the nodes in the system to the voltage reference. The dynamics for this work are taken to be decoupled from the real
power-frequency dynamics in order to focus the work on restoring the location-varying nature of voltage. The scheme is
demonstrated to be stable on a Simulink simulator designed for this work.

<br/><img src='/images/plecs_model.jpg'>

