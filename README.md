# Text-Classification-Using-Gibbs-Sampler
Course project for 'Simulation of Stochastic and Random Process'

## This project classifies text samples as either spam or ham (non-spam). It leverages labeled data to achieve high accuracy, which eventually saturates once the balance condition of the Markov Chain is reached. The implementation is developed and coded based on a [research paper](https://github.com/Kruthikesh/Text-Classification-Using-Gibbs-Sampler/files/15346709/text_clas.pdf), with optimizations including vectorization of loops, resulting in a sevenfold decrease in execution time.

### MCMC is a sampling method used to obtain probability distribution functions (pdfs) based on given information. The core idea is to simulate draws from pdfs to allow the Markov Chain to grow, ensuring that the next sampling point depends on the current sampling point.

## Key Concepts: Stationary Distribution: If the sampling probability remains the same after many iterations, the distribution reaches a stationary state. Detailed Balance Condition: Ensures that the Markov Chain has a stationary distribution that converges to the target distribution 𝑝(𝑥).

## Gibbs Sampling: Samples from the conditional distribution 𝑝(𝜃1∣𝜃2,𝜃3,…)p(θ1∣θ2,θ3,…) and accepts each state with probability one. This method simplifies the computation by focusing on conditional distributions.

## This project successfully classifies text samples as spam or ham using MCMC methods and optimizes performance through vectorization. The implementation demonstrates significant improvements in accuracy and efficiency, showcasing the power of advanced sampling methods in text classification tasks.
