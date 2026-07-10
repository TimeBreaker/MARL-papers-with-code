# MARL Papers with Code
This is a collection of Multi-Agent Reinforcement Learning (MARL) papers with code. I have selected some relatively important papers with open source code and categorized them by time and method.

For MARL papers and MARL resources, please refer to [Multi Agent Reinforcement Learning papers](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers) and [MARL Resources Collection](https://github.com/TimeBreaker/MARL-resources-collection).

I will continually update this repository and I welcome suggestions. (missing important papers, missing categories, invalid links, etc.) This is only a first draft so far and I'll add more resources in the next few months.

**Update (2026):** Added a [Recent Papers with Code (2022–2026)](#recent-papers-with-code-2022-2026) section covering recent open-source work (value factorization, policy gradient, offline MARL, sequence/diffusion models, communication & coordination graphs, roles, ad hoc / zero-shot coordination, LLM-based multi-agent, adversarial/robust). Only papers with an official / well-known open-source repository are listed.

This repository is not for commercial purposes.

My email: chenhao915@mails.ucas.ac.cn


## Overview
* [Classic Papers](https://github.com/TimeBreaker/MARL-papers-with-code#classic-papers)
* [Other Papers](https://github.com/TimeBreaker/MARL-papers-with-code#other-papers)
* [Recent Papers with Code (2022–2026)](https://github.com/TimeBreaker/MARL-papers-with-code#recent-papers-with-code-2022-2026)
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


## Recent Papers with Code (2022–2026)
A curated batch of recent MARL papers that ship an official or widely-used open-source implementation. Grouped by topic.

Category|Paper|Code|Accepted at|Year
--|:--:|:--:|:--:|--:
Value Factorization|[ResQ: A Residual Q Function-based Approach for MARL Value Factorization](https://arxiv.org/abs/2205.15245)|https://github.com/xmu-rl-3dv/ResQ|NeurIPS|2022
Value Factorization|[DFAC: Factorizing Distributional Value Functions for Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2306.02430)|https://github.com/j3soon/dfac-extended|JMLR|2023
Value Factorization|[RiskQ: Risk-sensitive Multi-Agent Reinforcement Learning Value Factorization](https://arxiv.org/abs/2311.01753)|https://github.com/xmu-rl-3dv/RiskQ|NeurIPS|2023
Value Factorization|[Soft-QMIX: Integrating Maximum Entropy for Monotonic Value Function Factorization](https://arxiv.org/abs/2406.13930)|https://github.com/WentseChen/Soft-QMIX||2024
Value Factorization|[DoF: A Diffusion Factorization Framework for Offline MARL](https://openreview.net/forum?id=OTFKVkxSlL)|https://github.com/xmu-rl-3dv/DoF|ICLR|2025
Policy Gradient|[HATRPO/HAPPO: Trust Region Policy Optimisation in Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2109.11251)|https://github.com/morning9393/HAPPO-HATRPO|ICLR|2022
Policy Gradient|[A2PO: Order Matters: Agent-by-agent Policy Optimization](https://arxiv.org/abs/2302.06205)|https://github.com/xihuai18/A2PO-ICLR2023|ICLR|2023
Policy Gradient|[HARL: Heterogeneous-Agent Reinforcement Learning](https://jmlr.org/papers/v25/23-0488.html)|https://github.com/PKU-MARL/HARL|JMLR|2024
Policy Gradient|[HASAC: Maximum Entropy Heterogeneous-Agent Reinforcement Learning](https://arxiv.org/abs/2306.10715)|https://github.com/PKU-MARL/HARL|ICLR|2024
Policy Gradient|[BPTA: Backpropagation Through Agents](https://arxiv.org/abs/2401.12574)|https://github.com/LiZhYun/BackPropagationThroughAgents|AAAI|2024
Policy Gradient|[Optimistic Multi-Agent Policy Gradient](https://arxiv.org/abs/2311.01953)|https://github.com/wenshuaizhao/optimappo|ICML|2024
Offline MARL|[OMAR: Offline Multi-Agent Reinforcement Learning with Actor Rectification](https://proceedings.mlr.press/v162/pan22a.html)|https://github.com/ling-pan/OMAR|ICML|2022
Offline MARL|[CFCQL: Counterfactual Conservative Q Learning for Offline MARL](https://arxiv.org/abs/2309.12696)|https://github.com/thu-rllab/CFCQL|NeurIPS|2023
Offline MARL|[OMIGA: Offline MARL with Implicit Global-to-Local Value Regularization](https://arxiv.org/abs/2307.11620)|https://github.com/ZhengYinan-AIR/OMIGA|NeurIPS|2023
Offline MARL|[OG-MARL: Putting Data at the Centre of Offline Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2409.12001)|https://github.com/instadeepai/og-marl||2024
Sequence Model / Diffusion|[MAT: Multi-Agent Reinforcement Learning is a Sequence Modeling Problem](https://arxiv.org/abs/2205.14953)|https://github.com/PKU-MARL/Multi-Agent-Transformer|NeurIPS|2022
Sequence Model / Diffusion|[MADiff: Offline Multi-agent Learning with Diffusion Models](https://arxiv.org/abs/2305.17330)|https://github.com/zbzhu99/madiff|NeurIPS|2024
Sequence Model / Diffusion|[Oryx: A Scalable Sequence Model for Many-Agent Coordination in Offline MARL](https://arxiv.org/abs/2505.22151)|https://github.com/instadeepai/og-marl|NeurIPS|2025
Communication|[MAIC: Multi-Agent Incentive Communication via Decentralized Teammate Modeling](https://ojs.aaai.org/index.php/AAAI/article/view/21179)|https://github.com/mansicer/MAIC|AAAI|2022
Communication|[MASIA: Efficient Multi-agent Communication via Self-supervised Information Aggregation](https://openreview.net/forum?id=n4wnZAdBavx)|https://github.com/chenf-ai/MASIA|NeurIPS|2022
Communication|[CACOM: Context-aware Communication for Multi-agent Reinforcement Learning](https://arxiv.org/abs/2312.15600)|https://github.com/LXXXXR/CACOM|AAMAS|2024
Communication|[CommFormer: Learning Multi-Agent Communication from Graph Modeling Perspective](https://openreview.net/forum?id=Qox9rO0kN0)|https://github.com/charleshsc/CommFormer|ICLR|2024
Coordination Graph|[SOG: Self-Organized Group for Cooperative Multi-agent Reinforcement Learning](https://openreview.net/forum?id=hd5KRowT3oB)|https://github.com/thu-rllab/SOG|NeurIPS|2022
Coordination Graph|[GACG: Group-Aware Coordination Graph for Multi-Agent Reinforcement Learning](https://www.ijcai.org/proceedings/2024/434)|https://github.com/Wei9711/GACG|IJCAI|2024
Role|[ACORM: Attention-Guided Contrastive Role Representations for MARL](https://openreview.net/forum?id=LWmuPfEYhH)|https://github.com/NJU-RL/ACORM|ICLR|2024
Diversity|[DiCo: Controlling Behavioral Diversity in Multi-Agent Reinforcement Learning](https://proceedings.mlr.press/v235/bettini24a.html)|https://github.com/proroklab/ControllingBehavioralDiversity|ICML|2024
Ad Hoc Teamwork|[NAHT: N-Agent Ad Hoc Teamwork](https://arxiv.org/abs/2404.10740)|https://github.com/carolinewang01/naht|NeurIPS|2024
Zero-Shot Coordination|[HSP: Learning Zero-Shot Cooperation with Humans, Assuming Humans Are Biased](https://arxiv.org/abs/2302.01605)|https://github.com/samjia2000/HSP|ICLR|2023
Zero-Shot Coordination|[COLE: Cooperative Open-ended Learning Framework for Zero-shot Coordination](https://arxiv.org/abs/2302.04831)|https://github.com/liyang619/COLE-Platform|ICML|2023
Large Scale / Permutation Invariant|[HPN: Boosting MARL via Permutation Invariant and Permutation Equivariant Networks](https://openreview.net/forum?id=OxNQXyZK-K8)|https://github.com/tjuHaoXiaotian/API-Network|ICLR|2023
Benchmark|[BenchMARL: Benchmarking Multi-Agent Reinforcement Learning](https://jmlr.org/papers/v25/23-1612.html)|https://github.com/facebookresearch/BenchMARL|JMLR|2024
LLM-based Multi-Agent|[CAMEL: Communicative Agents for "Mind" Exploration of LLM Society](https://arxiv.org/abs/2303.17760)|https://github.com/camel-ai/camel|NeurIPS|2023
LLM-based Multi-Agent|[Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442)|https://github.com/joonspk-research/generative_agents|UIST|2023
LLM-based Multi-Agent|[Voyager: An Open-Ended Embodied Agent with Large Language Models](https://arxiv.org/abs/2305.16291)|https://github.com/MineDojo/Voyager|TMLR|2023
LLM-based Multi-Agent|[AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](https://arxiv.org/abs/2308.08155)|https://github.com/microsoft/autogen|COLM|2024
LLM-based Multi-Agent|[MetaGPT: Meta Programming for a Multi-Agent Collaborative Framework](https://arxiv.org/abs/2308.00352)|https://github.com/geekan/MetaGPT|ICLR|2024
LLM-based Multi-Agent|[ChatDev: Communicative Agents for Software Development](https://arxiv.org/abs/2307.07924)|https://github.com/OpenBMB/ChatDev|ACL|2024
LLM-based Multi-Agent|[AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors](https://arxiv.org/abs/2308.10848)|https://github.com/OpenBMB/AgentVerse|ICLR|2024
LLM-based Multi-Agent|[CoELA: Building Cooperative Embodied Agents Modularly with Large Language Models](https://arxiv.org/abs/2307.02485)|https://github.com/UMass-Embodied-AGI/Co-LLM-Agents|ICLR|2024
LLM-based Multi-Agent|[ProAgent: Building Proactive Cooperative Agents with Large Language Models](https://arxiv.org/abs/2308.11339)|https://github.com/PKU-Alignment/ProAgent|AAAI|2024
LLM-based Multi-Agent|[Eureka: Human-Level Reward Design via Coding Large Language Models](https://arxiv.org/abs/2310.12931)|https://github.com/eureka-research/Eureka|ICLR|2024
LLM-based Multi-Agent|[LLM-Coordination: Evaluating Multi-agent Coordination Abilities in Large Language Models](https://arxiv.org/abs/2310.03903)|https://github.com/eric-ai-lab/llm_coordination|NAACL Findings|2025
Adversarial / Robust|[AMI: Attacking Cooperative MARL by Adversarial Minority Influence](https://arxiv.org/abs/2302.03322)|https://github.com/DIG-Beihang/AMI||2023
Adversarial / Robust|[WALL: Wolfpack Adversarial Attack for Robust Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2502.02844)|https://github.com/sunwoolee0504/WALL|ICML|2025


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