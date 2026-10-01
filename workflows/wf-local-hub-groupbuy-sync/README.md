# 团购信息多平台同步

> 套餐变更 → 各平台上架信息核对清单

工作流 `wf-local-hub-groupbuy-sync`　·　归属 多平台运营中台　·　触发 人工触发+定时校验　·　
复杂度 L（各平台无开放写接口，需半自动）　·　阶段 P2

## 调用链

- `多平台连接`（multichannel-connector）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 多平台运营中台 的「团购信息多平台同步」：<你的输入>
```
