### Brian McMahon

Building **[Nous Ergon](https://nousergon.ai)** — a harness for running rigorous AI/ML experiments in finance.

It runs experiments through a full production pipeline — multi-agent research, ML prediction, and risk-gated execution — and measures the results.

**Experiments it can run**
- **Agent architectures** — research topologies, orchestration and judging strategies
- **Prediction models** — ensemble configurations, feature recipes, calibration
- **Execution & risk policies** — position sizing, entry/exit triggers, drawdown response
- **Evaluation methodology** — judge calibration, statistical promotion gates

**[nousergon.ai](https://nousergon.ai)**&nbsp; ·&nbsp; **[Live dashboard](https://live.nousergon.ai)**&nbsp; ·&nbsp; **[Blog](https://nousergon.ai/blog)**

#### Nous Ergon

| Repo | What it is |
|---|---|
| [alpha-engine-docs](https://github.com/cipher813/alpha-engine-docs) | System overview & architecture — **start here** |
| [alpha-engine-evaluator](https://github.com/cipher813/alpha-engine-evaluator) | Measurement & evaluation layer — grades every module's output; a weekly agent proposes refinements |
| [alpha-engine-research](https://github.com/cipher813/alpha-engine-research) | Multi-agent investment-research pipeline on LangGraph |
| [alpha-engine-predictor](https://github.com/cipher813/alpha-engine-predictor) | Stacked meta-ensemble predicting 21-day market-relative returns |
| [alpha-engine-backtester](https://github.com/cipher813/alpha-engine-backtester) | Weekly evaluator + parameter optimizer |
| [alpha-engine-lib](https://github.com/cipher813/alpha-engine-lib) | Shared substrate — decision capture, freshness gates, cost telemetry |

#### Other open source

| Repo | What it is |
|---|---|
| [mnemon](https://github.com/cipher813/mnemon) | Self-hosted, cross-device long-term memory for AI agents via MCP — hybrid semantic + keyword search, your keys |
| [morning-signal](https://github.com/cipher813/morning-signal) | Self-hostable daily briefing podcast — Claude writes it, TTS voices it, publishes an RSS feed |
| [flow-doctor](https://github.com/cipher813/flow-doctor) | Error monitoring for Python pipelines — capture, dedupe, LLM root-cause, route alerts, auto-fix PRs |

<sub>Nous Ergon: architecture and approach are public; the tuned weights, prompts, and thresholds are private.</sub>
