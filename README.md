### Brian McMahon

Building **[Nous Ergon](https://nousergon.ai)** — a harness for running rigorous AI/ML experiments in finance.

It takes an experiment — a hypothesis with a pre-committed acceptance bar — and runs it through a full production pipeline: market data, multi-agent research (LangGraph + Claude), a stacked ML prediction ensemble, and risk-gated execution. Then it grades the result. The pipeline is the substrate; the evaluation layer is the point — decision quality is measured *before* outcomes, so an experiment is judged on its method, not a lucky week.

**What it's built to test**

| | |
|---|---|
| **Agent architectures** | research topologies, orchestration and judging strategies, prompt and tool designs |
| **Prediction models** | ensemble configurations, feature recipes, calibration methods |
| **Execution & risk policies** | position sizing, entry/exit triggers, drawdown response |
| **Evaluation methodology itself** | judge calibration, statistical promotion gates |

Finance-specific by design, with the statistical rigor a quant desk expects — purged cross-validation, deflated Sharpe, multiple-testing control, calibrated LLM judges over investment decisions — and instrumented end-to-end, so every signal, prediction, fill, and dollar of P&L is traceable.

**[nousergon.ai](https://nousergon.ai)**&nbsp; ·&nbsp; **[Live dashboard](https://live.nousergon.ai)**&nbsp; ·&nbsp; **[Blog](https://nousergon.ai/blog)**

#### Public repos

| Repo | What it is |
|---|---|
| [alpha-engine-evaluator](https://github.com/cipher813/alpha-engine-evaluator) | The measurement & evaluation layer — grades every module's output into a report card; a weekly agent proposes refinements |
| [alpha-engine-research](https://github.com/cipher813/alpha-engine-research) | Multi-agent investment-research pipeline — six sector teams, a CIO, and a macro economist on LangGraph |
| [alpha-engine-predictor](https://github.com/cipher813/alpha-engine-predictor) | Stacked meta-ensemble predicting 21-day market-relative returns with a confidence-driven veto |
| [alpha-engine-backtester](https://github.com/cipher813/alpha-engine-backtester) | Weekly evaluator + parameter optimizer that writes tuned configs back to the system |
| [alpha-engine-lib](https://github.com/cipher813/alpha-engine-lib) | Shared substrate — decision capture, freshness gates, trading-calendar arithmetic, cost telemetry |
| [alpha-engine-docs](https://github.com/cipher813/alpha-engine-docs) | Architecture, module guides, and the system-overview entry point |

<sub>Architecture and approach are public; the tuned weights, prompts, and thresholds are private.</sub>
