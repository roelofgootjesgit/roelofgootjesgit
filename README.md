Roelof Gootjes

Backend / Data / FinTech Systems Engineer

I build deterministic, event-driven systems
that turn complex decision pipelines into measurable and reproducible outcomes.

QuantMetrics Suite

Most trading systems don’t fail because of bad ideas —
they fail because they cannot prove them under real conditions.

QuantMetrics is a modular trading infrastructure
that turns strategy ideas into testable, traceable, and verifiable systems.

It enables you to:

validate decisions under real execution constraints
execute trades through controlled, broker-agnostic layers
capture every step in an auditable event trail
analyze exactly where performance is gained or lost

This is not a trading bot.
This is infrastructure for building, testing, and proving decision systems.

Core Principle

Edge = Model Probability – Market Probability

The system exists to measure, validate, and execute this edge —
not assume it.

What This Solves

Most traders have strategies.
Almost none have infrastructure.

This leads to:

inconsistent execution
hidden risk exposure
lack of reliable performance tracking
inability to validate real edge

QuantMetrics solves this by enforcing:

deterministic execution
centralized risk control
full decision traceability
reproducible analysis via event replay
System Architecture
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

A closed feedback loop — not just execution, but continuous system validation and improvement.

Components
Component	Role
QuantOS
	Orchestration — process control, environment setup, multi-repo coordination
QuantBuild
	Strategy engine — signal generation, regime detection, portfolio logic
QuantBridge
	Execution layer — broker abstraction, order routing, risk enforcement
QuantLog
	Observability — event logging, trace replay, system validation

Each component is fully decoupled and independently testable.

What This Demonstrates
Event-driven system design
Clear separation of concerns (decision / execution / logging / analysis)
Deterministic and reproducible pipelines
Observability through structured event logging
Real-world system thinking (risk, execution constraints, failure handling)
Ability to design and manage complex multi-component systems
Design Principles
Strategy logic contains zero broker API calls
Execution is fully broker-agnostic
Risk is centralized and enforced system-wide
All behavior is traceable through event logs
Systems are deterministic and reproducible
Infrastructure first, strategy second
Stack

Core
Python · Pydantic · PyYAML · dotenv

Data & Storage
Pandas · NumPy · PyArrow · Parquet · JSONL

Execution & Market Data
cTrader Open API · Oanda v20 · Dukascopy · yfinance

Observability & Analytics
Streamlit · Telegram · Matplotlib

Testing
pytest · contract validation

Deployment
Linux VPS · systemd · cron

Status

Currently running in:

paper trading
dry-run environments
live infrastructure testing

Next step:

→ full live deployment and multi-account scaling

For Companies & Collaborators

This system is relevant for:

trading infrastructure development
financial data pipelines
decision system validation
backend systems with auditability requirements
event-driven architectures in production environments
Contact

Building in public.
Available for:

backend / data engineering roles
fintech infrastructure projects
system design and automation

GitHub: https://github.com/roelofgootjesgit
