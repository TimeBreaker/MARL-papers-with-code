# MARL Papers with Code
This is a collection of Multi-Agent Reinforcement Learning (MARL) papers with code. I have selected some relatively important papers with open source code and categorized them by time and method.

For MARL papers and MARL resources, please refer to [Multi Agent Reinforcement Learning papers](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers) and [MARL Resources Collection](https://github.com/TimeBreaker/MARL-resources-collection).

I will continually update this repository and I welcome suggestions. (missing important papers, missing categories, invalid links, etc.) This is only a first draft so far and I'll add more resources in the next few months.

This repository is not for commercial purposes.

My email: chenhao915@mails.ucas.ac.cn


## Overview
* [Classic Papers](https://github.com/TimeBreaker/MARL-papers-with-code#classic-papers)
* [Other Papers](https://github.com/TimeBreaker/MARL-papers-with-code#other-papers)
* [TODO](https://github.com/TimeBreaker/MARL-papers-with-code#todo)


## Classic Papers
### Algorithms
Category|Paper|Code|Accepted at|Year
--|:--:|:--:|:--:|--:
Independent Learning|[IQL：Multi-Agent Reinforcement Learning: Independent vs. Cooperative Agents](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.84.3701&rep=rep1&type=pdf)|https://github.com/oxwhirl/pymarl|ICML|1993
Value Decomposition|[VDN：Value-Decomposition Networks For Cooperative Multi-Agent Learning](https://arxiv.org/pdf/1706.05296)|https://github.com/oxwhirl/pymarl|AAMAS|2017
Value Decomposition|[QMIX: Monotonic Value Function Factorisation for Deep Multi-Agent Reinforcement Learning](http://proceedings.mlr.press/v80/rashid18a/rashid18a.pdf)|https://github.com/oxwhirl/pymarl|ICML|2018
Value Decomposition|[QTRAN: Learning to Factorize with Transformation for Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/1905.05408)|https://github.com/oxwhirl/pymarl|ICML|2019
Policy Gradient|[COMA：Counterfactual Multi-Agent Policy Gradients](https://arxiv.org/abs/1705.08926)|https://github.com/oxwhirl/pymarl|AAAI|2018
Policy Gradient|[MADDPG：Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments](https://arxiv.org/pdf/1706.02275.pdf&quot;&gt;Multi-Agent)|https://github.com/openai/maddpg|NIPS|2017
Communication|[BiCNet：Multiagent Bidirectionally-Coordinated Nets: Emergence of Human-level Coordination in Learning to Play StarCraft Combat Games](https://arxiv.org/abs/1703.10069)|https://github.com/Coac/CommNet-BiCnet||2017
Communication|[CommNet：Learning Multiagent Communication with Backpropagation](https://arxiv.org/abs/1605.07736)|https://github.com/facebookarchive/CommNet|NIPS|2016
Communication|[IC3Net：Learning when to Communicate at Scale in Multiagent Cooperative and Competitive Tasks](https://arxiv.org/abs/1812.09755)|https://github.com/IC3Net/IC3Net||2018
Communication|[RIAL/RIDL：Learning to Communicate with Deep Multi-Agent Reinforcement Learning](https://arxiv.org/abs/1605.06676)|https://github.com/iassael/learning-to-communicate|NIPS|2016
Exploration|[MAVEN：Multi-Agent Variational Exploration](https://arxiv.org/pdf/1910.07483)|https://github.com/starry-sky6688/MARL-Algorithms|NIPS|2019

### Environments
Environment|Paper|Code|Accepted at|Year
--|:--:|:--:|:--:|--:
StarCraft|[The StarCraft Multi-Agent Challenge](https://arxiv.org/pdf/1902.04043)|https://github.com/oxwhirl/smac|NIPS|2019
StarCraft|[SMACv2: A New Benchmark for Cooperative Multi-Agent Reinforcement Learning](https://openreview.net/pdf?id=pcBnes02t3u)|https://github.com/oxwhirl/smacv2||2022
StarCraft|[Benchmarking Multi-Agent Deep Reinforcement Learning Algorithms in Cooperative Tasks](https://arxiv.org/pdf/2006.07869)|https://github.com/uoe-agents/epymarl|NIPS|2021
Football|[Google Research Football: A Novel Reinforcement Learning Environment](https://ojs.aaai.org/index.php/AAAI/article/view/5878/5734)|https://github.com/google-research/football|AAAI|2020
PettingZoo|[PettingZoo: Gym for Multi-Agent Reinforcement Learning](https://proceedings.neurips.cc/paper/2021/file/7ed2d3454c5eea71148b11d0c25104ff-Paper.pdf)|https://github.com/Farama-Foundation/PettingZoo|NIPS|2021
Melting Pot|[Scalable Evaluation of Multi-Agent Reinforcement Learning with Melting Pot](http://proceedings.mlr.press/v139/leibo21a/leibo21a.pdf)|https://github.com/deepmind/meltingpot|ICML|2021
MuJoCo|[MuJoCo: A physics engine for model-based control](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.296.6848&rep=rep1&type=pdf)|https://github.com/deepmind/mujoco|IROS|2012
MALib|[MALib: A Parallel Framework for Population-based Multi-agent Reinforcement Learning](https://arxiv.org/pdf/2106.07551)|https://github.com/sjtu-marl/malib||2021
MAgent|[MAgent: A many-agent reinforcement learning platform for artificial collective intelligence](https://ojs.aaai.org/index.php/AAAI/article/download/11371/11230)|https://github.com/Farama-Foundation/MAgent|AAAI|2018
Neural MMO|[Neural MMO: A Massively Multiagent Game Environment for Training and Evaluating Intelligent Agents](https://arxiv.org/pdf/1903.00784)|https://github.com/openai/neural-mmo||2019
MPE|[Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments](https://proceedings.neurips.cc/paper/2017/file/68a9750337a418a86fe06c1991a1d64c-Paper.pdf)|https://github.com/openai/multiagent-particle-envs|NIPS|2017
Pommerman|[Pommerman: A multi-agent playground](https://arxiv.org/pdf/1809.07124.pdfâ€%E2%80%B9arxiv.org)|https://github.com/MultiAgentLearning/playground||2018
HFO|[Half Field Offense: An Environment for Multiagent Learning and Ad Hoc Teamwork](https://www.cse.iitb.ac.in/~shivaram/papers/hmsks_ala_2016.pdf)|https://github.com/LARG/HFO|AAMAS Workshop|2016


## Other Papers
Category|Paper|Code|Accepted at|Year
--|:--:|:--:|:--:|--:
Graph Neural Network|[Multi-Agent Game Abstraction via Graph Attention Neural Network](https://ojs.aaai.org/index.php/AAAI/article/view/6211/6067)|https://github.com/starry-sky6688/MARL-Algorithms|AAAI|2020
Curriculum Learning|[From Few to More: Large-Scale Dynamic Multiagent Curriculum Learning](https://arxiv.org/abs/1909.02790)|https://github.com/starry-sky6688/MARL-Algorithms|AAAI|2020
Curriculum Learning|[EPC：Evolutionary Population Curriculum for Scaling Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/2003.10423)|https://github.com/qian18long/epciclr2020|ICLR|2020
Curriculum Learning/Emergent|[Emergent Tool Use From Multi-Agent Autocurricula](https://arxiv.org/pdf/1909.07528)|https://github.com/openai/multi-agent-emergence-environments|ICLR|2020
Curriculum Learning|[Cooperative Multi-agent Control using deep reinforcement learning](http://ala2017.it.nuigalway.ie/papers/ALA2017_Gupta.pdf)|https://github.com/sisl/MADRL|AAMAS|2017
Role|[ROMA: Multi-Agent Reinforcement Learning with Emergent Roles](https://openreview.net/pdf?id=RQP2wq-dbkz)|https://github.com/TonghanWang/ROMA|ICML|2020
Role|[RODE: Learning Roles to Decompose Multi-Agent Tasks](https://arxiv.org/pdf/2010.01523)|https://github.com/TonghanWang/RODE|ICLR|2021
Role|[Scaling Multi-Agent Reinforcement Learning with Selective Parameter Sharing](http://proceedings.mlr.press/v139/christianos21a/christianos21a.pdf)|https://github.com/uoe-agents/seps|ICML|2021
Opponent Modeling|[Opponent Modeling in Deep Reinforcement Learning](https://arxiv.org/abs/1609.05559)|https://github.com/hhexiy/opponent|ICML|2016
Selfish Agent|[M3RL: Mind-aware Multi-agent Management Reinforcement Learning](https://arxiv.org/pdf/1810.00147)|https://github.com/facebookresearch/M3RL|ICLR|2019
Communication|[Emergence of grounded compositional language in multi-agent populations](https://ojs.aaai.org/index.php/AAAI/article/download/11492/11351)|https://github.com/bkgoksel/emergent-language|AAAI|2018
Communication|[Fully decentralized multi-agent reinforcement learning with networked agents](http://proceedings.mlr.press/v80/zhang18n/zhang18n.pdf)|https://github.com/cts198859/deeprl_network|ICML|2018
Policy Gradient|[DOP: Off-Policy Multi-Agent Decomposed Policy Gradients](https://arxiv.org/abs/2007.12322)|https://github.com/TonghanWang/DOP|ICLR|2021
Policy Gradient|[MAAC：Actor-Attention-Critic for Multi-Agent Reinforcement Learning](https://arxiv.org/abs/1810.02912)|https://github.com/shariqiqbal2810/MAAC|ICML|2019
Environment|[Emergent Complexity via Multi-Agent Competition](https://arxiv.org/pdf/1710.03748.pdf%3Cp%3EKEYWORDS:&nbsp;Artificial)|https://github.com/openai/multiagent-competition|ICLR|2018
Exploration|[EITI/EDTI：Influence-Based Multi-Agent Exploration](https://arxiv.org/pdf/1910.05512)|https://github.com/TonghanWang/EITI-EDTI|ICLR|2020
Exploration|[LIIR: Learning Individual Intrinsic Reward in Multi-Agent Reinforcement Learning](http://papers.neurips.cc/paper/8691-liir-learning-individual-intrinsic-reward-in-multi-agent-reinforcement-learning.pdf)|https://github.com/yalidu/liir|NIPS|2019
From Single-Agent to Multi-Agent|[MAPPO：The Surprising Effectiveness of MAPPO in Cooperative, Multi-Agent Games](https://arxiv.org/pdf/2103.01955)|https://github.com/marlbenchmark/on-policy||2021
Diversity|[Q-DPP：Multi-Agent Determinantal Q-Learning](http://proceedings.mlr.press/v119/yang20i/yang20i.pdf)|https://github.com/QDPP-GitHub/QDPP|ICML|2020
Ad Hoc Teamwork|[CollaQ：Multi-Agent Collaboration via Reward Attribution Decomposition](https://arxiv.org/pdf/2010.08531)|https://github.com/facebookresearch/CollaQ||2020
Value Decomposition|[NDQ: Learning Nearly Decomposable Value Functions Via Communication Minimization](https://arxiv.org/abs/1910.05366v1)|https://github.com/TonghanWang/NDQ|ICLR|2020
Value Decomposition|[QPLEX: Duplex Dueling Multi-Agent Q-Learning](https://arxiv.org/abs/2008.01062)|https://github.com/wjh720/QPLEX|ICLR|2021
Self-Play|[TLeague: A Framework for Competitive Self-Play based Distributed Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/2011.12895)|https://github.com/tencent-ailab/TLeague||2020
Transformer|[UPDeT: Universal Multi-agent Reinforcement Learning via Policy Decoupling with Transformers](https://openreview.net/forum?id=v9c7hr9ADKx)|https://github.com/hhhusiyi-monash/UPDeT|ICLR|2021
Sparse Reward|[Individual Reward Assisted Multi-Agent Reinforcement Learning](https://proceedings.mlr.press/v162/wang22ao/wang22ao.pdf)|https://github.com/MDrW/ICML2022-IRAT|ICML|2022
Ad Hoc|[Open Ad Hoc Teamwork using Graph-based Policy Learning](http://proceedings.mlr.press/v139/rahman21a/rahman21a.pdf)|https://github.com/uoe-agents/GPL|ICLM|2021
Generalization|[UNMAS: Multiagent Reinforcement Learningfor Unshaped Cooperative Scenarios](https://arxiv.org/pdf/2203.14477)|https://github.com/James0618/unmas|TNNLS|2021
Other|[SIDE: State Inference for Partially Observable Cooperative Multi-Agent Reinforcement Learning](https://www.ifaamas.org/Proceedings/aamas2022/pdfs/p1400.pdf)|https://github.com/deligentfool/SIDE|AAMAS|2022
Other|[Context-Aware Sparse Deep Coordination Graphs](https://arxiv.org/pdf/2106.02886)|https://github.com/TonghanWang/CASEC-MACO-benchmark|ICLR|2022


## TODO
* More papers will be added to [Other Papers](https://github.com/TimeBreaker/MARL-papers-with-code#other-papers).


## Citation

If you find this repository useful, please cite our repo:
```
@misc{chen2021multi,
  author={Chen, Hao},
  title={Multi-Agent Reinforcement Learning Papers with Code},
  year={2021}
  publisher = {GitHub},
  journal = {GitHub Repository},
  howpublished = {\url{https://github.com/TimeBreaker/MARL-papers-with-code}}
}
```