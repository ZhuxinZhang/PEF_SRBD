This paper presents a neural internal model-based reinforcement learning (RL) control method for 
underactuated unmanned surface vessels (USVs) to improve tracking accuracy and robustness in 
complex environments. Key challenges include model mismatches and external disturbances. 
Traditional model-based methods depend on precise hydrodynamic modeling and struggle 
with uncertainties; pure model-free RL suffers from low data efficiency. Inspired by internal 
model control, we integrate simplified rigid-body dynamics predictive error feedback into RL: 
the state error vector between actual and predicted states is fed to the policy network. 
Simulations use ±20% parameter perturbations to mimic model uncertainties. Comparisons with 
PID, MPC, and vanilla SAC validate that our method better compensates for model mismatch 
and disturbances, enabling high-precision USV path-following.
