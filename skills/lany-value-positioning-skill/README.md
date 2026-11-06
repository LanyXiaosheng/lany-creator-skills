# 价值定位技能使用说明

`lany-value-positioning-skill` 把泛泛的个人IP方向变成可验证的服务对象和内容承诺。

## 什么时候用

不知道自己能提供什么；经历很多却讲不清差异；内容有人看但不知道给谁带来何种改变。已有定位、只要一段口播稿时不必使用。

## 给什么、得到什么

给出真实经历、已解决的问题、用户原话、能力与时间边界。技能返回定位卡、证据缺口和一份最小试用内容，不承诺涨粉或收入。

## 完整示例（虚构演示）

输入：

> 使用 $lany-value-positioning-skill。我做行政，给同事改过两次会议纪要模板，但没有收费经验。三位项目经理抱怨“纪要写了，任务还是没人接”。每周只有三小时，我不想做泛职场博主，也不提供管理咨询。

合理输出：

- 对象：每周开跨部门例会、会后需要追踪任务的项目经理。
- 卡点：记录了讨论，却未明确负责人、截止时间和验收结果。
- 证据：两次模板改写是实际经验；三位经理的抱怨是问题信号。尚无证据证明模板能提高团队履约率。
- 承诺：帮助把一份纪要改成带负责人、期限和验收项的行动清单，不承诺团队一定按时执行。
- 本色锚点：“把会议纪要改成待办清单的行政同事”。不包装成组织管理专家。
- 试用内容：用一份脱敏的虚构纪要展示如何抽取行动项，附空白清单。
- 下一步：邀请愿意试用的经理在一次例会后使用；记录哪些行动项仍然无法指派、是否能独立使用。先验证可用性，再决定是否提供付费代整理。

这是示例输入推导出的方案，不是用户的真实业务数据。

## 不适用边界

不代做头像设计，不猜受众隐私，不根据平台流量强行确定商业方向。没有用户证据时输出的是假设定位。

## 文件

- [SKILL.md](SKILL.md)：模型执行规范。
- [价值定位方法指南](references/methods.md)：比较候选方向、填写定位卡和设计试用时读取，包含决策规则、模板、虚构演示和验收边界。

## 独立仓库与安装

仓库：[lany-value-positioning-skill](https://github.com/LanyXiaosheng/lany-value-positioning-skill)。独立仓库根目录即技能目录，包含 `SKILL.md`、本说明及 `references/`。

确认目标目录不存在后，可在未设置 `CODEX_HOME` 的默认环境下安装：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/LanyXiaosheng/lany-value-positioning-skill.git ~/.codex/skills/lany-value-positioning-skill
```

已设置 `CODEX_HOME` 时，将目标改为该目录下的 `skills/lany-value-positioning-skill`。已有同名技能时先比较或备份，不覆盖。客户端发现技能后，使用 `$lany-value-positioning-skill` 调用。

方法指南随本仓库保存和维护。浏览其他技能可进入[合集](https://github.com/LanyXiaosheng/lany-creator-skills)。
