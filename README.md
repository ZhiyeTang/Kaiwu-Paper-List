# 深圳大学X腾讯开悟教学项目：论文阅读清单

## 第一方论文

[1] [Wu, Bin. "Hierarchical macro strategy model for moba game ai." Proceedings of the AAAI Conference on Artificial Intelligence. Vol. 33. No. 01. 2019.](https://arxiv.org/pdf/1812.07887.pdf) (AAAI 2019)
> 本文提出了一种层次（Hierachical）强化学习模型，智能体首先通过模仿学习的方式制定宏观策略（Macro Strategy），再使用强化学习的方式学习微观策略（Micro Strategy）。

[2] [Ye, Deheng, et al. "Supervised learning achieves human-level performance in moba games: A case study of honor of kings." IEEE Transactions on Neural Networks and Learning Systems (2020).](https://arxiv.org/pdf/2011.12582.pdf) (TNNLS 2020)
> 本文将宏观策略与微观策略进行了进一步的结合，使用监督学习的方式令智能体达到了比人类玩家更优秀的水平。

[3] [Ye, Deheng, et al. "Mastering complex control in moba games with deep reinforcement learning." Proceedings of the AAAI Conference on Artificial Intelligence. Vol. 34. No. 04. 2020.](https://arxiv.org/pdf/1912.09729.pdf) (AAAI 2020)
> 详细介绍了代码包中使用的强化学习算法的设计细节。

[4] [Ye, Deheng, et al. "Towards playing full moba games with deep reinforcement learning." Advances in Neural Information Processing Systems 33 (2020): 621-632.](https://arxiv.org/pdf/2011.12692.pdf) (NeurIPS 2020)
> 基于强化学习，引入策略蒸馏（Policy Distillation）的思想将多个专家策略的知识压缩到一个模型上，让一个模型学会多个英雄的玩法。

[5] [Gao, Yiming, et al. "Learning Diverse Policies in MOBA Games via Macro-Goals." Advances in Neural Information Processing Systems 34 (2021): 16171-16182.](https://arxiv.org/pdf/2110.14221.pdf) (NeurIPS 2021)
> 本文设计了一个元控制器（Meta-Controller）和宏观策略引导（Macro-Goals Guided，MGG）的训练框架。元控制器通过有监督学习人类专家的操作意图，然后再放置到强化学习框架中进行进一步的强化学习。

## 第三方论文

[1] [Jiang, Daniel R., Emmanuel Ekwedike, and Han Liu. "Feedback-Based Tree Search for Reinforcement Learning." ICML. 2018.](https://arxiv.org/pdf/1805.05935.pdf) (ICML 2018)

[2] [Wang, Qing, et al. "Exponentially weighted imitation learning for batched historical data." Advances in Neural Information Processing Systems 31 (2018).](https://dl.acm.org/doi/pdf/10.5555/3327345.3327526) (NeurIPS 2018)

[3] [Eisenach, Carson, et al. "Marginal policy gradients: A unified family of estimators for bounded action spaces with applications." 7th International Conference on Learning Representations, ICLR 2019. 2019.](https://arxiv.org/pdf/1806.05134.pdf) (ICLR 2019)

[4] [Cheng, Ziqiang, et al. "What makes a good team? a large-scale study on the effect of team composition in honor of kings." The World Wide Web Conference. 2019.](https://arxiv.org/pdf/1902.06432.pdf) (WWW 2019)

[5] [Wei, Hua, et al. "Boosting Offline Reinforcement Learning with Residual Generative Modeling." 30th International Joint Conference on Artificial Intelligence, IJCAI 2021. International Joint Conferences on Artificial Intelligence, 2021.](https://arxiv.org/pdf/2106.10411.pdf) (IJCAI 2021)