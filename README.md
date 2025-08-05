# Striketarget Live Trade Performance

## Overview
This repository provides real-time transparency into Striketarget's options trading performance. Every trade is executed with real capital, governed by our proprietary Neural Decision Framework, designed to mitigate the costly, unforced errors that impact professional traders.

**Live Beta Launch:** September 1, 2025

## The Problem: The High Cost of Preventable Errors
Even professional traders are susceptible to cognitive biases that lead to unforced errors. Academic research has consistently quantified the impact of these biases:

- **Overconfidence Leads to Underperformance:** Research by Barber & Odean in "Trading Is Hazardous to Your Wealth" (2000) shows that the most active traders, often driven by overconfidence, significantly underperform their peers.
- **The Disposition Effect:** Shefrin & Statman (1985) identified the "disposition effect," a widespread bias where traders sell winning positions too early and hold losing positions for too long, directly harming returns.

These are not catastrophic system failures; they are the common, everyday mistakes that erode P&L. Striketarget is designed to prevent them.

## The Striketarget Solution
Our Neural Decision Framework acts as a systematic, rules-based co-pilot to enforce discipline and mitigate cognitive bias. It ensures every trade is evaluated against a pre-defined strategy, preventing impulsive decisions and filtering out low-conviction setups.

## Performance Metrics

### Primary Metrics (Institutional Focus)
- **Max Drawdown** - Maximum peak-to-trough decline
- **Sharpe Ratio** - Risk-adjusted returns
- **Sortino Ratio** - Downside risk-adjusted returns
- **Calmar Ratio** - Annual return / Max drawdown
- **Win Rate** - Percentage of profitable trades
- **Profit Factor** - Gross profit / Gross loss

### Secondary Metrics (Error Prevention Focus)
- **Execution Cost Tracking**
- **Unforced Errors Avoided**
- **Neural Decision Framework Consensus Scores**
- **Time to Recovery** (from drawdown)

## Data Structure
We provide full transparency into our trade data.

### Individual Trade Record
```json
{
  "date": "2025-09-01",
  "time": "09:30:00",
  "symbol": "SPY",
  "strategy": "iron_condor",
  "entry_price": 450.50,
  "exit_price": 451.20,
  "pnl_percent": 0.15,
  "risk_metrics": { "sharpe_ratio": 1.45, "sortino_ratio": 2.1 },
  "error_prevention": {
    "filters_applied": ["volatility_threshold", "liquidity_check", "neural_decision_framework_consensus"],
    "manual_override": false,
    "neural_decision_framework_consensus_score": 0.85
  }
}
```

## Academic Foundation
Our methodology is grounded in established behavioral finance research.

- Barber, B. M., & Odean, T. (2000). Trading is hazardous to your wealth: The common stock investment performance of individual investors. *The Journal of Finance*.
- Shefrin, H., & Statman, M. (1985). The Disposition to Sell Winners Too Early and Ride Losers Too Long: Theory and Evidence. *The Journal of Finance*.
- Odean, T. (1999). Do investors trade too much?. *American Economic Review*.

## Risk Disclosure
**Important:** This repository is for educational and transparency purposes only. Past performance does not guarantee future results. Options trading involves substantial risk and is not suitable for all investors. Striketarget provides tools for analysis and does not provide investment advice.

## Contact
For institutional inquiries, please contact **partners@striketarget.ai**.

---

*The beta features initial Neural Decision Framework capabilities presently under development.* 