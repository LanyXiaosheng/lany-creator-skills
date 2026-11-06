---
name: lany-creator-workbench-skill
description: Lany 创作者工作台总入口。用户调用本工具箱、希望串联定位与内容变现方法，或不确定该用哪一个 Lany 专项技能时，用它识别当前瓶颈并选择最小工作流；明确的单项任务直接使用对应技能。
---

# Lany 创作者工作台

把当前问题路由到一项能交付结果的工作。本入口按产物组织九项专项技能，用于选路与交接。

## 先确定交付物

从对话提取目标、已有材料、卡点和资源限制。已有信息不重复问；只有缺失信息会改变选路或导致虚构时才提出简短问题，同时推进不依赖该信息的部分。

用户明确要脚本就完成脚本，不要求先做商业定位或建库。用户说“都想做”，先找到最靠近目标的一项产物，其余列为后续选项。

## 选路

根据下表选择对应技能，不一次加载全部技能。优先读取本地同级目录 `../技能名/SKILL.md`；表中链接指向独立公开仓库，供浏览和获取。若本地缺失，只有实际读取到对应文件后才按该技能执行，不把链接存在当成已经安装。

| 当前问题或产物 | 读取技能 | 判断边界 |
| --- | --- | --- |
| 面向谁、解决什么问题、凭什么值得信任 | [价值定位](https://github.com/LanyXiaosheng/lany-value-positioning-skill/blob/main/SKILL.md) | 定位假设与证据，不虚构市场结论 |
| 从一件小事获得真实付费反馈 | [小生意验证](https://github.com/LanyXiaosheng/lany-small-bet-business-skill/blob/main/SKILL.md) | 交付、报价假设、小规模验证，不承诺收益 |
| 长期维护互惠关系、兑现价值 | [信任关系](https://github.com/LanyXiaosheng/lany-trust-relationship-skill/blob/main/SKILL.md) | 提供行动建议，不自动联系别人 |
| 把原始素材形成可调用的认识 | [洞见卡](https://github.com/LanyXiaosheng/lany-insight-card-skill/blob/main/SKILL.md) | 来源、边界和检验方法 |
| 读书学习要解决当前实际项目问题 | [项目式学习](https://github.com/LanyXiaosheng/lany-project-learning-skill/blob/main/SKILL.md) | 项目相关的学习产物与实践方案 |
| 笔记调用不起来，想建立运行中的知识库 | [知识工作流](https://github.com/LanyXiaosheng/lany-knowledge-workflow-skill/blob/main/SKILL.md) | 适配现有目录，按当前授权落盘 |
| 已有经历、观点或素材，要能拍的口播 | [短视频脚本](https://github.com/LanyXiaosheng/lany-short-video-script-skill/blob/main/SKILL.md) | 素材支持的表达，不代造经历 |
| 从对标中学会起作用的方法 | [内容拆解迁移](https://github.com/LanyXiaosheng/lany-content-remix-skill/blob/main/SKILL.md) | 分开结构观察与心理假设 |
| 持续创作但无法判断该改哪里 | [内容实验](https://github.com/LanyXiaosheng/lany-content-experiment-skill/blob/main/SKILL.md) | 下一轮可判断试验，不把相关性当因果 |

## 串联时保留证据

仅当一个技能的产出确实是下一项的输入时串联。可从任一点进入或跳过已完成部分：

- 学到一个新观点：项目式学习 → 洞见卡 → 脚本。
- 有兴趣但不知道做什么生意：价值定位 → 小生意验证；内容作为获客手段时再考虑脚本和实验。
- 有同类账号参考却不知道为什么有效：拆解迁移 → 脚本 → 内容实验。
- 旧笔记很多但找不到素材：知识工作流 → 洞见卡。

传递已知事实、来源、待验证假设、用户限制、本次产物。不要把上一阶段的猜测升级成下一阶段的事实；缺失的客户评价、财务数字或结果继续保持缺失。

## 交付与验收

先给请求的具体产物，再简述所选技能及理由。多个产物说明关系，不抄整份技能目录。成功标准是当前产物能被使用或检验，而非调用技能越多越好。

- 选路是否符合用户已经明确的任务？
- 是否保留真实材料、假设和虚构示例的区别？
- 是否实际交付结果，而非只建议用户使用某个技能？
- 是否把纯写作扩展成建库，把复盘扩展成发帖？若是则缩回任务范围。

生成方案不授予发帖、收款、联系客户的权限。引用技能缺失时说明具体文件，完成已有依据支持的部分，不假称执行过缺失技能。

调用示例见[使用说明](README.md)。需要判断相邻技能的边界、设计串联顺序或检查交接信息时，读取本地[方法指南](references/methods.md)。
