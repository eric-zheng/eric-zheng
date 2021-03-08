# Hi there 👋

## Highlighted Projects

### Horizontally Fused Training Array

Our study reveals that single-accelerator training jobs can dominate the cluster-wide resource consumption when launched repetitively (e.g., for hyper-parameter tuning) while severely underutilizing the hardware.
This is because DL researchers and practitioners often lack the required expertise to independently optimize their own workloads.
We propose Horizontally Fused Training Array (HFTA), a new DL framework extension library that horizontally fuses the models from repetitive jobs deeply down to operators, and then trains those models simultaneously on a shared accelerator.
On three emerging DL training workloads and state-of-the-art accelerators (GPUs and TPUs), HFTA demonstrates strong effectiveness in squeezing out hardware utilization and achieves up to 15.1x higher training throughput vs. the standard practice of running each job on a separate accelerator.

Link to the publication: https://arxiv.org/abs/2102.02344

<!--
**eric-zheng/eric-zheng** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
