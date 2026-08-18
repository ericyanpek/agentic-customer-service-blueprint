# 游戏智能客服参考架构

本目录沉淀一套面向游戏内 MVP 场景的 AWS 智能客服心智模型、参考架构与实施演进计划。

内容基于截至 2026-08-18 的 Amazon Bedrock、Amazon Bedrock AgentCore 和 Strands Agents 能力。知识库工程化治理与共享记忆工程化治理被视为独立的旁路平台，本项目只定义智能客服如何消费这些能力。

## 文档索引

1. [智能客服全景心智模型](docs/intelligent-customer-service-mental-model.md)
2. [游戏内智能客服 MVP 实现与演进规划](docs/game-customer-service-mvp-roadmap.md)
3. [行业案例映射：某全球在线教育企业](docs/industry-case-mapping-online-education.md)
4. [权威资料中的智能客服定位、主流实践与规划基线](docs/authoritative-market-practices-intelligent-customer-service.md)

## 核心判断

智能客服不是一个会聊天的 RAG 应用，而是：

> 以工单为业务单元、以 Agent 为决策中枢、以工具为执行手段、以确定性策略为安全边界、以人工客服为风险兜底的问题解决系统。

## 文档使用方式

- 方案交流：从心智模型中的全景图和职责边界开始。
- MVP 立项：使用路线图中的范围、里程碑和验收门槛。
- 技术设计：将路线图中的待决策项进一步拆成 ADR。
- 方案演示：以充值未到账场景作为端到端主路径。
