# Lany Creator Skills

面向创作者的10个可复用AI技能：9个专项方法与1个总入口，覆盖价值定位、小生意验证、信任关系、洞见卡、项目学习、知识工作流、短视频脚本、内容拆解迁移和实验复盘。

每个技能都是独立目录，包含模型指令、中文使用说明与本地方法指南。技能以具体产物组织，可单独使用，也可由总入口按当前问题选择。

## 技能目录

| 技能 | 用途 |
| --- | --- |
| [lany-creator-workbench-skill](skills/lany-creator-workbench-skill/README.md) | 总入口：识别当前瓶颈，选最小工作流并完成产物 |
| [lany-value-positioning-skill](skills/lany-value-positioning-skill/README.md) | 从真实能力与用户问题形成可验证的价值定位 |
| [lany-small-bet-business-skill](skills/lany-small-bet-business-skill/README.md) | 将业务想法拆成有成本边界的小规模验证 |
| [lany-trust-relationship-skill](skills/lany-trust-relationship-skill/README.md) | 价值赠予、交付回访与持续关系维护 |
| [lany-insight-card-skill](skills/lany-insight-card-skill/README.md) | 素材变成有来源、行动和边界的洞见卡 |
| [lany-project-learning-skill](skills/lany-project-learning-skill/README.md) | 用阅读和实践解决当前项目的具体卡点 |
| [lany-knowledge-workflow-skill](skills/lany-knowledge-workflow-skill/README.md) | 让现有笔记完成采集、加工、检索调用与复盘 |
| [lany-short-video-script-skill](skills/lany-short-video-script-skill/README.md) | 将真实经历、观点或录音整理成可拍摄口播 |
| [lany-content-remix-skill](skills/lany-content-remix-skill/README.md) | 拆解对标结构与受众机制，用自己的证据原创迁移 |
| [lany-content-experiment-skill](skills/lany-content-experiment-skill/README.md) | 内容切片、同口径比较、单变量试验和复盘 |

详细输入、产物、示例与组合方式见[技能总览](技能总览.md)。

## 文件结构

每个技能包含：

- `SKILL.md`：名称、触发条件、方法、产物与完成检查。
- `README.md`：面向使用者的中文说明和完整示例。
- `references/methods.md`：随仓库保存的方法、步骤、模板、虚构示例和反例。

## 在Codex中使用

克隆本仓库：

```bash
git clone https://github.com/LanyXiaosheng/lany-creator-skills.git
```

将需要的技能目录从 `skills/` 复制到 `$CODEX_HOME/skills`；未设置CODEX_HOME时通常为 `~/.codex/skills`。遇到同名目录先比较、备份，不直接覆盖。使用总入口时，将全部10个目录放在同一父目录，以保留相对引用。

客户端发现技能后，在对话中调用：

```text
$lany-creator-workbench-skill
这是我的目标、现有材料和时间限制。请选择适合的方法，并完成第一份产物。
```

明确任务时直接调用专项技能：

```text
$lany-short-video-script-skill
把下面真实经历改成60秒口播，保留事实，不增加成绩或收入数字。
```

其他支持SKILL.md格式的工具可按各自的加载方式使用；本仓库不宣称已经验证所有客户端。技能本身不需要额外程序依赖。

## 本地方法文档

每个技能都附带重新整理的方法指南，使用仓库内的相对链接读取。内容已去除原资料中的个人品牌、人设、账号、联系方式与文章网页链接，保留用户自己的Lany技能命名。

方法文档提供操作步骤、判断条件、可填写模板、完整虚构示例、反例与验收标准。它们是重新组织的工作说明，不是原资料全文，也不冒充真实用户经历或商业成果。技能执行无需访问原文网站。

## 范围与验证

技能的核心流程已通过格式与引用检查，并完成6个独立场景试用；本地方法文档更新另做文件、引用与内容检查。试用覆盖真实素材脚本、不可比数据复盘、知识库方案、洞见卡、小业务验证和总入口选路；不代表所有场景或商业效果已被验证。

技能不保证涨粉或收益，不把单次观察当作普遍因果；所有示例均标注为示例。发帖、私信、上传、收款及文件删除等操作仍以当前用户请求为准。
