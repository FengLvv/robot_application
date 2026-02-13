# VR-WoZ Toolkit 项目概述

## 项目名称
Unity VR-WoZ Toolkit - 面向具身智能交互研究的VR模拟工具包

## 项目定位
为设计研究人员提供低成本、高效率的具身智能（人形机器人）交互验证工具

## 核心价值
- 降低具身智能交互研究的门槛和成本
- 使设计师能够在产品落地前验证交互方案
- 优化传统WoZ方法的局限性

## 技术栈
- **VR平台**: Unity + PICO Unity Integration SDK
- **目标设备**: PICO VR设备
- **控制接口**: Python API
- **动作捕捉**: CV2 真人动作识别

## 当前限制
- 仅适用于人形机器人（因采用CV2识别真人动作来操作VR中的机器人）
- 非人形机器人无法直接套用动作映射

## 文档结构
```
docs/
├── 00_project_overview.md          # 本文档
├── 01_research_background/         # 研究背景
│   ├── problem_statement.md        # 问题陈述
│   ├── literature_review.md        # 文献综述
│   └── woz_method_analysis.md      # WoZ方法分析
├── 02_brainstorming/               # 头脑风暴
│   ├── humanoid_robot_applications.md  # 人形机器人应用场景
│   └── decision_log.md             # 决策日志
├── 03_requirements/                # 需求文档
│   ├── vr_woz_toolkit_prd.md       # 产品需求文档
│   └── user_personas.md            # 用户画像
├── 04_user_journeys/               # 用户旅程
│   ├── researcher_journey.md       # 研究人员使用流程
│   ├── designer_journey.md         # 设计师使用流程
│   └── participant_journey.md      # 实验参与者体验流程
└── 05_technical_design/            # 技术设计
    ├── system_architecture.md      # 系统架构
    └── api_design.md               # Python API 设计
```

## 项目阶段
- [x] 立项阶段 - 当前
- [ ] 需求分析
- [ ] 技术设计
- [ ] 开发实现
- [ ] 测试验证
- [ ] 文档完善

---
*创建日期: 2026-02-13*

