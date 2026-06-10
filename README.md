### Brian McMahon

Building **[Nous Ergon](https://nousergon.ai)** — a harness for rigorous AI/ML experiments in finance.

An equity research-and-trading system, built solo, instrumented end-to-end: multi-agent research (LangGraph + Claude), a stacked ML prediction ensemble, risk-gated execution, and a weekly self-tuning loop — all sitting on an eval substrate that grades every module's output and an approval-gated agent that proposes refinements each week.

Eval-led and finance-specific. The harness is the durable artifact; alpha capture is one experiment among several.

**[nousergon.ai](https://nousergon.ai)**&nbsp; ·&nbsp; **[Live dashboard](https://live.nousergon.ai)**&nbsp; ·&nbsp; **[Blog](https://nousergon.ai/blog)**

#### Selected public repos

| Repo | What it is |
|---|---|
| [alpha-engine-evaluator](https://github.com/cipher813/alpha-engine-evaluator) | Measurement & evaluation layer — Report Card grading + the Director weekly action-plan agent |
| [alpha-engine-research](https://github.com/cipher813/alpha-engine-research) | Multi-agent investment-research pipeline — six sector teams, a CIO, and a macro economist on LangGraph |
| [alpha-engine-predictor](https://github.com/cipher813/alpha-engine-predictor) | Stacked meta-ensemble predicting 21-day market-relative alpha with a confidence-driven veto |
| [alpha-engine-backtester](https://github.com/cipher813/alpha-engine-backtester) | Weekly evaluator + parameter optimizer that writes tuned configs back to the system |
| [alpha-engine-lib](https://github.com/cipher813/alpha-engine-lib) | Shared substrate — decision capture, freshness gates, trading-calendar arithmetic, cost telemetry |
| [alpha-engine-docs](https://github.com/cipher813/alpha-engine-docs) | Architecture, module guides, and the system-overview entry point |

<sub>Disclosure boundary: architecture and approach are public; specific weights, prompts, and thresholds are private.</sub>
