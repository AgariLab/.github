# AgariLab - 和牌研究所

可复现的日麻 AI 研究：从强基线出发，用固定对手评测、自博弈和限时搜索持续改进。

长期目标是世界顶尖棋力；当前处于工程基础建设阶段，尚无已验证的棋力成果。

| 项目 | 职责 |
| --- | --- |
| [agari-kit](https://github.com/AgariLab/agari-kit) | Agent 接口、数据质量、评测、牌谱和平台适配 |
| [agari-research](https://github.com/AgariLab/agari-research) | GRP → CQL → PPO 基线复现、模型、训练和实验 |
| [RiichiEnv](https://github.com/AgariLab/RiichiEnv) | 上游环境 fork、规则回归和引擎补丁 |

初期专注四人赤牌半庄。代码默认 Apache-2.0，数据和模型按来源许可分别管理。
目前正在完成首期工程闭环；安装、数据、训练和评测命令以各仓库 README 为准。
