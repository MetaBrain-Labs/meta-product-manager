# Meta-Product-Manager

AI 产品经理 Skill——以专业产品经理方法论协助用户从零设计或完善产品，输出标准化产品文档。

## 简介

Meta-Product-Manager 是一个面向 IDE（如 Cursor、Trae）的 AI Skill，模拟专业产品经理的工作方式，通过结构化的多轮对话，帮助用户将模糊的产品想法转化为清晰的产品文档，支持从需求探索到商业验证的完整产品设计流程。

## 适用场景

- 将初步想法完善为完整的产品方案
- 将产品需求落地为可与研发对接的 PRD
- 竞品分析与商业可行性调研
- 创业产品从 0 到 1 的产品设计
- 产品方案自检与逻辑闭环验证

## 工作准则

- **结果导向**：交付可持久化保存的文档产物，对话用于推进决策
- **实事求是**：区分可推导事实与推测判断，明确标注假设内容
- **决策清晰**：不模棱两可，每个决策有明确依据
- **逐步推进**：拆分多轮讨论，逐项确认，不追求一次性输出所有内容
- **人工确认**：关键决策和产物交付前由用户确认，不越过用户推进流程

## 核心能力

### 需求验证

将模糊的产品想法转化为结构清晰、有共识的产品轮廓。

输出产物：产品草案、用户故事

### 产品落地

深化产品轮廓，完成业务建模、功能层级设计与 PRD 编写，为研发交付做准备。

输出产物：产品需求文档（PRD）

### 商业验证

调研产品的商业价值，包括市场规模、竞品分析、用户付费意愿等，辅助商业决策。

输出产物：市场需求文档（MRD）、商业需求文档（BRD）

### 产品检测

以用户视角验证产品逻辑是否形成闭环，发现设计缺陷并修正。

## 文档模板

`assets/templates/` 目录提供以下标准化文档模板：

| 模板 | 用途 |
|---|---|
| `product-draft-template.md` | 产品草案：定义产品定位、目标用户、核心功能与边界 |
| `user-story-template.md` | 用户故事：描述不同维度下的用户使用场景 |
| `product-requirement-document-template.md` | 产品需求文档：面向研发的功能需求详细说明 |
| `market-requirement-document-template.md` | 市场需求文档：市场与用户需求分析 |
| `business-requirement-document-template.md` | 商业需求文档：商业目标与可行性分析 |

## 参考指南

`references/` 目录包含标准化作业指导：

| 指南 | 内容 |
|---|---|
| `project-building-guide.md` | 产出文件的目录组织结构 |
| `document-writing-standard.md` | 文档命名、格式、版本与表达规范 |
| `needs-brainstorm-guide.md` | 需求头脑风暴：整理 → 发散 → 收敛 |
| `user-needs-exploration-guide.md` | 用户需求发散的 17 个维度检查表 |
| `distinguish-user.md` | 区分对话用户与产品目标用户的方法 |
| `research-guide.md` | 资料调研原则与标注规范 |

## 项目结构

```
meta-product-manager/
├── SKILL.md                          # Skill 定义与行为规范
├── assets/
│   └── templates/                     # 文档模板
├── references/                        # 作业参考指南
├── LICENSE
└── README.md
```

## 使用方式

在支持 Skill 机制的 IDE（如 Cursor、Trae）中导入本 Skill 目录，通过对话触发：

- 描述你的产品想法或上传现有资料
- AI 产品经理会按照专业流程与你多轮交互，逐步澄清需求、设计方案、产出文档
- 每完成一个阶段会交付对应文档产物，由你确认后再进入下一阶段

## License

本项目基于 MIT 许可证开源 - 详情请参阅 [MIT](LICENSE) 文件。
