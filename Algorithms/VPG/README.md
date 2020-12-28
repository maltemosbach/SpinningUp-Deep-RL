# Vanilla Policy Gradient (VPG)

## Background
### Notations
Symbol | Description
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

### Derivation
Policy gradient methods operate by optimizing the policy directly such that the return <img align="center" src="../../docs/images/VPG/J.svg" alt="J"/> is maximized. Using *gradient ascent*, the parameters <img align="center" src="../../docs/images/VPG/theta.svg" alt="theta"/> can be moved into the direction suggested by <img align="center" src="../../docs/images/VPG/Nable-of-J.svg" alt="\nabla_\theta J(\theta)"/> to obtain a policy <img align="center" src="../../docs/images/VPG/pi_theta.svg" alt="\pi_{\theta}"/> that maximizes the return.

In *vanilla policy gradient (VPG)* we train a **stochastic** policy <img align="center" src="../../docs/images/VPG/pi_theta.svg" alt="\pi_{\theta}"/> in an **on policy** way to maximize the performance <img align="center" src="../../docs/images/VPG/J-of-pi_theta.svg" alt="J(\pi_{\theta})"/>.






## Pseudocode
![VPG pseudocode algorithm](../../docs/images/VPG/VPG_Pseudocode.svg)
