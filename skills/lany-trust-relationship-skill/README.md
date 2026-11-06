# 信任与关系维护技能使用说明

`lany-trust-relationship-skill` 帮你设计真正有用的小礼物、交付回访与合适的联系节奏。

## 什么时候用

想持续分享经验而不想频繁推销；免费材料有人领取但不知道是否有用；交付完成后需要了解客户结果；想判断复购、推荐或社群是否适合业务。

## 输入与输出

输入关系背景、对方的问题、已有承诺、反馈和联系边界。输出礼物说明、消息草稿、联系表、兑现记录。它不会自动发私信、加好友、拉群或发送邮件。

## 完整示例（虚构演示）

输入：

> 使用 $lany-trust-relationship-skill。五位项目经理自愿领取了我的会议行动清单，其中两位允许本周五回访。我只想了解是否能用，不要催单，也不建群。

合理输出：

- 礼物：一页行动清单和一份填写示例，完整解释负责人、期限、验收项，注明需要会上确认负责人，不替团队分派任务。
- 周五回访草稿：“这周的行动清单用上了吗？如果用了，哪一列最难填？没用也没关系，我主要想知道哪里不适合你。”
- 联系计划：只向同意周五回访的两位起草回访；其余三位暂不主动追问。按已有同意范围执行，未授权发送时只交草稿。
- 兑现记录：是否打开和是否使用分开；有实际行动清单才记为已使用，无法填写的字段记作产品问题。
- 后续：如果原表有缺陷先修复；只有对方主动表示需要更复杂协助，才说明可提供的服务及边界。
- 停止：明确不需要就结束；没有回应不连续催问。无需把每个人导入社群。

未观察到实际使用前，不能声称五位用户已经获得结果，更不能据此写推荐评价。

## 边界

不把赠予当人情债；不以联系次数衡量信任；不把付费当交付完成；低频业务无需复购。本方法不保证关系改善、复购或收益。

- [执行规范](SKILL.md)
- [价值赠予与交付回访方法指南](references/methods.md)：需要制作礼物、安排回访与核对兑现时读取，包含工作模板、虚构演示和停止规则。

## 独立仓库与安装

仓库：[lany-trust-relationship-skill](https://github.com/LanyXiaosheng/lany-trust-relationship-skill)。独立仓库根目录即技能目录，包含 `SKILL.md`、本说明及 `references/`。

确认目标目录不存在后，可在未设置 `CODEX_HOME` 的默认环境下安装：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/LanyXiaosheng/lany-trust-relationship-skill.git ~/.codex/skills/lany-trust-relationship-skill
```

已设置 `CODEX_HOME` 时，将目标改为该目录下的 `skills/lany-trust-relationship-skill`。已有同名技能时先比较或备份，不覆盖。客户端发现技能后，使用 `$lany-trust-relationship-skill` 调用。

方法指南随本仓库保存和维护。浏览其他技能可进入[合集](https://github.com/LanyXiaosheng/lany-creator-skills)。
