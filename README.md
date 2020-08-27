# DavidREU2020
## David's REU 2020 Project Code 

### Descriptions of Code Files

* __1 queue 1 server simulation__
  * Simulates based on a customizable average arrival rate
  * Outputs a normalized histogram of steady-state queue sizes
  * Can perform exponential curve fitting
* __2 × 2 switch__
  * Simulates based on a customizable threshold and four customizable average arrival rates
  * Outputs an (non-steady-state) average total queue length
  * Contains the random and MaxWeight policies
* __3 queues 1 server simulation__
  * Simulates based on three customizable average arrival rates
  * Outputs steady-state average queue lengths and normalized histograms of them
  * Contains the random, serve-the-shortest-queue, and serve-the-longest-queue policies
  * Contains the state-space-collapse phenomenon
* __3 × 3 switch__
  * Simulates based on nine customizable average arrival rates
  * Outputs nine (non-steady-state) average queue lengths
  * Contains the random and MaxWeight policies
* __3-queue system in a 2 × 2 switch__
  * Simulates based on three customizable average arrival rates
  * Outputs steady-state average queue lengths
  * Contains the MaxWeight, MaxSizeCenter, and random policies
  * Contains the state-space-collapse phenomenon
* __TD control for 3-queue system in a 2 × 2 switch__
  * Simulates based on a customizable threshold and three customizable average arrival rates
  * Outputs steady-state average total queue lengths and simulation-parameter plots
  * Contains the random, MaxWeight, MaxSizeCenter, greedy, epsilon-greedy, epsion-MaxWeight, and epsilon-MaxSizeCenter policies
  * Contains the differential q-learning, relative-value-iteration q-learning, discounted-cost q-learning, average-cost q-learning, and average-cost Sarsa methods
* __comparison of performances for 3-queue system in a 2 × 2 switch__
  * Simulates based on a customizable threshold, three customizable average arrival rates, and customizable simulation parameters
  * Outputs steady-state average total queue lengths and comparison-of-performances bar graphs
  * Contains outputs for thresholds 1, 2, 3, 4, and 8
* __state-value estimation for 3-queue system in a 2 × 2 switch__
  * Simulates based on a customizable threshold and three customizable average arrival rates
  * Outputs state-value estimates
  * Contains the MaxWeight and MaxSizeCenter polices
