# A title

Body text

## Title #2

More body text

### title #3

#### title #4

## Sample KaTeX

$$
J(\theta)
= \sum_{s \in \mathcal{S}} d^\pi(s) V^\pi(s) 
= \sum_{s \in \mathcal{S}} d^\pi(s) \sum_{a \in \mathcal{A}} \pi_\theta(a \vert s) Q^\pi(s, a)
$$

where $d^\pi(s)$ is the stationary distribution of Markov chain for $\pi_\theta$ (on-policy state distribution under $\pi$). For simplicity, the parameter $\theta$ would be omitted for the policy $\pi_\theta$ when the policy is present in the subscript of other functions; for example, $d^{\pi}$ and $Q^\pi$ should be $d^{\pi_\theta}$ and $Q^{\pi_\theta}$ if written in full.
