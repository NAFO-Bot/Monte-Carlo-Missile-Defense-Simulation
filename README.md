# Monte-Carlo-Missile-Defense-Simulation
Raid Size = 250 missile
All missiles are identical; all of them are detected and tracked. No sensor bottlenecks modelled.
The following are treated as the same 
SRBMs
MRBMs
IRBMs
Cruise missiles
Hypersonic weapons
Decoys
The defensive architecture consists of three sequential layers:
Aegis - This one goes first 
THAAD - This is the second layer
Patriot - This is the final layer
It is assumed that if a layer has inventory left, it can engage the target.
Aegis → THAAD → Patriot interceptors are fired in that order. No launches for already intercepted missiles - perfect missile allocation.
AEGIS and THAAD get 2 shots on target, PATRIOT gets 1
Single-shot Pk = 0.92 - PATRIOT
Pk Aegis = 0.96 (2 interceptors per bogey)
Pk THAAD = 0.98 (2 interceptors per bogey)
100 simulations ran.
