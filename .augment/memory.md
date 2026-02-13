# VR-WoZ Toolkit 项目记忆

## 项目概述

**项目名称**: VR-WoZ Toolkit  
**目标**: 构建Unity VR-WoZ实验包，帮助设计研究人员低成本验证人形机器人交互设计  
**技术栈**: Unity + PICO Unity Integration SDK + Python API + CV2动作捕捉  
**限制**: 仅适用于人形机器人（CV2识别真人动作控制VR机器人）

## 实验设计

### 实验角色分工
- **实验员A**: 主控，把握实验进度，主动打字/说话开启话题
- **实验员B**: 配合A，控制机器人进行动作
- **被试C**: 戴VR眼镜，与虚拟机器人交互

### 关键约束：被试可行性
被试C必须能够使用VR设备，因此：
- ✅ 年轻人/大学生：容易招募，VR适用性好
- ❌ 老年人：难以招募，VR适用性差，伦理审批复杂

**核心洞察**: 被试不一定是最终用户。可以用年轻人验证交互设计。

## 应用场景评估结果（V2 - 2026-02-13）

### 🏆 推荐场景 Top 5

| 排名 | 场景 | 被试可行性 | 行业热点 |
|------|------|------------|----------|
| 🥇 | **家庭助手** | ⭐⭐⭐⭐⭐ 年轻人/大学生 | 1X NEO 2026预售 |
| 🥈 | **汽车/制造业工厂** | ⭐⭐⭐⭐ 大学生模拟工人 | Tesla Optimus, Figure+BMW |
| 🥉 | **餐饮服务** | ⭐⭐⭐⭐⭐ 任何人当顾客 | 北京机器人餐厅 |
| 4 | **酒店/展馆引导** | ⭐⭐⭐⭐⭐ 任何人当访客 | 世界机器人大会 |
| 5 | **安防巡逻** | ⭐⭐⭐⭐ 大学生模拟 | 东京都厅 |

### ❌ 不推荐场景

| 场景 | 原因 |
|------|------|
| **养老护理** | 老人难以使用VR设备、招募困难、伦理审批复杂 |
| 仓储物流 | 人形必要性低（轮式AGV更常见） |
| 表演/娱乐 | 交互验证需求低 |

## 文档结构

```
docs/
├── 00_project_overview.md              # 项目概述
├── 01_research_background/
│   ├── problem_statement.md            # 问题陈述
│   └── woz_method_analysis.md          # WoZ方法分析
├── 02_brainstorming/
│   ├── humanoid_robot_applications.md  # V1 头脑风暴版
│   └── humanoid_robot_applications_v2_trends.md  # V2 行业热点+被试可行性版
├── 03_requirements/                    # 待填充
├── 04_user_journeys/                   # 待填充
└── 05_technical_design/                # 待填充
```

## 已安装的Skills

- `multi-agent-brainstorming`: 多代理头脑风暴
- `product-requirements`: 产品需求文档
- `deep-research`: 深度研究
- `user-journeys`: 用户旅程
- `perplexity`: Perplexity AI搜索
- `google-trends`: Google趋势分析

## 下一步建议

1. 从Top 3中选择1-2个场景深入研究
2. 使用 `product-requirements` skill 编写详细实验需求
3. 使用 `user-journeys` skill 设计实验流程
4. 使用 `deep-research` skill 进行文献研究

## 关键决策记录

| 日期 | 决策 | 原因 |
|------|------|------|
| 2026-02-13 | 排除养老护理场景 | 老人难以使用VR设备，被试可行性极低 |
| 2026-02-13 | 家庭助手排名第一 | 被试极易招募 + 2026商业化元年 + 交互空间大 |
| 2026-02-13 | V2完全重写 | 基于网络搜索行业热点，不参考V1结果 |

