# 总入口使用说明

不知道该用哪个专项技能时从这里开始；已明确要脚本、卡片等产物时可直接调用对应技能。

## 需要提供

当前目标、已有材料、卡点和时间等限制。不必先填长问卷。缺少资料的结论只能作为假设；信息够用时直接工作。

## 示例（虚构）

```text
$lany-creator-workbench-skill
我有30条AI工具使用笔记，想做面向独立设计师的内容。
目前没有客户数据，每周可用3小时。
请确定本周该产出什么，并完成第一份产物。
```

合理起点可能是整理一个可验证的用户问题，或从已经提供的笔记建立洞见卡。不能据此断言设计师一定愿意购买服务。

## 会得到什么

定位草案、洞见卡、口播稿或下轮实验等当前任务的具体产物，以及简短的选路理由。需要多个环节时保留输入输出，不机械地运行全部九个技能。

## 明确任务时直接调用

```text
$lany-short-video-script-skill 把下面真实经历改成60秒口播，保留事实，不增加成绩或收入数字。
```

完整选择表见[SKILL.md](SKILL.md)。本入口不替代平台实时规则查询，不自动发布、联系他人，也不承诺涨粉收益。本地[方法指南](references/methods.md)提供选路规则、交接模板及完整示例。

## 独立仓库与安装

仓库：[lany-creator-workbench-skill](https://github.com/LanyXiaosheng/lany-creator-workbench-skill)。独立仓库根目录即技能目录，包含 `SKILL.md`、本说明及 `references/`。

确认目标目录不存在后，可在未设置 `CODEX_HOME` 的默认环境下安装：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/LanyXiaosheng/lany-creator-workbench-skill.git ~/.codex/skills/lany-creator-workbench-skill
```

已设置 `CODEX_HOME` 时，将目标改为该目录下的 `skills/lany-creator-workbench-skill`。已有同名技能时先比较或备份，不覆盖。客户端发现技能后，使用 `$lany-creator-workbench-skill` 调用。

总入口需要读取专项技能后才能完整执行。可单独安装需要的专项技能，并与本目录保持同级；专项技能列表及公开仓库链接见 [SKILL.md](SKILL.md)。它不会因安装本入口而自动安装其他技能。

方法指南随本仓库保存和维护。浏览其他技能可进入[合集](https://github.com/LanyXiaosheng/lany-creator-skills)。
