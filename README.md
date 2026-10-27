# dtc-store-ops

DTC 独立站从 0 到 1 ，从1到10，经营方法论与操盘 playbook。

这套 skill 来自多个真实项目的完整生命周期：欧美市场、1–10 人团队、约 $100 客单价、5年周期。重点在方论多实践和迭代。——**它编码的是一次失败换来的经营纪律，不是成功学。**

核心信念：**网站上线不是从 0 到 1，订单能够重复才是。**

## 包含什么

| 文件 | 内容 |
|---|---|
| `SKILL.md` | 入口：十条核心纪律 + 阶段工作流决策树（先读这个） |
| `references/unit-economics.md` | 贡献利润测算、三个数字、红线与停止规则、现金流倒挂 |
| `references/validation-playbook.md` | 关键词四篮、竞品拆解、VOC 证据链、小流量验证 |
| `references/google-ads-playbook.md` | 账户结构、三档爬坡、周节奏、数据症状倒推表 |
| `references/supply-chain-and-fulfillment.md` | 选品否决项、尾程结构、退货、现金周期、规模不经济 |
| `references/retrospective-and-fundraising.md` | 0→1 五条件、信号复盘法、融资叙事三要素 |
| `references/brand-positioning.md` | 品牌定位一句话模板 + 五问 + 一致性检查 |
| `references/edm-lifecycle.md` | EDM：三条自动化、弃购纪律、复购周期设计 |
| `references/affiliate-marketing.md` | 联盟营销：漏斗八阶段、佣金政策、激活、违规监控 |
| `references/pr-outreach.md` | PR 外联：编辑四分法、开发信结构、CRM、分层衡量 |
| `references/case-study-gift-store.md` | 匿名案例：两年期礼物站完整复盘 |
| `references/category-adapters/gifts-home.md` | **基准品类适配器**：礼物/家居参数、阈值与四个坑 |
| `references/category-adapters/hardware.md` | **硬件品类适配器**：机器人/3D打印机——认证、参数页、社区、众筹、耗材 LTV、售后 |
| `templates/sku-profit-table.md` | SKU 利润表（含硬件双线核算列） |
| `templates/search-term-log.md` | 搜索词台账（含硬件问题词标记） |
| `templates/weekly-dashboard.md` | 周经营看板 |
| `templates/voc-evidence-table.md` | VOC 证据表 |
| `templates/hardware-certification-checklist.md` | 硬件认证核查表（上线前一票否决） |

**版本说明**：v1.0 为礼物/家居单品类基准；v1.1 起引入"纪律层 + 品类适配层"架构——SKILL.md 永远只放品类无关内容，新品类通过 `category-adapters/` 扩展，换品类前先过"适配七问"。v1.2 补齐经营闭环的放大器模块：品牌定位、EDM、联盟营销、PR 外联。

## 在 WorkBuddy 中使用

把整个 `dtc-store-ops/` 目录复制到 skills 目录：

```bash
# WorkBuddy
cp -r dtc-store-ops ~/.codebuddy/skills/
```

之后对话中出现独立站/DTC/Shopify/Google Ads/ROAS/选品/复盘等话题时，skill 会自动触发；也可以显式调用。

## 在 Codex 中使用

Codex 会自动读取仓库根目录的 `AGENTS.md`。把本仓库放到工作区（或把 `AGENTS.md` 内容并入你的项目级 `AGENTS.md`），Codex 即按其中的指令加载本 playbook。

## 给其他 Agent / 人工使用

所有内容都是纯 Markdown，任何能读文件的 agent 都可以直接消费：从 `SKILL.md` 开始，按决策树进入对应 `references/`。表格模板可直接复制到 Google Sheet / 飞书多维表 / Notion。

## 使用原则

1. 顺序执行：先算账 → 再验证 → 再打渠道 → 再谈放大 → 最后复盘。跳步的代价在后面成倍出现。
2. 所有示例数字均为教学口径，决策前用你自己的后台数字替换。
3. 这套纪律按 1–3 人团队、$10k–$50k 启动资金的产能设计；团队变大后，先改清单密度，再扩动作。

## 免责声明

本项目为经验方法论沉淀，不构成投资、经营或法律建议。合规、认证、税务、隐私事项请以目的国专业意见为准。案例数据已脱敏，请勿对号入座。

## License

MIT，见 `LICENSE`。
