# 黄若烯 · Ruoxi Huang

> 金融科技硕士在读 · 量化因子研究 / 机器学习 / 组合系统
>
> Master's candidate in Financial Technology · quantitative factor research, machine learning and portfolio systems

[个人主页 / Portfolio](https://ruoxi-huang.github.io/Ruoxi-Huang/) ·
[中文](#中文) · [English](#english) ·
[Email](mailto:ruoxi.huang.alex@gmail.com)

---

## 中文

香港大学金融科技硕士（MFFinTech）在读，北京航空航天大学信息管理与信息系统管理学学士。关注把 Alpha 研究做成可复现的组合系统：数据接入、因子工程、点时建模、风险分解、约束优化与日频回测使用同一套口径。

目前在做量化因子研究实习，工作重点包括多因子 Alpha、机器学习增量模型、类 Barra 风险模型与带跟踪误差约束的组合构建。

### 研究与工程方向

- 多因子 Alpha：截面 IC / RankIC、因子正交化、点时股票池与防泄漏设计
- 机器学习增量：XGBoost 残差排序、GRU 时序信号、基于滞后 OOF 证据的专家路由
- 风险模型：市值加权 WLS、EWMA / Newey-West、Eigenfactor、VRA、贝叶斯收缩
- 组合优化：跟踪误差约束、连续 SOCP 与稀疏持仓 MIQCP
- 因子基础设施：分钟级三维张量、GP / RL 因子挖掘、只读数据库批量回测

### 项目

| 项目 | 做什么 | 关键结果 |
| --- | --- | --- |
| [中证 800 指数增强研究平台](https://ruoxi-huang.github.io/Ruoxi-Huang/projects/p1-platform/) | 数据 → 因子 → Alpha → 风险 → 优化 → 回测的端到端研究系统 | 2016–2026 长区间净收益 306.51%，IR 1.150，实现 TE 6.60% |
| [动态多专家 Alpha 融合与路由](https://ruoxi-huang.github.io/Ruoxi-Huang/projects/p2-dynamic-blend/) | Linear IC 锚 + XGBoost 残差 + GRU 时序，由因果路由器分配权重 | 冻结留出 52 期：IR 1.010 → 1.168，净主动累计 30.41% → 35.45% |
| [类 Barra CNE6 风险模型](https://ruoxi-huang.github.io/Ruoxi-Huang/projects/p3-barra-cne6/) | 因子暴露生产与因子 / 个股协方差估计 | 125 期 TE 校准：实现 / 预测 0.436，预测与实现相关 0.269 |
| [AlphaCube 三维张量因子挖掘](https://ruoxi-huang.github.io/Ruoxi-Huang/projects/p4-alphacube/) | (股票, 交易日, 分钟) 立方体上的 GP 与四个 RL miner | 242 个可搜索算子；100 万纯多头测试段超额夏普 +2.28 |
| [只读数据库因子回测编排层](https://ruoxi-huang.github.io/Ruoxi-Huang/projects/p5-database-backtest/) | 只读 PostgreSQL / MySQL 上的因子发现、审计与批量回测 | 自动发现、映射、审计、断点续跑；复用原始回测框架 |

所有业绩数字均为历史回测 / 研究结果，不是实盘业绩，对股票池、风险预算、调仓频率与交易成本假设敏感。

### 教育

| 时间 | 学校 | 专业 | GPA |
| --- | --- | --- | --- |
| 2025.09 – 至今 | 香港大学 | 金融科技硕士（MFFinTech） | 3.99 / 4.0 |
| 2021.09 – 2025.07 | 北京航空航天大学 | 信息管理与信息系统 · 管理学学士 | 3.72 / 4.0 |

### 实习

- 量化研究实习 · 公募基金 · 2026.06 – 至今
- 数据自动化实习 · 券商财富管理 · 2024.07 – 2024.09
- 数据自动化实习 · 财险业务发展 · 2024.01 – 2024.04

### 技术栈

`Python` · `pandas` · `NumPy` · `PyTorch` · `XGBoost` · `Scikit-Learn` · `SQL` · `PostgreSQL` · `MySQL` · `Clarabel` · `Gurobi` · `Selenium`

多因子挖掘 · 时序分析 · 机器学习 · 组合优化 · 可复现研究工程

### 联系方式

- Email: [ruoxi.huang.alex@gmail.com](mailto:ruoxi.huang.alex@gmail.com)
- Email: [ruoxi_huang_alex@163.com](mailto:ruoxi_huang_alex@163.com)
- Portfolio: [ruoxi-huang.github.io/Ruoxi-Huang](https://ruoxi-huang.github.io/Ruoxi-Huang/)

---

## English

I am a Master of Finance in Financial Technology candidate at The University of Hong Kong, with a bachelor's degree in Information Management and Information Systems from Beihang University. My work focuses on turning alpha research into reproducible portfolio systems, where data ingestion, factor engineering, point-in-time modelling, risk decomposition, constrained optimisation and daily backtesting share one consistent set of conventions.

I am currently a quantitative research intern, working on multi-factor alpha, incremental machine-learning models, Barra-style risk models and tracking-error-constrained portfolio construction.

### Research and engineering

- Multi-factor alpha: cross-sectional IC / RankIC, factor orthogonalisation, point-in-time universes and leakage controls
- Machine-learning increments: XGBoost residual ranking, GRU temporal signals and expert routing from lagged out-of-fold evidence
- Risk models: cap-weighted WLS, EWMA / Newey-West, Eigenfactor adjustment, VRA and Bayesian shrinkage
- Portfolio construction: tracking-error constraints, continuous SOCP and sparse-holding MIQCP
- Factor infrastructure: minute-level 3-D tensors, GP / RL factor mining and read-only database batch backtesting

### Selected projects

| Project | What it does | Selected result |
| --- | --- | --- |
| [CSI 800 enhanced-index platform](https://ruoxi-huang.github.io/Ruoxi-Huang/projects/p1-platform/) | End-to-end research stack: data → factors → alpha → risk → optimisation → backtest | 2016–2026 net return 306.51%, IR 1.150, realised TE 6.60% |
| [Dynamic multi-expert alpha blending](https://ruoxi-huang.github.io/Ruoxi-Huang/projects/p2-dynamic-blend/) | Linear IC anchor, XGBoost residual and GRU temporal signal, weighted by a causal router | 52-period holdout: IR 1.010 → 1.168; net active return 30.41% → 35.45% |
| [Barra CNE6-style risk model](https://ruoxi-huang.github.io/Ruoxi-Huang/projects/p3-barra-cne6/) | Factor-exposure production plus factor / stock covariance estimation | 125 TE periods: realised/predicted 0.436; prediction-realisation correlation 0.269 |
| [AlphaCube tensor factor mining](https://ruoxi-huang.github.io/Ruoxi-Huang/projects/p4-alphacube/) | GP and four RL miners on a (stock, day, minute) cube | 242 searchable operators; CNY 1m long-only test-segment excess Sharpe +2.28 |
| [Read-only database factor runner](https://ruoxi-huang.github.io/Ruoxi-Huang/projects/p5-database-backtest/) | Factor discovery, audit and batch backtesting on read-only PostgreSQL / MySQL | Automatic discovery, mapping, audit and resumable batches; original framework unchanged |

All performance figures are historical backtest or research results, not live trading performance, and are sensitive to the universe, risk budget, rebalance schedule and cost assumptions.

### Education

| Period | Institution | Programme | GPA |
| --- | --- | --- | --- |
| Sep 2025 – Present | The University of Hong Kong | Master of Finance in Financial Technology | 3.99 / 4.0 |
| Sep 2021 – Jul 2025 | Beihang University | B.Mgt. in Information Management and Information Systems | 3.72 / 4.0 |

### Experience

- Quantitative research intern · public fund · Jun 2026 – Present
- Data automation intern · brokerage wealth management · Jul 2024 – Sep 2024
- Data automation intern · P&C insurance, business development · Jan 2024 – Apr 2024

### Toolkit

`Python` · `pandas` · `NumPy` · `PyTorch` · `XGBoost` · `Scikit-Learn` · `SQL` · `PostgreSQL` · `MySQL` · `Clarabel` · `Gurobi` · `Selenium`

Multi-factor mining · time-series analysis · machine learning · portfolio optimisation · reproducible research engineering

### Contact

- Email: [ruoxi.huang.alex@gmail.com](mailto:ruoxi.huang.alex@gmail.com)
- Email: [ruoxi_huang_alex@163.com](mailto:ruoxi_huang_alex@163.com)
- Portfolio: [ruoxi-huang.github.io/Ruoxi-Huang](https://ruoxi-huang.github.io/Ruoxi-Huang/)

---

<sub>Site source and deployment notes: [DEVELOPMENT.md](DEVELOPMENT.md)</sub>
