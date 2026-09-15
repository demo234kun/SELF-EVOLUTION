# SELF-EVOLUTION

> **自进化AI知识库 | Self-Evolving AI Paper Hub (2025–2026)**
>
> 系统收录 2025–2026 年发表的关于**AI自进化 (Self-Evolution)** 的前沿论文。
> 覆盖自我博弈、Agent自进化、代码进化、具身智能、安全理论等核心方向。
>
> 每篇论文提供：**论文元数据 + 三维度解读（论文 / 解读 / 链接）**，详见各分类目录下的 `.md` 文件。
>
> 📌 所有"作者单位"均**逐篇核验自 arXiv/出版社官方页面**（非推断）。

---

## 📊 知识库概览

| 统计项 | 数量 |
|--------|------|
| 收录论文总数 | **44** |
| 涵盖年份 | 2025 – 2026 |
| 分类方向 | 6 个 |
| 覆盖期刊/会议 | arXiv, PNAS, AI & Society 等 |
| 单篇解读结构 | 基本信息 + Q1–Q9 + 研究主题/数据类型/研究设计 |

---

## 🗂️ 分类导航

| 分类 | 目录 | 论文数 | 说明 |
|------|------|--------|------|
| [综述](#-1-综述类-surveys) | [`papers/01-surveys/`](papers/01-surveys/) | 5 | 自进化方向全景综述 |
| [自我博弈](#-2-自我博弈-self-play) | [`papers/02-self-play/`](papers/02-self-play/) | 13 | Self-Play / 自我对弈训练 |
| [Agent自进化](#-3-agent自进化-agents) | [`papers/03-agents/`](papers/03-agents/) | 14 | Agent持续学习与自优化 |
| [代码进化](#-4-代码进化-code-evolution) | [`papers/04-code-evolution/`](papers/04-code-evolution/) | 6 | 代码/算法自我改进 |
| [具身多模态](#-5-具身多模态-embodied--multimodal) | [`papers/05-embodied-multimodal/`](papers/05-embodied-multimodal/) | 2 | 具身智能自进化 |
| [安全与理论](#-6-安全与理论-safety--theory) | [`papers/06-safety-theory/`](papers/06-safety-theory/) | 4 | 自进化安全风险与奇点讨论 |

---

## 🔥 高引用 Top-10

| # | 论文 | 年份 | 引用 | 方向 |
|---|------|------|------|------|
| 1 | [ACE: Agentic Context Engineering](papers/03-agents/ACE.md) | 2025 | 293 | Agent上下文自优化 |
| 2 | [Darwin Gödel Machine](papers/04-code-evolution/Darwin-Godel-Machine.md) | 2025 | 209 | 自我改进Agent |
| 3 | [R-Zero: Self-Evolving Reasoning from Zero Data](papers/02-self-play/R-Zero.md) | 2025 | 188 | 自我博弈推理 |
| 4 | [A Comprehensive Survey of Self-Evolving AI Agents](papers/01-surveys/Comprehensive-Survey-Fang.md) | 2025 | 181 | 综述 |
| 5 | [Advances and Challenges in Foundation Agents](papers/06-safety-theory/Foundation-Agents.md) | 2025 | 158 | 基础Agent架构 |
| 6 | [A Survey of Self-Evolving Agents (Gao et al.)](papers/01-surveys/Survey-Self-Evolving-Agents-Gao.md) | 2025 | 149 | 综述 |
| 7 | [EvolveR: Self-Evolving LLM Agents](papers/03-agents/EvolveR.md) | 2025 | 116 | 经验驱动Agent进化 |
| 8 | [Agent0: Self-Evolving from Zero Data](papers/03-agents/Agent0.md) | 2025 | 62 | 从零数据进化 |
| 9 | [AgentEvolver](papers/03-agents/AgentEvolver.md) | 2025 | 62 | 自进化Agent系统 |
| 10 | [Multi-Agent Evolve (MAE)](papers/02-self-play/Multi-Agent-Evolve.md) | 2025 | 50 | 多Agent共进化 |

---

## 📚 分类论文目录

---

### 📖 1. 综述类 (Surveys)

> 系统梳理自进化AI的定义、框架、机制与未来方向。

| # | 论文 | 作者单位 | 来源 | 时间 | 关键词 | 核心研究问题 | 梗概 | 领域 | 链接 | MD解读 |
|---|------|----------|------|------|--------|-------------|------|------|------|--------|
| 1 | [A Survey of Self-Evolving Agents: On Path to ASI](papers/01-surveys/Survey-Self-Evolving-Agents-Gao.md) | 卡内基梅隆大学（领衔）、清华、上交、普林斯顿、港中文等16机构 | arXiv 2507.21046 | 2025 | Self-evolving agent, LLM, 持续学习 | 如何系统定义和分类自进化Agent的机制？ | 首篇系统综述，围绕 **what/when/how** 三维度组织自进化Agent：进化对象（模型/记忆/工具/架构）、进化时机（测试时内/测试时外）、进化算法（标量奖励/文本反馈/单/多Agent）。分析了评测指标、应用领域（代码/教育/医疗）及安全挑战。149引用。 | Agent架构 / 持续学习 | [arXiv](https://arxiv.org/abs/2507.21046) | [详解](papers/01-surveys/Survey-Self-Evolving-Agents-Gao.md) |
| 2 | [A Comprehensive Survey of Self-Evolving AI Agents](papers/01-surveys/Comprehensive-Survey-Fang.md) | 格拉斯哥大学（领衔）、谢菲尔德、剑桥、UCL、NUS、莱顿等8机构 | arXiv 2508.07407 | 2025 | Self-evolving agent, Foundation model, Lifelong learning | 如何将基础模型与终身Agent系统桥接？ | 统一抽象反馈循环框架：System Inputs → Agent System → Environment → Optimizers。按优化目标分类进化技术，覆盖生物医学/编程/金融等垂直领域，专设评测、安全与伦理章节。181引用。 | Agent系统 / 终身学习 | [arXiv](https://arxiv.org/abs/2508.07407) | [详解](papers/01-surveys/Comprehensive-Survey-Fang.md) |
| 3 | [Recursive Self-Improvement in AI](papers/01-surveys/Recursive-Self-Improvement-Chen.md) | 伊利诺伊理工学院（IIT）、DeepGrounding | arXiv 2607.07663 | 2026 | RSI, Self-refine, Self-reward, 模型坍塌 | 不同层次的自改进（行为/策略/评估器/研究过程）边界在哪里？ | 调查1250篇arXiv论文（2024-2026），沿两轴分类：改进对象×闭环程度。提出**验证层级**（形式化验证→内在自评估），发现自改进强度与验证信号强度正相关，揭示了自我确认循环、模型坍塌等失败模式。10引用。 | 递归自改进 / 治理 | [arXiv](https://arxiv.org/abs/2607.07663) | [详解](papers/01-surveys/Recursive-Self-Improvement-Chen.md) |
| 4 | [Self-Evolving Embodied AI](papers/01-surveys/Self-Evolving-Embodied-AI-Fang.md) | 清华大学（北京信息科学与技术国家研究中心） | arXiv 2602.04411 | 2026 | Embodied AI, 自进化, 具身智能 | 如何让具身Agent在真实开放环境中持续自适应？ | 首篇定义并系统综述**自进化具身AI**新范式：记忆自更新、任务自切换、环境自预测、具身自适应、模型自进化。对比现有方法在in-the-wild场景的局限，提出通向通用人工智能的新视角。 | 具身智能 / 自进化框架 | [arXiv](https://arxiv.org/abs/2602.04411) | [详解](papers/01-surveys/Self-Evolving-Embodied-AI-Fang.md) |
| 5 | [Beyond Individual Intelligence: LLM Multi-Agent Self-Evolution](papers/01-surveys/Beyond-Individual-Qi.md) | 西安交通大学 MOE KLINNS Lab | arXiv 2605.14892 | 2026 | Multi-agent, Failure attribution, 自进化 | 多Agent系统中的错误传播如何转化为结构性自我改进？ | 提出**LIFE演进框架**：Lay（能力基础）→ Integrate（协作）→ Find（故障归因）→ Evolve（自主改进）。揭示各阶段间的因果依赖关系，提出闭环多Agent系统的跨阶段研究议程。 | 多Agent系统 / 故障归因 | [arXiv](https://arxiv.org/abs/2605.14892) | [详解](papers/01-surveys/Beyond-Individual-Qi.md) |

---

### 🎮 2. 自我博弈 (Self-Play)

> 通过自我对弈/竞争实现无需人工数据的自进化训练。

| # | 论文 | 作者单位 | 来源 | 时间 | 关键词 | 核心研究问题 | 梗概 | 领域 | 链接 | MD解读 |
|---|------|----------|------|------|--------|-------------|------|------|------|--------|
| 1 | [R-Zero: Self-Evolving Reasoning LLM from Zero Data](papers/02-self-play/R-Zero.md) | 腾讯AI Lab（西雅图）、圣路易斯华盛顿大学、马里兰大学等 | arXiv 2508.05004 | 2025 | Self-play, Zero-data, Reasoning, Challenger-Solver | 能否完全从零数据出发实现LLM推理能力自进化？ | 从单个基座模型初始化Challenger和Solver两个独立模型，通过自对弈共进化：Challenger被奖励生成接近Solver能力边界的任务，Solver被奖励解决越来越难的问题。无需预设任务和标签。Qwen3-4B-Base数学推理+6.49，通用推理+7.54。**188引用，该领域核心奠基工作。** | 推理 / 自我博弈 | [arXiv](https://arxiv.org/abs/2508.05004) | [详解](papers/02-self-play/R-Zero.md) |
| 2 | [R-Few: Guided Self-Evolving LLMs with Minimal Human Supervision](papers/02-self-play/R-Few.md) | 腾讯AI Lab（西雅图）、圣路易斯华盛顿大学 | arXiv 2512.02472 | 2025 | Guided self-play, Curriculum learning, 低人工监督 | 无引导的自进化系统为何会退化？如何用最少人工监督稳定进化？ | 提出**R-Few**框架：Challenger采样少量人工标注数据引导合成问题生成，Solver在混合人工/合成数据上按在线难度课程训练。解决了概念漂移、多样性坍塌、误进化等问题。Qwen3-8B数学+3.0超过R-Zero。31引用。 | 推理 / 课程学习 | [arXiv](https://arxiv.org/abs/2512.02472) | [详解](papers/02-self-play/R-Few.md) |
| 3 | [G-Zero: Self-Play for Open-Ended Generation from Zero Data](papers/02-self-play/G-Zero.md) | 圣路易斯华盛顿大学、弗吉尼亚大学、马里兰大学、UNC | arXiv 2605.09959 | 2026 | Verifier-free, Open-ended, Hint-δ intrinsic reward | 自我博弈如何扩展到无法验证的开放生成任务？ | 提出**Hint-δ**内在奖励：量化Generator无辅助响应与条件于自生成提示的响应之间的预测偏移。Proposer通过GRPO训练瞄准Generator盲点，Generator通过DPO内化改进。完全绕过外部judge。7引用。 | 开放生成 / 内在奖励 | [arXiv](https://arxiv.org/abs/2605.09959) | [详解](papers/02-self-play/G-Zero.md) |
| 4 | [Multi-Agent Evolve (MAE)](papers/02-self-play/Multi-Agent-Evolve.md) | 伊利诺伊大学厄巴纳-香槟分校、北京大学、NVIDIA | arXiv 2510.23595 | 2025 | Multi-agent, Self-play, Proposer-Solver-Judge | 如何不依赖环境反馈实现LLM一般推理能力的自进化？ | 提出**三元组交互框架**：Proposer生成问题、Solver解题、Judge评估，三者从同一LLM实例化并共进化。通过RL优化行为。Qwen2.5-3B-Instruct平均提升4.54%。50引用。 | 推理 / 多Agent共进化 | [arXiv](https://arxiv.org/abs/2510.23595) | [详解](papers/02-self-play/Multi-Agent-Evolve.md) |
| 5 | [Tool-R0: Self-Evolving LLM Agents for Tool-Learning from Zero Data](papers/02-self-play/Tool-R0.md) | 伊利诺伊大学厄巴纳-香槟分校、苏黎世联邦理工学院 | arXiv 2602.21320 | 2026 | Tool-learning, Self-play RL, Zero-data | 如何从零数据训练通用工具调用Agent？ | Generator和Solver从同一基座模型初始化共进化：Generator提出挑战性任务，Solver学习用真实工具调用解决。无预存任务或数据集。相对基座模型提升92.5%，超越全监督基线。23引用。 | 工具学习 / 自我博弈 | [arXiv](https://arxiv.org/abs/2602.21320) | [详解](papers/02-self-play/Tool-R0.md) |
| 6 | [SAGE: Multi-Agent Self-Evolution for LLM Reasoning](papers/02-self-play/SAGE.md) | 深圳大学、人工智能与数字经济广东省实验室、卡尔顿大学 | arXiv 2603.15255 | 2026 | Multi-agent, Curriculum drift, Planning | 自我博弈如何在多步推理中保持稳定性和质量控制？ | 四Agent闭环框架：Challenger（出题）、Planner（计划）、Solver（解题）、Critic（评分过滤）。Critic防止课程漂移。Qwen-2.5-7B在LiveCodeBench+8.9%，OlympiadBench+10.7%。5引用。 | 推理 / 课程质量控制 | [arXiv](https://arxiv.org/abs/2603.15255) | [详解](papers/02-self-play/SAGE.md) |
| 7 | [Language Self-Play (LSP)](papers/02-self-play/Language-Self-Play.md) | Meta Superintelligence Labs、加州大学伯克利分校 | arXiv 2509.07414 | 2025 | Self-play, Game theory, Data-free training | 能否通过博弈论框架实现无额外数据的LLM自进化？ | 将LLM能力映射为博弈中的策略，通过自我对弈（Language Self-Play）从预训练模型自身改进。Llama-3.2-3B-Instruct在指令跟随、数学、代码基准上均提升。37引用。 | 博弈论 / 数据无关训练 | [arXiv](https://arxiv.org/abs/2509.07414) | [详解](papers/02-self-play/Language-Self-Play.md) |
| 8 | [Self-RedTeam: Online Self-Play for Safer Language Models](papers/02-self-play/Self-RedTeam.md) | 华盛顿大学、斯坦福大学 | arXiv 2506.07468 | 2025 | Safety alignment, Self-play MARL, Nash equilibrium | 如何用在线自我博弈实现LLM安全对齐的持续自我改进？ | 首个完全在线自我博弈多Agent RL算法：单一策略同时扮演攻击者和防御者，奖励模型裁判结果。理论上若收敛到纳什均衡，防御者对任意对抗输入产生安全响应。跨5个模型家族，安全提升高达95%。35引用。 | 安全对齐 / 自我博弈 | [arXiv](https://arxiv.org/abs/2506.07468) | [详解](papers/02-self-play/Self-RedTeam.md) |
| 9 | [SPELL: Self-Play RL for Long-Context LLMs](papers/02-self-play/SPELL.md) | 中山大学、阿里巴巴通义实验室、深圳循环区研究院 | arXiv 2509.23863 | 2025 | Long-context, Self-play, Curriculum | 如何在缺乏人工标注的情况下提升LLM长文本推理能力？ | 三角色自我博弈框架：Questioner（生成问题）、Responder（答题）、Verifier（评估语义等价性）。自动课程逐步增加文档长度，奖励函数自适应问题难度。Qwen3-30B平均提升7.6分。27引用。 | 长文本 / 自我博弈训练 | [arXiv](https://arxiv.org/abs/2509.23863) | [详解](papers/02-self-play/SPELL.md) |
| 10 | [Active-Zero: Active Exploration for VLM Self-Evolution](papers/02-self-play/Active-Zero.md) | 中科院自动化所、中国科学院大学、NUS、清华、武汉AI研究院 | arXiv 2602.11241 | 2026 | Vision-language, Active exploration, Self-play | VLM自我博弈如何突破对静态图像集的依赖？ | 从被动交互转向**主动视觉环境探索**：Searcher从开放世界检索图像、Questioner合成校准推理任务、Solver通过准确性奖励精炼。自脚手架自动课程。Qwen2.5-VL-7B推理任务5.7%提升。4引用。 | 视觉语言 / 主动探索 | [arXiv](https://arxiv.org/abs/2602.11241) | [详解](papers/02-self-play/Active-Zero.md) |
| 11 | [Self-Play Only Evolves When Data Ensures Learnable Information Gain](papers/02-self-play/Self-Play-Information-Gain.md) | 伦敦国王学院、艾伦·图灵研究所 | arXiv 2603.02218 | 2026 | Information gain, Sustainable evolution, Self-play theory | 自我博弈为何经常停滞？可持续自进化需要什么条件？ | 揭示可持续自进化需要**可学习信息增益跨迭代递增**。识别三元角色（Proposer/Solver/Verifier）和三个系统设计：非对称共进化、容量增长、主动信息寻求。提供了从脆弱自博弈到可持续自进化的可量化系统路径。14引用。 | 自进化理论 / 可持续性 | [arXiv](https://arxiv.org/abs/2603.02218) | [详解](papers/02-self-play/Self-Play-Information-Gain.md) |
| 12 | [Self-Consolidation for Self-Evolving Agents](papers/02-self-play/Self-Consolidation.md) | 中国科学院大学 Terminus AI Lab、中科院香港智能机器人中心、南京理工 | arXiv 2602.01966 | 2026 | Self-consolidation, Contrastive reflection, Parameter internalization | 如何解决Agent长期进化中的噪声累积和检索效率问题？ | 引入对比反思策略总结错误模式，提出**自巩固机制**：将非参数化文本经验蒸馏为紧凑可学习参数，直接内化到隐空间。解决了检索时间增长和上下文窗口耗尽问题。4引用。 | Agent记忆 / 经验蒸馏 | [arXiv](https://arxiv.org/abs/2602.01966) | [详解](papers/02-self-play/Self-Consolidation.md) |
| 13 | [MARS: Meta-cognitive Reflection for Efficient Self-Improvement](papers/02-self-play/MARS.md) | 南洋理工大学、新加坡科技研究局（A*STAR）、长安大学、南开大学 | arXiv 2601.11974 | 2026 | Metacognitive reflection, Single-cycle, Low-overhead | 如何在单次递归周期内实现高效自进化？ | 受教育心理学启发的**MARS框架**：在单次递归周期内结合基于原则的反思（抽象规范性规则避免错误）和过程性反思（推导成功步骤策略）。在6个基准上超越SOTA自进化系统，同时显著降低计算开销。3引用。 | 元认知 / 高效自进化 | [arXiv](https://arxiv.org/abs/2601.11974) | [详解](papers/02-self-play/MARS.md) |

---

### 🤖 3. Agent自进化 (Agents)

> 让部署后的Agent通过交互数据和环境反馈持续自我优化。

| # | 论文 | 作者单位 | 来源 | 时间 | 关键词 | 核心研究问题 | 梗概 | 领域 | 链接 | MD解读 |
|---|------|----------|------|------|--------|-------------|------|------|------|--------|
| 1 | [ACE: Agentic Context Engineering](papers/03-agents/ACE.md) | SambaNova Systems、加州大学伯克利分校 | arXiv 2510.04618 | 2025 | Context engineering, Self-improvement, Modular | LLM应用如何通过上下文适应而非权重更新实现自改进？ | 提出**ACE框架**：将上下文视为持续演进的playbook，通过生成→反思→策划的模块化过程积累、精炼和组织策略。防止简短偏见和上下文坍塌。Agent基准+10.6%，金融+8.6%。在AppWorld排行榜上匹配顶尖生产Agent。**293引用，该领域最高引论文。** | 上下文工程 / 自适应 | [arXiv](https://arxiv.org/abs/2510.04618) | [详解](papers/03-agents/ACE.md) |
| 2 | [EvolveR: Self-Evolving LLM Agents through Experience-Driven Lifecycle](papers/03-agents/EvolveR.md) | 浙江大学、上海人工智能实验室、复旦、上交、中科大等8机构 | arXiv 2510.16079 | 2025 | Experience lifecycle, Self-distillation, Policy reinforcement | Agent如何从自身行为后果中系统性学习？ | 闭环经验生命周期：(1) 离线自蒸馏——交互轨迹合成结构化可复用策略原则库；(2) 在线交互——检索蒸馏原则指导决策，积累多样化行为轨迹。策略强化机制迭代更新Agent。116引用。 | 经验学习 / 策略蒸馏 | [arXiv](https://arxiv.org/abs/2510.16079) | [详解](papers/03-agents/EvolveR.md) |
| 3 | [Agent0: Unleashing Self-Evolving Agents from Zero Data](papers/03-agents/Agent0.md) | 北卡罗来纳大学教堂山分校、Salesforce Research、斯坦福大学 | arXiv 2511.16043 | 2025 | Zero-data, Multi-step co-evolution, Tool integration | 如何实现完全自主的多步共进化Agent？ | Curriculum Agent与Executor Agent共进化：前者提出越来越难的前沿任务，后者学习解决。集成外部工具增强解决能力，反过来迫使Curriculum Agent构建更复杂的工具感知任务。Qwen3-8B数学推理+18%，通用推理+24%。62引用。 | 自主进化 / 工具集成 | [arXiv](https://arxiv.org/abs/2511.16043) | [详解](papers/03-agents/Agent0.md) |
| 4 | [AgentEvolver: Towards Efficient Self-Evolving Agent System](papers/03-agents/AgentEvolver.md) | 阿里巴巴通义实验室 | arXiv 2511.10395 | 2025 | Self-questioning, Self-navigating, Self-attributing | 如何降低Agent自进化的数据构建和探索成本？ | 三机制协同：(i) **Self-questioning**——好奇心驱动的新环境任务生成；(ii) **Self-navigating**——经验复用+混合策略指导的高效探索；(iii) **Self-attributing**——基于贡献度的差异化奖励分配。62引用。 | 高效探索 / 好奇心驱动 | [arXiv](https://arxiv.org/abs/2511.10395) | [详解](papers/03-agents/AgentEvolver.md) |
| 5 | [WebEvolver: Coevolving World Model for Web Agent](papers/03-agents/WebEvolver.md) | 腾讯AI Lab | arXiv 2504.21024 | 2025 | World model, Web agent, Co-evolution | Web Agent自进化为何会在自主学习中停滞？ | 引入**协同进化World Model LLM**：作为虚拟Web服务器生成自指令训练数据持续优化策略，作为推理时的想象引擎前瞻模拟指导动作选择。Mind2Web-Live/WebVoyager/GAIA-web上性能提升10%。48引用。 | Web Agent / 世界模型 | [arXiv](https://arxiv.org/abs/2504.21024) | [详解](papers/03-agents/WebEvolver.md) |
| 6 | [Do Self-Evolving Agents Forget?](papers/03-agents/Do-Self-Evolving-Agents-Forget.md) | 伊利诺伊大学厄巴纳-香槟分校 | arXiv 2605.09315 | 2026 | Capability erosion, Lifelong learning, 持续适应 | 自进化是否会导致已有能力退化？ | 揭示**自进化下的能力侵蚀**现象：适应新任务分布会渐进退化先前获取的能力，在工作流/技能/模型/记忆四个进化通道中一致出现。提出**Capability-Preserving Evolution (CPE)**约束破坏性漂移，workflow进化中保留能力从41.8%提升到52.8%。4引用。 | 能力保持 / 遗忘 | [arXiv](https://arxiv.org/abs/2605.09315) | [详解](papers/03-agents/Do-Self-Evolving-Agents-Forget.md) |
| 7 | [RSEA: Recursive Self-Evolving Agent via Held-Out Selection](papers/03-agents/RSEA.md) | 莫纳什大学马来西亚校区 | arXiv 2606.28374 | 2026 | Held-out validation, Natural language state, Monotone-safe | 无约束的上下文自进化为何不安全？如何保证单调安全？ | 携带三层自然语言状态（策略/技能/操作手册）的Agent，通过轨迹重写所有层，**仅在disjoint held-out split上不退化时才提交**。保证单调安全：从不在任何基准上显著差于基线Agent。ALFWorld 69.3%（重试79.4%）。5引用。 | 自进化安全 / 严格门控 | [arXiv](https://arxiv.org/abs/2606.28374) | [详解](papers/03-agents/RSEA.md) |
| 8 | [PACE: Two-Timescale Self-Evolution for Small Language Model Agents](papers/03-agents/PACE.md) | 亚马逊（Amazon） | arXiv 2605.23019 | 2026 | SLM agent, Prompt evolution, Control logic | 小模型Agent能否不更新权重实现有效自进化？ | 两时间尺度框架：低风险提示精炼（固定控制逻辑下进化）与高风险控制逻辑更新（饱和后考虑），通过held-out验证接受。冻结SLM（4B-14B）上12个backbone-benchmark组合全部改进，最高+9.2%相对提升。1引用。 | 小模型 / 提示进化 | [arXiv](https://arxiv.org/abs/2605.23019) | [详解](papers/03-agents/PACE.md) |
| 9 | [APEX: Three-Layer Self-Evolution Framework for Production AI Agents](papers/03-agents/APEX.md) | Grace AI Technology | arXiv 2606.15363 | 2026 | Harness, Principles, Workflow topology | 生产Agent的自进化如何超越单维度优化？ | 三层协同进化：L1 harness故障模式修补（同Self-Harness），L2行为原则蒸馏（成功轨迹提炼），L3 Agent工作流拓扑选择（结构适应度选择）。在114条真实任务轨迹上实现APEX Health Score 0.570（基线0.300）。 | 生产Agent / 多维进化 | [arXiv](https://arxiv.org/abs/2606.15363) | [详解](papers/03-agents/APEX.md) |
| 10 | [E-SPL: Evolutionary System Prompt Learning](papers/03-agents/E-SPL.md) | 多伦多大学、西北大学、Bridgewater AIA Labs | arXiv 2602.14697 | 2026 | System prompt, Evolutionary RL, Context-weight synergy | 系统提示和模型权重能否协同进化？ | 每轮RL迭代中并行采样多系统提示下的轨迹，联合应用RL更新权重和进化更新提示。提示通过LLM自反思驱动的突变和交叉进化，选择基于跨迭代的相对性能评级。AIME→BeyondAIME泛化中成功率从38.8%提升到45.1%。3引用。 | 系统提示 / 协同进化 | [arXiv](https://arxiv.org/abs/2602.14697) | [详解](papers/03-agents/E-SPL.md) |
| 11 | [Towards AGI: A Pragmatic Approach Towards Self-Evolving Agent](papers/03-agents/Towards-AGI-Kar.md) | Rastrai | arXiv 2601.11658 | 2026 | Hierarchical evolution, Curriculum, RL, Genetic algorithm | 失败的Agent如何自动升级进化策略？ | 层级自进化多Agent框架：任务尝试 → 工具合成(Code-Gen LLM) → 进化阶段(CL/RL/GA)。CL快速恢复泛化强，RL高难度任务突出，GA行为多样性高。进化后Agent一致优于原始版本。1引用。 | 层级进化 / 多策略 | [arXiv](https://arxiv.org/abs/2601.11658) | [详解](papers/03-agents/Towards-AGI-Kar.md) |
| 12 | [Ctx2Skill: From Context to Skills for Context Learning](papers/03-agents/Ctx2Skill.md) | 伊利诺伊大学厄巴纳-香槟分校、DeepLang AI、复旦、港中文、清华 | arXiv 2604.27660 | 2026 | Skill discovery, Context learning, Multi-agent self-play | 语言模型如何从上下文中自主发现可复用技能？ | 多Agent自我博弈循环：Challenger生成探测任务和评分标准、Reasoner在进化技能集指导下解题、Judge提供二值反馈。Proposer和Generator分析失败案例合成技能更新。Cross-time Replay机制防止对抗坍塌。20引用。 | 技能发现 / 上下文学习 | [arXiv](https://arxiv.org/abs/2604.27660) | [详解](papers/03-agents/Ctx2Skill.md) |
| 13 | [HexMachina: Artifact-Centric Continual Learning for LLMs](papers/03-agents/HexMachina.md) | 加州大学圣塔芭芭拉分校 | arXiv 2506.04651 | 2025 | Continual learning, Artifact, Strategic planning | LLM Agent如何在长视野对抗环境中维持连贯策略？ | **以制品为中心的持续学习**：将环境发现（无需文档归纳适配层）与策略改进（通过代码精炼和模拟演化编译玩家）分离。在Catan实验中从零学习，54%胜率超越最强人工基线AlphaBeta。21引用。 | 持续学习 / 策略设计 | [arXiv](https://arxiv.org/abs/2506.04651) | [详解](papers/03-agents/HexMachina.md) |
| 14 | [SAGE: Socialized Evolution in Agent Ecosystems](papers/03-agents/SAGE-Socialized.md) | 清华大学、美团 | arXiv 2606.03544 | 2026 | Social evolution, Peer history, Agent ecosystem | 共享同伴经验何时比自我改进更好？ | 提出**SAGE框架**比较SocialEvo（所有Agent共享历史）vs SelfEvo（仅自身历史）。发现：群体历史不是万能放大器（最强Agent不超自我进化上限），但自我改进停滞的Agent可通过同伴经验突破。过滤后的同伴轨迹和反思摘要通常优于原始日志。1引用。 | 社会化进化 / 群体智能 | [arXiv](https://arxiv.org/abs/2606.03544) | [详解](papers/03-agents/SAGE-Socialized.md) |

---

### 💻 4. 代码进化 (Code Evolution)

> 让AI自动改进代码、算法和编程Agent自身。

| # | 论文 | 作者单位 | 来源 | 时间 | 关键词 | 核心研究问题 | 梗概 | 领域 | 链接 | MD解读 |
|---|------|----------|------|------|--------|-------------|------|------|------|--------|
| 1 | [Darwin Gödel Machine: Open-Ended Evolution of Self-Improving Agents](papers/04-code-evolution/Darwin-Godel-Machine.md) | 不列颠哥伦比亚大学（UBC）、Vector Institute、Sakana AI | arXiv 2505.22954 | 2025 | Self-improving, Open-ended, Code evolution, Godel machine | AI系统能否持续自主改进自身代码？ | 受生物进化和开放性研究启发：迭代修改自身代码，用编码基准经验验证每次变更。维护生成的coding agents档案，采样并创建新版本。开放探索形成增长的多样化高质量agent树。SWE-bench从20.0%→50.0%，Polyglot从14.2%→30.7%。**209引用，自我改进AI里程碑。** | 代码进化 / 开放性 | [arXiv](https://arxiv.org/abs/2505.22954) | [详解](papers/04-code-evolution/Darwin-Godel-Machine.md) |
| 2 | [SATLUTION: Autonomous Code Evolution Meets NP-Completeness](papers/04-code-evolution/SATLUTION.md) | NVIDIA Research、马里兰大学 | arXiv 2509.07367 | 2025 | Full-repo evolution, SAT, NP-complete, Correctness guarantee | LLM代码进化能否从内核扩展到完整仓库规模？ | 首个将LLM代码进化扩展到**完整仓库规模**（数百文件、数万行C/C++代码）的框架。以SAT（NP完全问题）为目标，在严格正确性保证和分布式运行时反馈下直接进化求解器仓库，同时自我进化进化策略。超越SAT Competition 2024/2025冠军。23引用。 | 仓库级进化 / 理论问题求解 | [arXiv](https://arxiv.org/abs/2509.07367) | [详解](papers/04-code-evolution/SATLUTION.md) |
| 3 | [MLEvolve: Self-Evolving Framework for ML Algorithm Discovery](papers/04-code-evolution/MLEvolve.md) | 上海人工智能实验室、华东师范大学 | arXiv 2606.06473 | 2026 | ML engineering, Progressive search, Retrospective memory | LLM agent如何在长期ML工程任务中持续自进化？ | 将树搜索扩展为**Progressive MCGS**：图参考边实现跨分支信息流，熵驱动进度调度从广探索转向聚焦利用。引入回顾性记忆（冷启动知识库+动态全局记忆），解耦战略规划和代码生成。MLE-Bench多维度SOTA，超越AlphaEvolve。11引用。 | ML算法发现 / 长期优化 | [arXiv](https://arxiv.org/abs/2606.06473) | [详解](papers/04-code-evolution/MLEvolve.md) |
| 4 | [MetaEvolve: Cultivating Core Meta-Skills with RL](papers/04-code-evolution/MetaEvolve.md) | 伊利诺伊大学厄巴纳-香槟分校 | arXiv 2607.21971 | 2026 | Meta-skills, Evolution-aware RL, Cross-domain transfer | 自进化框架成功的关键能力（元技能）是什么？如何显式培养？ | 假设自进化成功依赖于**元技能**（如环境反馈下的自我反思），提出MetaEvolve通过数据合成+进化感知RL+推理时进化搜索显式培养这些元技能。编程领域7个基准上分布内+10.01%，分布外+24.12%，算法优化相对提升46.9%。 | 元技能 / 跨域迁移 | [arXiv](https://arxiv.org/abs/2607.21971) | [详解](papers/04-code-evolution/MetaEvolve.md) |
| 5 | [Frontis-MA1: Training an AI4AI Model towards RSI](papers/04-code-evolution/Frontis-MA1.md) | Frontis AI（OpenRSI）、清华大学 | arXiv 2607.28568 | 2026 | AI4AI, OpenMLE, Program evolution operators | 如何构建可复现的递归自改进研究系统？ | 开放全栈RSI研究系统：OpenMLE-Gym（可验证任务环境）+ OpenMLE-RL（算子学习）+ OpenMLE-Evo（长期搜索）。Frontis-MA1(35B)围绕四个原子程序进化算子（Draft/Improve/Debug/Crossover）训练。MLE-Bench Lite上39.39%→60.61%（OpenMLE-Evo），达71.21%接近GPT-5.5。3引用。 | AI4AI / 开放系统 | [arXiv](https://arxiv.org/abs/2607.28568) | [详解](papers/04-code-evolution/Frontis-MA1.md) |
| 6 | [Seed2Scale: Self-Evolving Data Engine for Embodied AI](papers/04-code-evolution/Seed2Scale.md) | 中兴通讯（ZTE Corporation） | arXiv 2603.08260 | 2026 | Data engine, Small-large synergy, Embodied data | 具身AI数据自进化如何克服探索限制和信噪比问题？ | 异构协同："小模型采集+大模型评估+目标模型学习"。从仅4个种子演示出发，SuperTiny(VLA)作为采集器利用强归纳偏置稳健探索，预训练VLM作为验证器自主判断成功/失败和质量打分。缓解模型坍塌，迭代过程中成功率持续上升，提升131.2%。 | 具身数据 / 数据引擎 | [arXiv](https://arxiv.org/abs/2603.08260) | [详解](papers/04-code-evolution/Seed2Scale.md) |

---

### 🦾 5. 具身多模态 (Embodied & Multimodal)

> 让具身智能体和多模态模型在真实交互中自我进化。

| # | 论文 | 作者单位 | 来源 | 时间 | 关键词 | 核心研究问题 | 梗概 | 领域 | 链接 | MD解读 |
|---|------|----------|------|------|--------|-------------|------|------|------|--------|
| 1 | [SEEA-R1: Tree-Structured RL for Self-Evolving Embodied Agents](papers/05-embodied-multimodal/SEEA-R1.md) | 北京人形机器人创新中心、北京大学 | arXiv 2506.21669 | 2025 | RFT, Embodied agent, Multi-modal reward | 强化微调如何在具身领域实现自进化？ | 首个专为具身Agent设计的RFT框架。提出**Tree-GRPO**：将蒙特卡洛树搜索集成到GRPO中，将稀疏延迟奖励转化为稠密中间信号；引入**多模态生成奖励模型(MGRM)**泛化奖励估计。ALFWorld上文本85.07%/多模态46.27%超越GPT-4o。18引用。 | 具身RL / 树搜索 | [arXiv](https://arxiv.org/abs/2506.21669) | [详解](papers/05-embodied-multimodal/SEEA-R1.md) |
| 2 | [Agent0-VL: Self-Evolving Agent for Tool-Integrated Vision-Language Reasoning](papers/05-embodied-multimodal/Agent0-VL.md) | 北卡罗来纳大学教堂山分校 | arXiv 2511.19900 | 2025 | Vision-language, Tool-integrated, Self-rewarding | 视觉推理如何不依赖外部奖励实现持续自进化？ | 统一Solver（多轮工具推理）和Verifier（结构化反馈+细粒度自奖励）于单一LVLM。工具增强的验证避免评估幻觉，**自我进化推理循环**中工具验证和RL对齐推理与评估分布。零外部奖励下几何问题+12.5%。30引用。 | 视觉推理 / 工具验证 | [arXiv](https://arxiv.org/abs/2511.19900) | [详解](papers/05-embodied-multimodal/Agent0-VL.md) |

---

### ⚠️ 6. 安全与理论 (Safety & Theory)

> 自进化带来的安全风险、对齐挑战与哲学讨论。

| # | 论文 | 作者单位 | 来源 | 时间 | 关键词 | 核心研究问题 | 梗概 | 领域 | 链接 | MD解读 |
|---|------|----------|------|------|--------|-------------|------|------|------|--------|
| 1 | [Your Agent May Misevolve: Emergent Risks in Self-Evolving LLM Agents](papers/06-safety-theory/Misevolution.md) | 中国人民大学、普林斯顿大学、香港科技大学、复旦、上海AI Lab、上交 | arXiv 2509.26354 | 2025 | Misevolution, Safety, Emergent risks, Alignment | 自进化是否会产生非预期的危害性行为？ | **首次系统概念化"误进化(Misevolution)"**：沿模型/记忆/工具/工作流四个进化路径评估风险。发现误进化是普遍风险（即使在Gemini-2.5-Pro等顶级LLM上也出现），如记忆积累后的安全对齐退化、工具创建中的漏洞引入。48引用。 | 自进化安全 / 误进化 | [arXiv](https://arxiv.org/abs/2509.26354) | [详解](papers/06-safety-theory/Misevolution.md) |
| 2 | [Evolvable AI: Threats of a New Major Transition in Evolution](papers/06-safety-theory/Evolvable-AI.md) | 罗兰大学（ELTE）、HUN-REN生态研究中心、比利时皇家弗拉芒科学院 | PNAS 2026 | 2026 | Darwinian evolution, Existential risk, Major transition | AI系统可进化性将如何改变演化单位和生存风险？ | 从生物进化视角论证eAI（可进化AI）可能标志着进化单位和基质的转变——潜在的"Life 2.0"。区分"培育者"场景（人类控制适应度标准）和"生态系统"场景（选择来自开放环境，控制侵蚀）。自私复制可靠产生欺骗、寄生、操纵。提出复制门控等治理干预。8引用，**PNAS发表。** | 可进化AI / 生存风险 | [PNAS](https://doi.org/10.1073/pnas.2527700123) | [详解](papers/06-safety-theory/Evolvable-AI.md) |
| 3 | [LLMs: Assessment for Singularity](papers/06-safety-theory/LLMs-Singularity.md) | 未公开 | AI & Society 2025 | 2025 | Singularity, RSI, Intelligence explosion | 当前LLM技术能否达到技术奇点？ | 提出评估LLM达到奇点的理论框架：聚焦递归自改进(RSI)和自主代码生成。整合RLHF/DPO等技术分析如何使LLM独立增强推理和问题解决能力。映射潜在奇点模型生命周期和指数增长模型动力学。讨论伦理和安全含义。5引用。 | 奇点 / 技术评估 | [DOI](https://doi.org/10.1007/s00146-025-02271-4) | [详解](papers/06-safety-theory/LLMs-Singularity.md) |
| 4 | [Advances and Challenges in Foundation Agents](papers/06-safety-theory/Foundation-Agents.md) | 蒙特利尔大学、Mila、MetaGPT、微软亚研院、Google DeepMind、斯坦福等20机构 | arXiv 2504.01990 | 2025 | Foundation agent, Brain-inspired, Safety, Self-enhancement | 如何构建从脑启发到安全系统的统一Agent框架？ | 四部分综合框架：(1) 模块化基础Agent（认知/感知/操作模块映射到大脑功能）；(2) 自增强与自适应进化机制；(3) 多Agent系统涌现的集体智能；(4) 安全与伦理对齐。**158引用。** | 基础Agent / 脑启发 | [arXiv](https://arxiv.org/abs/2504.01990) | [详解](papers/06-safety-theory/Foundation-Agents.md) |

---

## 🧪 核心方法对比表

> 跨论文横向对比：**进化对象 / 驱动信号 / 验证类型 / 角色数 / 代表基准**。
> 「验证类型」按本库综述论文提出的**验证层级**排序：形式化/执行验证 > 奖励模型 > LLM 评判 > 内在自评估。

### 自我博弈类

| 论文 | 进化对象 | 驱动信号 | 验证类型 | 角色数 | 代表基准 |
|------|----------|----------|----------|--------|----------|
| R-Zero | 策略（权重） | 能力边界奖励 | 正确性（执行） | 2 (Challenger/Solver) | 数学 / 通用推理 |
| R-Few | 策略（权重） | 少量人工锚点 + 难度课程 | 正确性（执行） | 2 | 数学 / 通用推理 |
| G-Zero | 策略（权重） | **Hint-δ 内在奖励** | 内部分布动力学（无验证器） | 2 (Proposer/Generator) | 开放生成 |
| Multi-Agent Evolve | 策略（权重） | Judge 评估 | LLM 评判 | 3 (Proposer/Solver/Judge) | 数学 / 推理 / 常识 |
| Tool-R0 | 策略（权重） | 互补奖励 | 工具执行 | 2 (Generator/Solver) | 工具调用 |
| SAGE (Multi-Agent) | 策略（权重） | Critic 过滤 + 外部验证器 | 执行验证 | 4 (Challenger/Planner/Solver/Critic) | LiveCodeBench / OlympiadBench |
| Language Self-Play | 策略（权重） | 博弈胜负 | 博弈判定 | 2 | 指令 / 数学 / 代码 |
| Self-RedTeam | 策略（权重） | 奖励模型裁判 | 奖励模型 | 1（单策略双角色） | 14 安全基准 |
| SPELL | 策略（权重） | 语义等价验证 | LLM 验证 | 3 (Questioner/Responder/Verifier) | 6 长上下文基准 |
| Active-Zero | 策略（权重） | 准确性奖励 | 正确性验证 | 3 (Searcher/Questioner/Solver) | 12 VLM 基准 |
| Self-Play Info Gain | 理论（系统设计） | 可学习信息增益 | 信息论度量 | 3 (Proposer/Solver/Verifier) | 编码任务 |
| Self-Consolidation | 记忆 + 参数 | 对比反思 | 轨迹反馈 | — | 长期 Agent |
| MARS | 上下文（指令） | 原则反思 + 过程反思 | 任务反馈 | 1 | 6 基准 |

### Agent 自进化类

| 论文 | 进化对象 | 驱动信号 | 验证类型 | 角色数 | 代表基准 |
|------|----------|----------|----------|--------|----------|
| ACE | 上下文（playbook） | 执行反馈（无标签） | 无标签执行 | 1 | AppWorld / 金融 |
| EvolveR | 上下文（原则库）+ 策略 | 策略强化 | 任务表现 | 1 | 多跳 QA |
| Agent0 | 策略（权重） | 共生竞争 + 工具 | 工具执行 | 2 (Curriculum/Executor) | 数学 / 通用推理 |
| AgentEvolver | 策略（权重） | 自归因奖励 | 贡献度分配 | 1 | Agent 任务 |
| WebEvolver | 策略（权重） | 世界模型预测 | 环境预测 | 2 (Agent + World Model) | Mind2Web / WebVoyager / GAIA |
| Do Agents Forget? | 工作流/技能/模型/记忆 | CPE 约束 | 保留能力度量 | — | 四通道 |
| RSEA | 上下文（三层状态） | held-out 门控 | held-out 验证 | 1 | ALFWorld / GAIA / τ-bench / WebShop |
| PACE | 提示 + 控制逻辑 | held-out 验证 | held-out 验证 | 1 | 4 基准 + τ-bench |
| APEX | harness + 原则 + 拓扑 | 结构适应度 | 适应度评分 | 1 | 生产 Agent（114 轨迹） |
| E-SPL | 提示 + 权重 | RL + 进化算子 | 相对性能评级 | 1 | AIME → BeyondAIME |
| Towards AGI (Kar) | 多组件 | CL / RL / GA | 任务执行 | 4 | TaskCraft |
| Ctx2Skill | 技能集 | Judge 二值反馈 | LLM 评判 | 5 | CL-bench |
| HexMachina | 代码制品 | 模拟胜率 | 游戏胜负 | 2 | Catan |
| SAGE (Socialized) | 上下文 | 同伴历史 | 性能对比 | — | 3 竞技场 |

### 代码进化 / 具身类

| 论文 | 进化对象 | 驱动信号 | 验证类型 | 角色数 | 代表基准 |
|------|----------|----------|----------|--------|----------|
| Darwin Gödel Machine | 代码（自身） | 基准验证 | 编码基准（执行） | 1 | SWE-bench / Polyglot |
| SATLUTION | 仓库代码（数万行） | 正确性 + 运行时 | 形式 + 运行时 | 1 | SAT Competition |
| MLEvolve | 代码 + 搜索策略 | 回顾性记忆 + 图搜索 | ML 指标 | — | MLE-Bench |
| MetaEvolve | 权重（元技能） | 可验证奖励 | 测试用例（执行） | 1 | 7 编码基准 |
| Frontis-MA1 | 权重（四算子） | 执行反馈 | 执行验证 | 1 | MLE-Bench Lite |
| Seed2Scale | 数据 | VLM 验证 | VLM 质量评分 | 3 (采集/验证/学习) | 具身数据 |
| SEEA-R1 | 策略（权重） | MGRM 生成奖励 | 多模态奖励模型 | 1 | ALFWorld |
| Agent0-VL | 策略（权重） | 工具锚定自奖励 | 工具验证 | 2 (Solver/Verifier) | 几何 / 视觉科学 |

**规律**：验证信号越强（形式/执行），自进化越稳定、提升越显著（DGM、SATLUTION、MetaEvolve）；信号越弱（LLM 评判/内在自评估），越需要额外机制防坍塌（held-out 门控、Critic 过滤、Cross-time Replay）。

---

## 📈 趋势洞察

### 核心技术演进路线

```
2025 Q1-Q2: Self-Play 范式确立
  └─ R-Zero, Language Self-Play, Self-RedTeam
      → 从零数据自我博弈训练的基础框架

2025 Q3-Q4: Agent 自进化爆发
  └─ ACE, EvolveR, Agent0, AgentEvolver
      → 经验驱动、工具集成、多维进化的Agent系统

2026 Q1-Q2: 理论深化 + 安全觉醒
  └─ Self-Play Information Gain, Misevolution, CPE
      → 可持续性条件分析 + 误进化风险系统化

2026 Q3+: 规模化 + 代码进化
  └─ MetaEvolve, Frontis-MA1, MLEvolve
      → AI4AI系统走向实际部署，元技能跨域迁移
```

### 关键研究主题

| 主题 | 代表论文 | 核心贡献 |
|------|----------|----------|
| 零数据自进化 | R-Zero, Agent0, Tool-R0 | 完全不依赖人工数据的训练范式 |
| 可持续自进化条件 | Self-Play Info Gain, Do Agents Forget? | 信息增益递增 + 能力保持约束 |
| 误进化与安全 | Misevolution, Self-RedTeam, Evolvable AI | 四路径风险分析 + 对抗共进化 |
| 上下文自优化 | ACE, RSEA, PACE | 无需权重更新的低成本自适应 |
| 代码/算法进化 | DGM, SATLUTION, MLEvolve | 从内核到仓库级的代码自改进 |
| 多Agent共进化 | MAE, SAGE, G-Zero | 多角色协同进化系统 |

---

## 🔗 Quick Links

| 资源 | 链接 |
|------|------|
| arXiv Self-Evolution Papers | [arxiv.org/search/?query=self-evolving+agent](https://arxiv.org/search/?query=self-evolving+agent&start=0) |
| Self-Evolving Agents Survey (Gao) | [arxiv.org/abs/2507.21046](https://arxiv.org/abs/2507.21046) |
| Self-Evolving Agents Survey (Fang) | [arxiv.org/abs/2508.07407](https://arxiv.org/abs/2508.07407) |
| R-Zero | [arxiv.org/abs/2508.05004](https://arxiv.org/abs/2508.05004) |
| Darwin Gödel Machine | [arxiv.org/abs/2505.22954](https://arxiv.org/abs/2505.22954) |
| ACE | [arxiv.org/abs/2510.04618](https://arxiv.org/abs/2510.04618) |

---

## 📝 使用说明

- **表格导航**：首页表格按6大方向组织，提供论文、解读、链接三个维度
- **详细解读**：点击 `MD解读` 列链接，进入单篇论文的完整Q&A解读
- **解读格式**：每篇论文解读包含 9 个核心问题（Q1问题来源 / Q2相关研究 / Q3解决方案 / Q4数据细节 / Q5实验 / Q6创新点 / Q7不足 / Q8技术范式 / Q9研究话题）+ 研究主题/数据类型/研究设计
- **BibTeX 引用**：每篇解读文件末尾附有可直接复制的 `bibtex` 引用块（含完整作者列表与 arXiv/DOI 号）
- **关键词索引**：可通过搜索关键词快速定位相关论文

---

*Last updated: 2026-09-16 | Maintained by [demo234kun](https://github.com/demo234kun)*

*This knowledge base is curated for research purposes. All paper links point to original sources. 作者单位已逐篇核验。*
