# Baysian A, B testing for Swedish Fish Incorporated
## Method A:
### 6/16 Danes signed up for one year of salmon when recieved colorful brochure from Swedish Fish Inc. and marketing now wants to know, how good is method A?
### Each subscription earn 1000 and cost 30

## Method B: 
### 10/16 Danes signed up for one year of salmon when recieved colorful brochure _along with a free solmon_ from Swedish Fish Inc. and marketing now wants to know, how good is method A?
### Each subscription earn 1000 and cost 300"# Bayesian_Data_Analysis" 

# Approximate Bayesian Computation

# Faster Bayesian Computation
### They require that the liklihood that the generative model will generate any given data be calculated
### The explore the parameter space in  a smarter way - rather than just sampling from the prior, the explore the parameter space region that has higher probability
### Samples will be the same as apprximate Bayesian computation
## Markov Chain Monte Carlo
### A class of algorithms that sample from the probability distribution by walking around th eparameter space.
#### Metropolis - Hastings 
#### Gibbs sampling
#### hit-n-Run, the T-walk, particle monte carlo etc
## Hamiltonian Monte Carlo
#### is an efficient MCMC algorithm that scales but that is difficult to set up ubless we use
## Stan
### define model and Stan takes care of fitting it effieciently by compiling it down to C++ and fit it using Hamiltonian Monte Carlo
### tailor made for defining generative models

