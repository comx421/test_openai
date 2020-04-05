# Results of GAIL/BC on Mujoco

Here's the extensive experimental results of applying GAIL/BC on Mujoco environments, including Hopper-v1, Walker2d-v1, HalfCheetah-v1, Humanoid-v1, HumanoidStandup-v1. Every imitator is evaluated with seed to be 0.

## Results

### Training through iterations

* Hoppers-v1 ![](../../../.gitbook/assets/hopper-training.png)
* HalfCheetah-v1 ![](../../../.gitbook/assets/halfcheetah-training.png)
* Walker2d-v1 ![](../../../.gitbook/assets/walker2d-training.png)
* Humanoid-v1 ![](../../../.gitbook/assets/humanoid-training.png)
* HumanoidStandup-v1 ![](../../../.gitbook/assets/humanoidstandup-training.png)

For details \(e.g., adversarial loss, discriminator accuracy, etc.\) about GAIL training, please see [here](https://drive.google.com/drive/folders/1nnU8dqAV9i37-_5_vWIspyFUJFQLCsDD?usp=sharing)

### Determinstic Policy \(Set std=0\)

|  | Un-normalized | Normalized |
| :--- | :--- | :--- |
| Hopper-v1 | ![](../../../.gitbook/assets/hopper-unnormalized-deterministic-scores.png) | ![](../../../.gitbook/assets/hopper-normalized-deterministic-scores.png) |
| HalfCheetah-v1 | ![](../../../.gitbook/assets/halfcheetah-unnormalized-deterministic-scores.png) | ![](../../../.gitbook/assets/halfcheetah-normalized-deterministic-scores.png) |
| Walker2d-v1 | ![](../../../.gitbook/assets/walker2d-unnormalized-deterministic-scores.png) | ![](../../../.gitbook/assets/walker2d-normalized-deterministic-scores.png) |
| Humanoid-v1 | ![](../../../.gitbook/assets/humanoid-unnormalized-deterministic-scores.png) | ![](../../../.gitbook/assets/humanoid-normalized-deterministic-scores.png) |
| HumanoidStandup-v1 | ![](../../../.gitbook/assets/humanoidstandup-unnormalized-deterministic-scores.png) | ![](../../../.gitbook/assets/humanoidstandup-normalized-deterministic-scores.png) |

### Stochatic Policy

|  | Un-normalized | Normalized |
| :--- | :--- | :--- |
| Hopper-v1 | ![](../../../.gitbook/assets/hopper-unnormalized-stochastic-scores.png) | ![](../../../.gitbook/assets/hopper-normalized-stochastic-scores.png) |
| HalfCheetah-v1 | ![](../../../.gitbook/assets/halfcheetah-unnormalized-stochastic-scores.png) | ![](../../../.gitbook/assets/halfcheetah-normalized-stochastic-scores.png) |
| Walker2d-v1 | ![](../../../.gitbook/assets/walker2d-unnormalized-stochastic-scores.png) | ![](../../../.gitbook/assets/walker2d-normalized-stochastic-scores.png) |
| Humanoid-v1 | ![](../../../.gitbook/assets/humanoid-unnormalized-stochastic-scores.png) | ![](../../../.gitbook/assets/humanoid-normalized-stochastic-scores.png) |
| HumanoidStandup-v1 | ![](../../../.gitbook/assets/humanoidstandup-unnormalized-stochastic-scores.png) | ![](../../../.gitbook/assets/humanoidstandup-normalized-stochastic-scores.png) |

### details about GAIL imitator

For all environments, the imitator is trained with 1, 5, 10, 50 trajectories, where each trajectory contains at most 1024 transitions, and seed 0, 1, 2, 3, respectively.

### details about the BC imitators

All BC imitators are trained with seed 0.

