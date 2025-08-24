# Describe Your Build

**Baruk** is the first AI-powered DeFi platform on **SEI**. We're building an autonomous system that can trade, protect accounts, and simplify DeFi so anyone can use it with minimal learning.

## What's Built (Proof of Concept)

* **Account Abstraction (Privy):** Web2-simple onboarding with self-custody.
* **Baruk DeFi Protocol:** Our own swap/liquidity/trading primitives on SEI as the execution base.
* **Trading Core (v0):** Smart routing across our pools/venues on SEI, price-impact awareness, slippage limits, and pre-trade checks.
* **Risk & Precision Engine (v0):**
  * Position sizing rules, max loss per trade/day, slippage/price-deviation guards.
  * Pre-trade validation and post-trade health checks with kill-switch.
* **Security Layer (v0):**
  * Approval/permit scanner, transaction simulation ("what happens if I sign?"), contract heuristics for scam/rug patterns.
* **SEI-Native AI Training Pipeline:** We're fine-tuning an open-source GPT model on SEI tasks (chain reading, tx reasoning, DeFi flows). This is the model that powers the agent.
* **Agent Preview:** The agent can read wallet/position state, explain actions in plain language, and run sandbox/paper trades.

## What's In Progress

* **Autonomous Trading Agents (v1):**
  * Execute strategies end-to-end with user-defined risk limits; schedule, monitor, and adapt.
* **Risk & Precision Engine (v1):**
  * VaR-style limits, per-user risk profiles, circuit breakers, time-outs, and anomaly-based auto-pause.
* **Wallet Guard (v1):**
  * Policy-based approvals, spending caps, session controls, automatic revocation of risky approvals.
* **Advanced Scam/Rug Protection:**
  * Honeypot tests, liquidity lock checks, privileged-function audits, oracle/manipulation alerts.
* **One-Click DeFi:**
  * "Stake/Lend/LP" flows that bundle approvals, routing, and risk checks into a single confirmed action.
* **Cross-Protocol Adapters:**
  * Access other SEI DeFi protocols from one place, with Baruk risk controls on top.
* **Explainable AI:**
  * Pre-trade reasoning ("why this trade"), simulated outcomes, and post-trade breakdowns.
* **Backtesting & Paper Trading:**
  * Strategy testing on historical SEI data; safe trial runs before going live.
* **Strategy Library & Marketplace:**
  * Curated, audited strategies users can enable with guardrails.
* **Observability & Audit Trails:**
  * On-chain/off-chain logs so actions are verifiable and reviewable.
* **Mobile-Ready UX:**
  * Web2-level clarity, no jargon, helpful defaults, and clear safety prompts.

## Why This Can Be Realized

* **SEI is built for agents:** low latency and parallel execution suit autonomous trading and real-time protection.
* **Model First:** completing our SEI-trained GPT unlocks reliable chain understanding, safe automation, and plain-language guidance.
* **Safety by Design:** the Risk & Precision Engine and Security Layer wrap every action, so autonomy never compromises protection.

## Outcome

A platform where the AI can handle trading and safety for users with little to no training—**autonomous, explainable, and protected**—becoming the **go-to hub for AI decentralization on SEI**.
