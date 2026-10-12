# supply-chain-management

基于 Sunil Chopra《Supply Chain Management》知识框架整理的供应链分析技能（概括，非原文复刻）。涵盖战略匹配、六大驱动因素、网络设计、需求预测、S&OP、库存（EOQ、安全库存、报童模型）、运输、采购与合约、定价、牛鞭效应、风险与财务评估。

A supply chain analysis skill based on the frameworks in Sunil Chopra's *Supply Chain Management* (summarized, not reproduced).

## 安装 / Install

### Claude Code
```bash
git clone https://github.com/demian-enzo/supply-chain-management ~/.claude/skills/supply-chain-management
```
项目级可放到 `.claude/skills/supply-chain-management/`。

### Claude.ai / Claude 桌面版
将本仓库下载为 zip，在 Settings → Capabilities → Skills 上传。

### Cursor
```bash
git clone https://github.com/demian-enzo/supply-chain-management .cursor/skills/supply-chain-management
```

### 其他工具
把 `SKILL.md` 的内容作为系统提示或自定义指令使用即可。

## 使用示例
> 年需求 12000 件，周需求标准差 60，单价 50 元，持有成本率 20%，订货成本 200 元，提前期 2 周，服务水平 95%，求 EOQ、安全库存和再订货点。

技能会输出：结论、关键计算、权衡、假设和建议。
