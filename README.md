# MSBD 5008 Cascade Model Simulation

## Summary of Cascade Model Simulation Algorithm:
- All the Nodes in the network was set to 'B' before the Cascade simulation
- An inital set of Nodes will adopt 'A' before the Cascade simulation
- This algorithm will be using a basic Decision Based Diffusion Model to simulate the nodes making a decision based on its neighbouring nodes
- A node will switch from 'B' to 'A' if the payoff for adopting 'A' is higher

## Remarks
- A plot of the Graph Network before the Cascade and after the Cascade simulation will be generated for visual comparison
- At the end of the code, an interactive Graph Network will be generated using Plotly
- Further details of the analysis is found in the report

## Description on Basic Analysis and Summary of Network.ipynb
- Contains the code for Basic Analysis and Summary of the Network  
- First section Plots the Graph Network for the Complete Facebook Network
- Second section Plots the Basic Analysis and Summary for 2 Ego Networks that was referenced in the report. 

## Description on Ego_Network_Cascade_107.ipynb and Ego_Network_Cascade_686.ipynb
- Simulate the Cascade Effect on 2 different Ego Networks

## Description on Graph_Network_on_plotly.ipynb
- A jupyter notebook to plot an Ego Network and the Complete Facebook Network using Plotly





