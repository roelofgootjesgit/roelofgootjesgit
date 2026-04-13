# Roelof Gootjes

Python developer. Trading systems architect.  
Building deterministic trading infrastructure.

---

## QuantMetrics Suite

Most trading systems fail for one reason:  
they cannot prove their edge in live conditions.

QuantMetrics is a modular trading infrastructure  
designed to validate, execute and monitor strategies  
with institutional-grade control.

This is not a trading bot.  
This is a full trading system stack.

---

## Core Principle

Edge = Model Probability – Market Probability

The system exists to measure, validate and execute this edge.

---

## What This Solves

Most traders have strategies.  
Almost none have infrastructure.

This leads to:
- inconsistent execution
- hidden risk exposure
- no reliable performance tracking
- inability to validate edge

QuantMetrics solves this by enforcing:

- deterministic execution  
- centralized risk control  
- full decision traceability  
- reproducible backtesting via event replay  

---

## System Architecture
Market Data / News
↓
Signal Engine (QuantBuild)
↓
Risk Engine
↓
Execution Engine (QuantBridge)
↓
Broker / Trades
↓
Event Logging (QuantLog)
↓
Analytics / Evaluation
↓
Strategy Improvement Loop


A closed feedback loop — not just execution, but continuous improvement.

---

## Components

| Component | Role |
|----------|------|
| [QuantMetrics OS](https://github.com/roelofgootjesgit/quantmetrics_os) | Orchestration — process control, environment setup, multi-repo coordination |
| [QuantBuild E1](https://github.com/roelofgootjesgit/quantbuildE1) | Strategy engine — signal generation, regime detection, portfolio logic |
| [QuantBridge](https://github.com/roelofgootjesgit/quantBridge-v.1) | Execution layer — broker abstraction, order routing, prop firm risk control |
| [QuantLog](https://github.com/roelofgootjesgit/quantlog-v.1) | Observability — event logging, trace replay, system validation |

Each component is fully decoupled and independently testable.

---

## Design Principles

- Strategy code contains zero broker API calls  
- Execution is broker-agnostic via adapter layer  
- Risk is centralized — not duplicated per strategy  
- Full trace replay from raw event logs  
- Deterministic system behavior  
- Built for multi-account and prop environments  
- Infrastructure first, strategy second  

---

## Stack

**Core**  
Python 3.10 · Pydantic v2 · PyYAML · dotenv · filelock  

**Data & Storage**  
Pandas · NumPy · PyArrow · Parquet · JSONL  

**Market Data**  
Dukascopy · Oanda v20 · yfinance · ictrader

**Execution**  
cTrader Open API · Oanda v20  API

**News & Sentiment**  
RSS · httpx · OpenAI  

**Observability**  
Streamlit · Telegram · Matplotlib  

**Testing**  
pytest · contract validation  

**Deployment**  
Linux VPS · systemd · cron  

---

## Status

Currently running in:

- paper trading
- dry-run environments
- live infrastructure testing phase

Next step:
→ full live deployment + multi-account scaling

---

## For Builders & Traders

QuantMetrics is built for:

- traders who want to validate real edge  
- developers building trading systems  
- prop firm automation setups  
- multi-account trading infrastructure  

---

## Contact / Work

Building in public.  
Available for:

- custom trading infrastructure  
- strategy validation systems  
- execution & risk pipelines  

GitHub: https://github.com/roelofgootjesgit
