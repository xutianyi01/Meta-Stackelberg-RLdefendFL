# Meta Stackelberg Game: Robust Federated Learning against Adaptive and Mixed Poisoning Attacks

This repository contains the code for the paper:

**Meta Stackelberg Game: Robust Federated Learning against Adaptive and Mixed Poisoning Attacks**  
📄 [arXiv:2410.17431](https://arxiv.org/abs/2410.17431)


## Files
- [`Mixed_RLdefendFL4.ipynb`](./Mixed_RLdefendFL4.ipynb) — Main notebook for the Meta-Stackelberg robust FL defense.
- [`GAN_BackdoorFL_cifar10.ipynb`](./GAN_BackdoorFL_cifar10.ipynb) — **GAN-based** backdoor attack baseline on CIFAR-10 (for comparison/ablation).
- [`GAN_BackdoorFL_mnist.ipynb`](./GAN_BackdoorFL_mnist.ipynb) — **GAN-based** backdoor attack baseline on MNIST (for comparison/ablation).
- [`DIFF_BackdoorFL_cifar10.ipynb`](./DIFF_BackdoorFL_cifar10.ipynb) — **Diffusion-based** backdoor attack baseline on CIFAR-10 (for comparison/ablation).
- [`RE_NeuralCleanse_Backdoor.ipynb`](./RE_NeuralCleanse_Backdoor.ipynb) — **Reverse engineering** of backdoor triggers using **Neural Cleanse (ART)**; reconstructs trigger pattern/mask and visualizes sensitivity.




## Related Work

For more **code-level details** (attack implementations and training procedures), please check:

- Henger Li, Xiaolin Sun, Zizhan Zheng. **Learning to Attack Federated Learning: A Model-Based Reinforcement Learning Attack Framework.** *NeurIPS 2022*.  
  Paper: https://proceedings.neurips.cc/paper_files/paper/2022/file/e2ef0cae667dbe9bfdbcaed1bd91807b-Paper-Conference.pdf
  Code: https://github.com/SliencerX/Learning-to-Attack-Federated-Learning  

- Henger Li, Chen Wu, Sencun Zhu, Zizhan Zheng. **Learning to Backdoor Federated Learning.** *ICLR 2023 Workshop on Backdoor Attacks and Defenses in Machine Learning (BANDS).*  
  arXiv: https://arxiv.org/abs/2303.03320
  Code: https://github.com/HengerLi/RLBackdoorFL

- Henger Li, Zizhan Zheng. **Meta-Reinforcement Learning for Moving Target Defense (MTD).**  
  Paper: https://dl.acm.org/doi/10.1007/978-3-031-26369-9_6
  Code: https://github.com/HengerLi/Meta-RL-for-MTD  

## License
Released under the [MIT License](./LICENSE).
