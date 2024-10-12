# Bayesian A/B Testing for Swedish Fish Incorporated

These code files are my practice work, created while following exercises by [Rasmus Baath](https://github.com/rasmusab). I am still working on it.

## Method A:
- **Experiment:** 6 out of 16 Danes signed up for a one-year subscription to salmon after receiving a colorful brochure from Swedish Fish Inc.
- **Goal:** Marketing wants to assess the effectiveness of Method A.
- **Financials:** Each subscription earns $1,000 and costs $30.

## Method B:
- **Experiment:** 10 out of 16 Danes signed up for a one-year subscription to salmon after receiving a colorful brochure _along with a free salmon_ from Swedish Fish Inc.
- **Goal:** Marketing wants to assess the effectiveness of Method B.
- **Financials:** Each subscription earns $1,000 but costs $300.

---

# Bayesian Data Analysis

## Approximate Bayesian Computation
- This method requires calculating the likelihood that the generative model produces any given data.
- It explores the parameter space in a smarter way—rather than sampling randomly from the prior, it focuses on regions of the parameter space with higher probabilities.
- The resulting samples are similar to those generated via Approximate Bayesian Computation.

## Faster Bayesian Computation
### Markov Chain Monte Carlo (MCMC)
- A class of algorithms that sample from a probability distribution by walking around the parameter space.
  - **Metropolis-Hastings**
  - **Gibbs Sampling**
  - **Hit-and-Run**, **T-Walk**, **Particle Monte Carlo**, etc.

### Hamiltonian Monte Carlo
- An efficient MCMC algorithm that scales well, but can be difficult to set up unless using specialized tools.

## Stan
- Stan allows us to define a model and takes care of fitting it efficiently by compiling it into C++ and using Hamiltonian Monte Carlo for the fitting process.
- It is designed specifically for defining generative models.
