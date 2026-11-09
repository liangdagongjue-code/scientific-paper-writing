# Scientific Paper Writing

一套可跨研究主题复用的学术论文写作 Skill，涵盖论文组织、中文起草、英文翻译、修改核对，以及图表与补充材料的表达原则。

核心思路是建立完整的研究论证链：

**研究问题 → 已有进展 → 具体缺口 → 关键思路 → 方法与机制 → 支撑证据 → 研究意义。**

## 阅读入口

| 文件 | 用途 |
| --- | --- |
| [SKILL.md](SKILL.md) | AI 助手的执行入口、适用范围和工作原则 |
| [中文通用写作指南](references/中文通用写作指南.md) | 作者直接阅读的完整中文指南 |
| [Argument and Section Guide](references/argument-and-sections.md) | 论证主线、各节职责和不同论文类型的组织方法 |
| [Language, Evidence, and Revision Guide](references/language-and-evidence.md) | 英文表达、证据边界、引用、翻译和修改核对 |
| [Agent interface](agents/openai.yaml) | 助手界面的名称、描述和默认提示 |

## 写作方式

- 先明确研究问题、贡献与对应证据，再安排章节。
- 方法解释“为什么这样设计、怎样操作、产生什么作用”。
- 结果围绕研究问题组织，用代表性数据支撑发现，让表格承载完整数值。
- 在证据支持时明确突出方法优势，同时准确保留适用条件与比较范围。
- 大段新写默认先审阅中文逻辑，再完整翻译成英文；已认可内容不因翻译而擅自删减。
- 根据实证、理论、综述或定性研究调整结构，不固定要求六节，也不绑定某篇论文或某个期刊。

## 图表与画图规则

完整规则位于[中文指南第十节](references/中文通用写作指南.md#十图表与补充材料)及[英文图表章节](references/argument-and-sections.md#10-figures-and-supplementary-material)。

- 每张图明确承担一个研究表达任务。
- 框架图突出核心机制与真实依赖关系，按信息流组织箭头。
- 使用少量、语义一致且对比充分的颜色，按最终排版尺寸检查文字可读性。
- 图注保留理解科学内容必需的信息，避免逐一解释显而易见的图形。
- 图与表围绕同一研究问题时，可以组合呈现并在正文中自然引出。
- 图表、正文与补充材料在指标、符号、数字和结论上保持一致。

这些规则目前是论文 Skill 的组成部分，未单独注册为绘图 Skill。

## 使用示例

将本仓库完整保存为 `scientific-paper-writing` 文件夹，交给支持 `SKILL.md` 的助手读取入口文件及其引用资料；也可以直接阅读中文指南使用。

> 按照 scientific-paper-writing skill，先梳理本文的研究问题、创新点和证据，再起草中文引言。

> 按照这套 skill，将已经认可的中文方法章节完整翻译成英文，保留公式、数值、假设和引用。

> 检查实验章节是否围绕研究问题展开，比较范围是否准确，图表能否直接支撑主要结论。

## English overview

A reusable academic-writing skill for planning, drafting, translating, revising, and reviewing scholarly papers across research topics. It organizes writing around a focused research question, a supported contribution, clear mechanisms, and appropriate evidence.

The package includes an English skill entry point, two operational guides, a complete Chinese reading guide, and agent interface metadata. Figure and table guidance is included within the writing skill. Adapt the structure to the paper's genre and retain the actual scope of its evidence.
