# Multiagent Reinforcement Learning for Traffic Light Simulation

- Follow the Flow documentation to setup Flow, SUMO and RLlib in the system. More tutorials and examples are available in the main repository of Flow.
- Activate virtual environment for flow and run train.py and simulate.py scripts in /Training as "python simulate.py EXP_CONFIG" or "python train.py EXP_CONFIG"
- Pre-trained models are present in /ray_results. Use "tensorboard --logdir ~/ray_results" to view the training statistics.

# Flow

[Flow](https://flow-project.github.io/) is a computational framework for deep RL and control experiments for traffic microsimulation.

See [our website](https://flow-project.github.io/) for more information on the application of Flow to several mixed-autonomy traffic scenarios. Other [results and videos](https://sites.google.com/view/ieee-tro-flow/home) are available as well.

# More information

- [Documentation](https://flow.readthedocs.org/en/latest/)
- [Installation instructions](http://flow.readthedocs.io/en/latest/flow_setup.html)
- [Tutorials](https://github.com/flow-project/flow/tree/master/tutorials)
- [Binder Build (beta)](https://mybinder.org/v2/gh/flow-project/flow/binder)

# Technical questions

If you have a bug, please report it. Otherwise, join the [Flow Users group](https://join.slack.com/t/flow-users/shared_invite/enQtODQ0NDYxMTQyNDY2LTY1ZDVjZTljM2U0ODIxNTY5NTQ2MmUxMzYzNzc5NzU4ZTlmNGI2ZjFmNGU4YjVhNzE3NjcwZTBjNzIxYTg5ZmY) on Slack!  

# Getting involved

We welcome your contributions.

- Please report bugs and improvements by submitting [GitHub issue](https://github.com/flow-project/flow/issues).
- Submit your contributions using [pull requests](https://github.com/flow-project/flow/pulls). Please use [this template](https://github.com/flow-project/flow/blob/master/.github/PULL_REQUEST_TEMPLATE.md) for your pull requests.

# Citing Flow

If you use Flow for academic research, you are highly encouraged to cite our paper:

C. Wu, A. Kreidieh, K. Parvate, E. Vinitsky, A. Bayen, "Flow: Architecture and Benchmarking for Reinforcement Learning in Traffic Control," CoRR, vol. abs/1710.05465, 2017. [Online]. Available: https://arxiv.org/abs/1710.05465

If you use the benchmarks, you are highly encouraged to cite our paper:

Vinitsky, E., Kreidieh, A., Le Flem, L., Kheterpal, N., Jang, K., Wu, F., ... & Bayen, A. M,  Benchmarks for reinforcement learning in mixed-autonomy traffic. In Conference on Robot Learning (pp. 399-409). Available: http://proceedings.mlr.press/v87/vinitsky18a.html

# Contributors

Flow is supported by the [Mobile Sensing Lab](http://bayen.eecs.berkeley.edu/) at UC Berkeley and Amazon AWS Machine Learning research grants. The contributors are listed in [Flow Team Page](https://flow-project.github.io/team.html).
