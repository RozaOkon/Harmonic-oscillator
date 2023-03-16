# Harmonic-oscillator
Simulation of harmonic oscillator trajectory and energy using Euler, Verlet and leap frog algorithms

'init_cond_and_algorithms' script contains a definition of default initial conditions and algorithms and is being imported to the remaining programs.
'phase space' plots the dependence of position (x) and momentum (p) on time (t), as well as the phase space (p(x)) of harmonic oscillator using one from defined algorithms (Verlet, Euler, leap frog).
'stability' plots total energy of oscillator over the time and phase space with changing time steps (and the number of steps - so the simulation time was constant)

Both 'phase space' and 'stability' can be run with optional markers:
-m: mass of oscillator (default: 1)
-k: oscillator constant (default: 1)
-x0: inital position (default: 1)
-p0: initial momentum (default: 0)
-n_steps: number of simulation steps (default: 1000)
-delta_t: simulation time step (default: 0.05)
-method: algorithm employed to run the simulation (default: Euler algorithm; possible options: euler, verlet, leapfrog (only for phase-space))
