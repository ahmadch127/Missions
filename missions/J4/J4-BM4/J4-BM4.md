# Part A — Human-Readable Boss Mission Document

# 1. Boss Mission Metadata

**Boss Mission ID:** J4-BM4  
**Journey:** Grow Wealth Wisely  
**Boss Mission Title:** Survive a Market Crash  
**Boss Mission Type:** Journey Boss  
**Unlocks After:** J4-M26 — Long-Term Investing  
**Target Age Group:** Adults 18+  
**Difficulty:** Easy  
**Estimated Duration:** 9 minutes  
**Simulation Period:** Five years following the initial decline  
**Currency and Locale:** Pakistan — PKR (Rs.), en-PK  
**Language:** English

## Concepts Being Assessed

- Understanding volatility
- Managing concentration risk through diversification
- Investing regularly during changing markets
- Following a long-term plan
- Protecting emergency savings
- Recognising emotionally driven decisions

## Learning Objective
Apply volatility, diversification, regular investing, long-term planning, emergency-savings protection, and emotional control during a major market decline.

## Primary Combined Misconception
A major market decline means every investment has permanently failed and should be sold immediately.

## Secondary Misconceptions

- Market prices are guaranteed to recover after every decline.
- Borrowing or using emergency savings is a good way to recover investment losses quickly.
- Continuing regular investments during falling markets always guarantees a profit.
- Diversification prevents all losses during a market crash.

## Key Takeaway
**Review the plan, protect emergency money, and do not confuse falling prices with guaranteed failure or recovery.**

# 2. Boss Mission Overview
The learner manages a long-term portfolio after a sudden 25% decline. Five connected stages test the first reaction, social pressure, concentration risk, monthly contributions, and a five-year simulation with a genuine emergency. Sales, borrowing, emergency-fund use, diversification, and contribution choices persist into later stages. The final dashboard measures realised losses, portfolio value, contributions, emergency protection, debt, emotional decisions, diversification, long-term discipline, and financial confidence. The experience should feel tense but controlled, with replayable trade-offs and no guaranteed market outcome.

# 3. Concepts Being Assessed

| Mission | Title | Concept | Stages | Interaction | Evaluation |
| --- | --- | --- | --- | --- | --- |
| J4-M21 | Diversification | Reduce dependence on one company, sector, or outcome. | J4-BM4-ST3, J4-BM4-ST5 | before_vs_after, timeline_slider_investment_simulator_decision_tree | Applies the concept inside the connected crash simulation |
| J4-M23 | Volatility | Separate sharp price movement from permanent failure or guaranteed recovery. | J4-BM4-ST1, J4-BM4-ST2, J4-BM4-ST5 | decision_tree, predict_outcome_decision_tree, timeline_slider_investment_simulator_decision_tree | Applies the concept inside the connected crash simulation |
| J4-M24 | Start Early | Use time as planning flexibility without assuming future growth. | J4-BM4-ST1, J4-BM4-ST5 | decision_tree, timeline_slider_investment_simulator_decision_tree | Applies the concept inside the connected crash simulation |
| J4-M25 | Regular Investing | Follow or adjust an affordable contribution plan through changing prices. | J4-BM4-ST4, J4-BM4-ST5 | budget_builder_decision_tree, timeline_slider_investment_simulator_decision_tree | Applies the concept inside the connected crash simulation |
| J4-M26 | Long-Term Investing | Review goals, investment quality, affordability, and emergency protection before reacting. | J4-BM4-ST1, J4-BM4-ST2, J4-BM4-ST4, J4-BM4-ST5 | budget_builder_decision_tree, decision_tree, predict_outcome_decision_tree, timeline_slider_investment_simulator_decision_tree | Applies the concept inside the connected crash simulation |

# 4. Starting Financial State

| Value | Starting Position |
| --- | --- |
| Portfolio before decline | Rs. 200,000 |
| Portfolio after decline | Rs. 150,000 |
| Unrealised loss | Rs. 50,000 |
| General savings | Rs. 30,000 |
| Emergency fund | Rs. 100,000 |
| Monthly contribution budget | Rs. 10,000 |
| Debt | Rs. 0 |
| Time remaining | At least seven years |
| Simulation period | Five years |

**Financial Goal:** Required debt payments and the Year 2 emergency must use a valid funding source before continuing. Keep the long-term plan aligned while protecting emergency savings.

**Values that can change:** Investments, contributions, cash, emergency savings, debt, realised losses, unrealised gains or losses, concentration, diversification, and behaviour scores.

**Negative balances:** Not allowed. Invalid budget or emergency-funding choices must be revised.

# 5. Hook Screen

**Screen Title:** Your Portfolio Just Fell

**Hook Text:** Rs. 200,000 becomes Rs. 150,000 overnight. Headlines shout, friends panic, and your seven-year goal remains. What do you do first?

**Suggested Illustration:** A portfolio card drops beside urgent headlines and a seven-year calendar.

**Primary Button:** Enter the Crash

# 6. Scenario Setup Screens

## The Starting Drop

**Story Text:** Your long-term portfolio has fallen 25%. The Rs. 50,000 decline is still unrealised because you have not sold.

**Suggested Visual:** A before-and-after portfolio card.

**Important Financial Information:**

- amountOriginallyInvested: 200000
- investmentBalance: 150000
- unrealisedGainLoss: -50000

**Primary Button:** View Your Safety Net

## Money Outside the Market

**Story Text:** You have Rs. 30,000 general savings and a separate Rs. 100,000 emergency fund. Neither is part of the portfolio.

**Suggested Visual:** Three separate containers for investments, cash, and emergency savings.

**Important Financial Information:**

- generalSavings: 30000
- emergencyFund: 100000
- debtBalance: 0

**Primary Button:** Check the Plan

## Seven Years Still Remain

**Story Text:** The goal is at least seven years away. You also planned an affordable Rs. 10,000 monthly contribution.

**Suggested Visual:** A seven-year timeline beside a monthly contribution card.

**Important Financial Information:**

- timeRemainingYears: 7
- monthlyContributionBudget: 10000

**Primary Button:** Choose Your First Move

# 7. Pre-Simulation Decision

**Question:** What should guide your first response to the 25% decline?

- **The loudest headline**: Headlines cannot decide whether the portfolio still fits the goal.
- **A review of the goal, time horizon, and investment quality** — Recommended: Correct. Review creates space for evidence before fear or hope drives the decision.
- **A guarantee that prices will recover**: No one can guarantee recovery.
- **Borrowing enough to replace the loss**: Borrowing adds repayment pressure without reversing the existing decline.

**Connection:** The next five stages test review, social pressure, diversification, affordability, emergency protection, and uncertainty.

# 8. Persistent Simulation State

| Value | Initial | Minimum | Maximum | Increases Through | Decreases Through | Stages | Visible |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Current Investment Balance | 150000 | 0 | 1000000 | contributions, positive simulated movement | sales, withdrawals, negative simulated movement | J4-BM4-ST1, J4-BM4-ST2, J4-BM4-ST4, J4-BM4-ST5 | Yes |
| Total Additional Contributions | 0 | 0 | 600000 | monthly contributions | paused or redirected contributions | J4-BM4-ST4, J4-BM4-ST5 | Yes |
| Cash Outside Portfolio | 30000 | 0 | 300000 | sales, paused contributions | emergencies, new investments | J4-BM4-ST1, J4-BM4-ST2, J4-BM4-ST4, J4-BM4-ST5 | Yes |
| Emergency Fund | 100000 | 0 | 150000 | top-ups | genuine emergencies, investing emergency money | J4-BM4-ST4, J4-BM4-ST5 | Yes |
| Debt Balance | 0 | 0 | 200000 | borrowing to invest, emergency borrowing | classroom repayments | J4-BM4-ST1, J4-BM4-ST4, J4-BM4-ST5 | Yes |
| Monthly Debt Payment | 0 | 0 | 10000 | new borrowing | completed repayment | J4-BM4-ST1, J4-BM4-ST4, J4-BM4-ST5 | Yes |
| Realised Losses | 0 | 0 | 200000 | selling below cost | — | J4-BM4-ST1, J4-BM4-ST2, J4-BM4-ST5 | Yes |
| Unrealised Gain or Loss | -50000 | -500000 | 500000 | positive market movement | negative market movement | J4-BM4-ST1, J4-BM4-ST2, J4-BM4-ST5 | Yes |
| Portfolio Concentration | moderately_concentrated | 0 | 100 | greater dependence on one outcome | spreading exposure | J4-BM4-ST3, J4-BM4-ST5 | Yes |
| Diversification Score | 55 | 0 | 100 | reducing concentration | depending on one company or sector | J4-BM4-ST3, J4-BM4-ST5 | Yes |
| Emotional Decision Score | 50 | 0 | 100 | reviewing evidence, checking goals | panic selling, following predictions, assuming guaranteed recovery | J4-BM4-ST1, J4-BM4-ST2, J4-BM4-ST5 | No |
| Long-Term Discipline Score | 50 | 0 | 100 | affordable planning, review before change | investment debt, emergency-fund misuse, fear-only changes | J4-BM4-ST1, J4-BM4-ST4, J4-BM4-ST5 | No |

# 9. Multi-Stage Simulation

# Stage 1 — First Market Drop

**Stage ID:** J4-BM4-ST1  
**Timeline:** Day 1  
**Concepts:** volatility, long_term_planning, emotional_control  
**Interaction:** decision_tree

## Situation
The portfolio has fallen from Rs. 200,000 to Rs. 150,000. The goal is still at least seven years away, but frightening headlines create pressure to act immediately.

## Learner Objective
Choose the first response and understand how it changes realised losses, debt, and later options.

## Interaction Configuration
```json
{
  "startingNode": {
    "id": "J4-BM4-ST1-N1",
    "question": "What do you do first?"
  },
  "followUpNodes": [
    {
      "id": "J4-BM4-ST1-N2",
      "condition": "review_selected",
      "question": "What should the review include?",
      "preferredElements": [
        "original_goal",
        "time_horizon",
        "portfolio_quality",
        "fees",
        "diversification",
        "need_for_money"
      ]
    }
  ],
  "terminalOutcomes": [
    "sold_after_decline",
    "review_started",
    "borrowed_to_invest",
    "remained_invested_without_review"
  ],
  "tradeOffSummary": [
    {
      "choice": "sell_everything",
      "benefit": "removes_future_market_exposure",
      "risk": "realises_the_current_loss"
    },
    {
      "choice": "review_plan",
      "benefit": "supports_an_informed_decision",
      "risk": "uncertainty_remains"
    },
    {
      "choice": "borrow_to_invest",
      "benefit": "adds_market_exposure",
      "risk": "creates_debt"
    },
    {
      "choice": "ignore_without_checking",
      "benefit": "avoids_an_immediate_sale",
      "risk": "may_miss_real_problems"
    }
  ],
  "educationalAssumptions": [
    "Borrowing Rs. 50,000 creates ten equal classroom repayments of Rs. 5,000.",
    "No interest rate or fee is invented.",
    "Selling at Rs. 150,000 realises the Rs. 50,000 decline.",
    "Reviewing does not assume recovery."
  ]
}
```

## Available Choices

### Sell everything immediately

**Classification:** risky  
**Reason:** The sale happens before reviewing the goal or investment quality.  
**Immediate financial effect:** The portfolio is sold for Rs. 150,000.  
**Feedback:** Selling removes future price uncertainty, but the Rs. 50,000 decline becomes realised.  
**Short-term consequence:** Cash outside the portfolio becomes Rs. 180,000.  
**Later consequence:** Later market paths affect only money invested again.

### Review the investment plan

**Classification:** recommended  
**Reason:** It separates evidence from immediate emotional pressure.  
**Immediate financial effect:** No sale or borrowing occurs.  
**Feedback:** Review the goal, time horizon, quality, fees, diversification, and need for the money.  
**Short-term consequence:** The Rs. 50,000 decline remains unrealised.  
**Later consequence:** Later choices can respond to evidence instead of fear alone.

### Borrow Rs. 50,000 to recover the loss

**Classification:** high_risk  
**Reason:** Debt and market uncertainty are combined.  
**Immediate financial effect:** Debt and the portfolio each increase by Rs. 50,000.  
**Feedback:** Borrowing does not recover the old loss. The new money may also fall.  
**Short-term consequence:** Monthly debt payments become Rs. 5,000.  
**Later consequence:** Only Rs. 5,000 of the monthly contribution budget remains flexible in Stage 4.

### Ignore everything without checking

**Classification:** risky  
**Reason:** Patience is used without reviewing whether the portfolio still fits.  
**Immediate financial effect:** No balance changes immediately.  
**Feedback:** Avoiding panic can help, but long-term investing does not mean ignoring quality or suitability.  
**Short-term consequence:** The decline remains unrealised.  
**Later consequence:** A concentration or quality problem may remain hidden.

## Recommended Decision Logic

**Generally strongest:** Review the goal, time horizon, diversification, fees, and investment quality before making a major change.

**Other reasonable paths:**
- Selling may be reasonable after review if the investment is unsuitable or the money is needed sooner.
- Remaining invested may be reasonable when the portfolio still fits, but only after review.

**Trade-off:** Selling removes future market exposure but realises the loss; staying invested preserves uncertainty and possible future movement.

## Updated State Screen

**Title:** First Response Recorded

- **current_investment_balance:** 150000 → selected_choice.current_investment_balance. Selling or borrowing changes market exposure.
- **realised_losses:** 0 → selected_choice.realised_losses. A loss becomes realised only when sold below cost.
- **debt_balance:** 0 → selected_choice.debt_balance. Borrowing creates a repayment obligation.

**Learning message:** A price decline and permanent investment failure are not automatically the same.

**Next teaser:** A friend now sends a confident prediction.

## Retry Behaviour
Risky choices may continue. The learner may revise once before the decision is carried forward.

## Accessibility Alternative
Present four labelled buttons and a balance summary. Choose one response and hear the investment, cash, debt, and loss changes.

# Stage 2 — Social Pressure

**Stage ID:** J4-BM4-ST2  
**Timeline:** Day 2  
**Concepts:** emotional_control, evidence_based_review, volatility  
**Interaction:** predict_outcome_decision_tree

## Situation
A friend says, “Sell now. The market will never recover. Everyone who waits will lose everything.” Your balances from Stage 1 remain in place.

## Learner Objective
Predict what the message can prove, then choose how to respond.

## Interaction Configuration
```json
{
  "prediction": {
    "id": "J4-BM4-ST2-P1",
    "situation": "A friend confidently predicts permanent market failure.",
    "question": "What does the message prove?",
    "options": [
      {
        "id": "J4-BM4-ST2-P1-O1",
        "label": "The market will never recover",
        "isPreferred": false,
        "feedback": "A confident statement is not proof of a future result."
      },
      {
        "id": "J4-BM4-ST2-P1-O2",
        "label": "The friend is worried",
        "isPreferred": true,
        "feedback": "Correct. The message reveals emotion and opinion, not certainty."
      },
      {
        "id": "J4-BM4-ST2-P1-O3",
        "label": "Every investment has failed",
        "isPreferred": false,
        "feedback": "Different investments can have different problems and outcomes."
      }
    ],
    "likelyEducationalOutcome": "The learner separates social pressure from evidence.",
    "explanation": "Neither a friend nor the mission can know with certainty whether prices will recover.",
    "confidenceSelection": {
      "enabled": true,
      "options": [
        "not_sure",
        "somewhat_sure",
        "very_sure"
      ]
    }
  },
  "startingNode": {
    "id": "J4-BM4-ST2-N1",
    "question": "How do you respond?"
  },
  "followUpNodes": [
    {
      "id": "J4-BM4-ST2-N2",
      "condition": "research_or_goal_review",
      "question": "What should you distinguish?",
      "preferredElements": [
        "market_wide_movement",
        "permanent_problem",
        "temporary_volatility",
        "portfolio_no_longer_fits_goal"
      ]
    }
  ],
  "terminalOutcomes": [
    "sold_from_social_pressure",
    "researched_decline",
    "reviewed_goal",
    "assumed_guaranteed_recovery"
  ]
}
```

## Available Choices

### Follow the friend and sell

**Classification:** risky  
**Reason:** The decision relies mainly on another person’s prediction.  
**Immediate financial effect:** Any remaining portfolio is sold at its current value.  
**Feedback:** The sale removes future market exposure, but the decision is pressure-led.  
**Short-term consequence:** The remaining portfolio moves to cash.  
**Later consequence:** Later paths apply only to new contributions.

### Research the situation

**Classification:** recommended  
**Reason:** It checks causes and investment quality rather than one prediction.  
**Immediate financial effect:** No automatic sale occurs.  
**Feedback:** Review what caused the decline and whether the holdings remain suitable.  
**Short-term consequence:** Balances remain unchanged.  
**Later consequence:** Stage 3 uses evidence instead of the friend’s claim.

### Review the original goal

**Classification:** recommended  
**Reason:** It checks whether the time horizon and strategy still fit.  
**Immediate financial effect:** No automatic sale occurs.  
**Feedback:** Compare the seven-year goal with the portfolio and current needs.  
**Short-term consequence:** Balances remain unchanged.  
**Later consequence:** Contribution and emergency decisions stay linked to the goal.

### Assume recovery is guaranteed

**Classification:** risky  
**Reason:** Hope replaces review and genuine problems may be missed.  
**Immediate financial effect:** The portfolio remains invested without review.  
**Feedback:** Remaining invested may fit, but guaranteed recovery is not a valid reason.  
**Short-term consequence:** No balance changes immediately.  
**Later consequence:** A weak company or unsuitable portfolio may remain unaddressed.

## Recommended Decision Logic

**Generally strongest:** Research the decline and review the original goal before following anyone’s prediction.

**Other reasonable paths:**
- Research and goal review are both strong and may be combined.
- Selling may become reasonable after evidence shows the investment no longer fits.

**Trade-off:** Research takes time while uncertainty remains, but it reduces dependence on fear or guaranteed-recovery assumptions.

## Updated State Screen

**Title:** Pressure Response Recorded

- **emotional_decision_score:** score_before_stage → score_after_stage. Evidence-based choices improve the score.
- **realised_losses:** realised_losses_before_stage → realised_losses_after_stage. Selling turns an unrealised decline into a realised loss.

**Learning message:** A confident prediction is not evidence of permanent failure or guaranteed recovery.

**Next teaser:** Compare how concentration changes one company’s impact.

## Retry Behaviour
The learner may revise before confirmation. The outcome then carries forward.

## Accessibility Alternative
Use labelled prediction and response buttons. Choose what the message proves, then choose how to respond.

# Stage 3 — Diversification Check

**Stage ID:** J4-BM4-ST3  
**Timeline:** Week 1  
**Concepts:** diversification, concentration_risk, volatility  
**Interaction:** before_vs_after

## Situation
Two portfolios were each worth Rs. 200,000 before the decline. One depends on a single company. The other spreads money across companies, bonds, an ETF, and cash.

## Learner Objective
Compare the declines, identify concentration risk, and decide how to handle the learner’s own concentration.

## Interaction Configuration
```json
{
  "beforeState": [
    {
      "id": "J4-BM4-ST3-A-BEFORE",
      "label": "Portfolio A — Concentrated",
      "totalValue": 200000,
      "allocations": {
        "one_company": 200000,
        "bonds": 0,
        "etf": 0,
        "cash": 0
      }
    },
    {
      "id": "J4-BM4-ST3-B-BEFORE",
      "label": "Portfolio B — Diversified",
      "totalValue": 200000,
      "allocations": {
        "several_companies": 70000,
        "bonds": 40000,
        "etf": 60000,
        "cash": 30000
      }
    }
  ],
  "afterState": [
    {
      "id": "J4-BM4-ST3-A-AFTER",
      "label": "Portfolio A After Decline",
      "totalValue": 110000,
      "declineAmount": 90000,
      "declinePercent": 45
    },
    {
      "id": "J4-BM4-ST3-B-AFTER",
      "label": "Portfolio B After Decline",
      "totalValue": 160000,
      "declineAmount": 40000,
      "declinePercent": 20
    }
  ],
  "valuesCompared": [
    "dependence_on_one_outcome",
    "decline_amount",
    "decline_percent",
    "asset_types",
    "cash_access"
  ],
  "learnerQuestions": [
    {
      "id": "J4-BM4-ST3-Q1",
      "question": "Which portfolio depends more heavily on one outcome?",
      "correctAnswer": "portfolio_a"
    },
    {
      "id": "J4-BM4-ST3-Q2",
      "question": "Which portfolio experiences the larger decline?",
      "correctAnswer": "portfolio_a"
    },
    {
      "id": "J4-BM4-ST3-Q3",
      "question": "Did diversification prevent Portfolio B from losing money?",
      "correctAnswer": "no"
    }
  ],
  "importantHiddenDifference": "Portfolio A depends entirely on one company; Portfolio B spreads exposure across several investment types.",
  "explanation": "Diversification reduced dependence on one outcome in this illustration, but it did not prevent loss.",
  "importantClarification": "This is educational only. Diversification can reduce concentration risk but cannot guarantee smaller losses in every decline."
}
```

## Available Choices

### Reduce concentration gradually

**Classification:** recommended  
**Reason:** The portfolio becomes less dependent on one outcome without assuming risk disappears.  
**Immediate financial effect:** No forced sale amount is applied; the plan is marked for gradual spreading.  
**Feedback:** Dependence on one company or sector falls.  
**Short-term consequence:** Diversification score rises.  
**Later consequence:** Weak simulated paths use the broadly spread setting.

### Keep the concentration after a full review

**Classification:** reasonable  
**Reason:** The learner knowingly accepts higher concentration risk.  
**Immediate financial effect:** No sale occurs.  
**Feedback:** The portfolio remains more dependent on one outcome.  
**Short-term consequence:** Diversification score falls.  
**Later consequence:** Weak paths apply a larger concentration adjustment.

### Sell because diversification also lost money

**Classification:** risky  
**Reason:** The choice treats risk reduction as failure because it did not remove all loss.  
**Immediate financial effect:** Any remaining portfolio is sold.  
**Feedback:** Diversification does not promise zero loss.  
**Short-term consequence:** Market exposure falls to zero.  
**Later consequence:** Only new contributions enter later paths.

## Recommended Decision Logic

**Generally strongest:** Reduce extreme concentration when dependence on one outcome is high and the change fits the long-term plan.

**Other reasonable paths:**
- Keeping concentration may be reasonable only after understanding the higher risk and ability to tolerate it.

**Trade-off:** More diversification reduces dependence on one outcome but cannot remove all market risk.

## Updated State Screen

**Title:** Concentration Reviewed

- **portfolio_concentration_level:** concentration_before_choice → selected_choice.concentration_level. The learner chose whether to reduce or keep dependence on one outcome.
- **diversification_score:** score_before_choice → score_after_choice. Spreading exposure improves the score without guaranteeing protection.

**Learning message:** Diversification reduces concentration risk; it does not prevent every loss.

**Next teaser:** Decide whether the Rs. 10,000 monthly contribution still fits.

## Retry Behaviour
Keep correct answers and retry only incorrect comparisons. Risky portfolio choices may continue.

## Accessibility Alternative
Present both portfolios as labelled tables with Previous and Next controls. Compare values, answer three questions, then choose a concentration response.

# Stage 4 — Regular Contribution

**Stage ID:** J4-BM4-ST4  
**Timeline:** Month 1  
**Concepts:** regular_investing, affordability, emergency_savings_protection, investment_debt  
**Interaction:** budget_builder_decision_tree

## Situation
You still have a Rs. 10,000 monthly contribution budget. Any debt repayment created earlier must come first, and emergency savings should remain separate from long-term investing.

## Learner Objective
Build a valid monthly plan and choose whether to continue, pause, misuse emergency money, or borrow.

## Interaction Configuration
```json
{
  "budgetBuilder": {
    "totalAvailableAmount": 10000,
    "requiredCategories": [
      {
        "id": "J4-BM4-ST4-B1",
        "label": "Required Debt Repayment",
        "minimumSource": "monthly_debt_payment",
        "maximum": 10000,
        "requiredWhen": "debt_balance_above_zero"
      }
    ],
    "optionalCategories": [
      {
        "id": "J4-BM4-ST4-B2",
        "label": "Planned Investment Contribution",
        "minimum": 0,
        "maximum": 10000
      },
      {
        "id": "J4-BM4-ST4-B3",
        "label": "Keep as Accessible Cash",
        "minimum": 0,
        "maximum": 10000
      },
      {
        "id": "J4-BM4-ST4-B4",
        "label": "Emergency-Fund Top-Up",
        "minimum": 0,
        "maximum": 10000
      }
    ],
    "remainingBalanceRule": "10000_minus_all_allocations",
    "overspendingBehaviour": "block_confirmation",
    "multipleValidBudgets": true,
    "scoringRules": [
      "Cover required debt repayment first.",
      "Reward an affordable contribution or a clear pause reason.",
      "Do not reward investing emergency money or borrowing."
    ],
    "validationRules": [
      "Total allocations must equal Rs. 10,000.",
      "Required debt repayment must be covered.",
      "No category may be negative.",
      "Emergency withdrawals are outside the budget."
    ]
  },
  "startingNode": {
    "id": "J4-BM4-ST4-N1",
    "question": "How should the monthly plan respond to the decline?"
  },
  "terminalOutcomes": [
    "affordable_regular_contribution",
    "paused_for_clear_reason",
    "emergency_money_invested",
    "borrowed_more_to_invest"
  ],
  "educationalAssumptions": [
    "Investing emergency money uses Rs. 50,000 once.",
    "Borrowing Rs. 50,000 creates ten classroom repayments of Rs. 5,000.",
    "No interest rate or fee is invented.",
    "Lower prices do not guarantee profit."
  ]
}
```

## Available Choices

### Continue the affordable planned contribution

**Classification:** potentially_reasonable  
**Reason:** The plan is affordable, emergency savings are protected, and required debt payments are covered.  
**Immediate financial effect:** The valid amount after debt repayment becomes the monthly contribution.  
**Feedback:** Regular investing reduces dependence on one perfect entry point but does not guarantee profit.  
**Short-term consequence:** Contributions continue at Rs. 0–10,000.  
**Later consequence:** Five-year totals use the confirmed amount.

### Pause contributions for a clear affordability reason

**Classification:** depends_on_situation  
**Reason:** Pausing may fit changed expenses, debt, emergency readiness, or goals.  
**Immediate financial effect:** No new money is invested this month.  
**Feedback:** Pausing can be reasonable when circumstances changed; fear alone is weaker reasoning.  
**Short-term consequence:** Unused money stays accessible after debt payments.  
**Later consequence:** Five-year contributions are lower.

### Invest Rs. 50,000 of emergency money

**Classification:** high_risk  
**Reason:** Emergency protection is exchanged for uncertain market exposure.  
**Immediate financial effect:** Emergency savings fall and the portfolio rises by Rs. 50,000.  
**Feedback:** A later surprise may force debt or an investment sale.  
**Short-term consequence:** Emergency readiness weakens.  
**Later consequence:** The Year 2 emergency has fewer protected options.

### Borrow Rs. 50,000 to invest

**Classification:** high_risk  
**Reason:** Repayment is certain while investment performance is uncertain.  
**Immediate financial effect:** Debt and the portfolio each rise by Rs. 50,000.  
**Feedback:** Lower prices do not guarantee profit; the loan still requires repayment.  
**Short-term consequence:** Monthly debt payments rise by Rs. 5,000.  
**Later consequence:** The Year 2 emergency and contributions face more pressure.

## Recommended Decision Logic

**Generally strongest:** Continue an affordable contribution only after required repayments are covered and emergency savings remain protected.

**Other reasonable paths:**
- Pausing is reasonable when income, expenses, debt, emergency readiness, or goals changed.
- Continuing at a smaller amount is reasonable when debt repayment reduces the budget.

**Trade-off:** Continuing adds market exposure at several prices; pausing preserves cash but slows contributions.

## Updated State Screen

**Title:** Contribution Plan Updated

- **regular_monthly_contribution:** 10000 → confirmed_budget.planned_investment. Debt repayment and affordability determine the contribution.
- **emergency_fund:** before_choice → after_choice. Emergency money changes only through top-up, genuine use, or misuse.
- **debt_balance:** before_choice → after_choice. Borrowing adds repayment pressure.

**Learning message:** Regular investing should remain affordable and separate from emergency money.

**Next teaser:** Explore three five-year paths and a real Year 2 emergency.

## Retry Behaviour
Invalid budgets must be revised. Risky but valid emergency-fund and borrowing choices may continue.

## Accessibility Alternative
Use plus and minus buttons followed by labelled decision options. Build the Rs. 10,000 plan, then choose the contribution response.

# Stage 5 — Five-Year Uncertainty

**Stage ID:** J4-BM4-ST5  
**Timeline:** Years 1–5  
**Concepts:** long_term_investing, regular_investing, emergency_savings_protection, diversification, emotional_control  
**Interaction:** timeline_slider_investment_simulator_decision_tree

## Situation
Move through three possible five-year market paths. In Year 2, a genuine Rs. 40,000 household emergency occurs. All balances reflect earlier choices.

## Learner Objective
Separate contributions from market movement, handle the emergency, and finish with a reviewed—not guaranteed—long-term plan.

## Interaction Configuration
```json
{
  "timelineSlider": {
    "startingTime": "initial_decline",
    "endingTime": "year_5",
    "sliderSteps": [
      "initial_decline",
      "year_1",
      "year_2",
      "year_3",
      "year_4",
      "year_5"
    ],
    "valuesShownAtEachPoint": [
      "investment_balance",
      "total_additional_contributions",
      "realised_losses",
      "unrealised_gain_loss",
      "emergency_fund",
      "debt_balance",
      "portfolio_concentration_level"
    ],
    "milestones": [
      {
        "step": "initial_decline",
        "event": "Portfolio is 25% below its original value."
      },
      {
        "step": "year_2",
        "event": "A genuine Rs. 40,000 household emergency occurs."
      },
      {
        "step": "year_5",
        "event": "Review the final range and decision dashboard."
      }
    ],
    "contributions": "Monthly contributions are grouped into annual totals and added after that year’s market movement.",
    "comparisonData": "Each path uses the same learner decisions. Only fictional market movement changes."
  },
  "investmentSimulator": {
    "startingBalanceSource": "current_investment_balance",
    "availableAssets": [
      "fictional_long_term_portfolio"
    ],
    "simulationPeriodYears": 5,
    "educationalAssumptions": [
      "All three paths are fictional and are not forecasts.",
      "Annual contributions equal the confirmed monthly amount multiplied by twelve.",
      "Contributions are added after each year’s market movement for classroom simplicity.",
      "No fees, taxes, dividends, or inflation are added.",
      "A lucky path does not improve the decision score."
    ],
    "possibleFluctuations": [
      {
        "id": "J4-BM4-PATH-A",
        "label": "Path A — Gradual Recovery",
        "annualReturnPercents": [
          5,
          6,
          7,
          6,
          5
        ],
        "explanation": "The portfolio improves over several years, but this is only one possibility."
      },
      {
        "id": "J4-BM4-PATH-B",
        "label": "Path B — Uneven Recovery",
        "annualReturnPercents": [
          -10,
          12,
          -5,
          10,
          4
        ],
        "explanation": "The portfolio rises, falls again, and later stabilises unevenly."
      },
      {
        "id": "J4-BM4-PATH-C",
        "label": "Path C — Continued Weakness",
        "annualReturnPercents": [
          -15,
          -6,
          5,
          -4,
          2
        ],
        "explanation": "Prices remain weak for years and some investments do not recover."
      }
    ],
    "concentrationAdjustments": [
      {
        "level": "broadly_spread",
        "weakPathAdjustmentPercent": 0
      },
      {
        "level": "moderately_concentrated",
        "weakPathAdjustmentPercent": -3
      },
      {
        "level": "highly_concentrated",
        "weakPathAdjustmentPercent": -8
      }
    ],
    "contributions": "annual_contribution_equals_monthly_contribution_times_12",
    "withdrawals": [
      "year_2_emergency_investment_withdrawal",
      "sales_from_earlier_stages"
    ],
    "fees": 0,
    "outcomeExplanation": "Final value separates remaining opening balance, additional contributions, withdrawals, and fictional market movement.",
    "requiredDisclaimer": "These paths are fictional. Long-term investing provides more time for possible growth, but recovery, profit, and lower losses are not guaranteed.",
    "calculationRules": {
      "annualContribution": "regular_monthly_contribution_multiplied_by_12",
      "yearEndBalance": "opening_balance_multiplied_by_one_plus_annual_return_then_plus_annual_contribution",
      "unrealisedGainLoss": "final_balance_minus_remaining_cost_basis",
      "decisionScoreIndependentOfPath": true
    }
  },
  "prediction": {
    "id": "J4-BM4-ST5-P1",
    "question": "After viewing all three paths, which conclusion is most accurate?",
    "options": [
      {
        "id": "J4-BM4-ST5-P1-O1",
        "label": "Waiting always restores every loss",
        "isPreferred": false,
        "feedback": "Path C shows that weakness can continue and some investments may never recover."
      },
      {
        "id": "J4-BM4-ST5-P1-O2",
        "label": "Selling always prevents worse results",
        "isPreferred": false,
        "feedback": "Selling may avoid later losses or miss later gains; review is still needed."
      },
      {
        "id": "J4-BM4-ST5-P1-O3",
        "label": "Several outcomes are possible, so the plan still needs review",
        "isPreferred": true,
        "feedback": "Correct. Time helps planning, but it does not guarantee a result."
      }
    ],
    "likelyEducationalOutcome": "The learner accepts uncertainty without assuming guaranteed recovery.",
    "explanation": "Long-term investing still requires review of quality, goals, affordability, and risk."
  },
  "finalEmergency": {
    "amount": 40000,
    "timing": "year_2",
    "purpose": "essential_household_repair"
  }
}
```

## Available Choices

### Use the emergency fund for the repair

**Classification:** recommended  
**Reason:** The money was kept accessible for genuine unexpected needs.  
**Immediate financial effect:** The emergency fund falls by Rs. 40,000.  
**Feedback:** The repair is funded without a weak-market sale or new debt.  
**Short-term consequence:** Emergency savings need rebuilding.  
**Later consequence:** The investment plan can continue according to affordability.

### Use Rs. 30,000 cash and pause one Rs. 10,000 contribution

**Classification:** reasonable  
**Reason:** Accessible money covers the emergency without debt when enough cash exists.  
**Immediate financial effect:** Cash falls and one contribution is redirected.  
**Feedback:** The emergency is funded without debt.  
**Short-term consequence:** Total contributions fall by Rs. 10,000.  
**Later consequence:** The final investment value may be lower while emergency savings remain intact.

### Sell Rs. 40,000 of investments after review

**Classification:** depends_on_situation  
**Reason:** A reviewed sale may be necessary when accessible resources are insufficient.  
**Immediate financial effect:** Rs. 40,000 is withdrawn from the portfolio.  
**Feedback:** The repair is funded, but part of the investment is sold during uncertainty.  
**Short-term consequence:** Less money remains invested.  
**Later consequence:** Any loss on the sold portion becomes realised.

### Borrow Rs. 40,000 for the repair

**Classification:** risky  
**Reason:** Debt adds pressure and may be avoidable if emergency savings were protected.  
**Immediate financial effect:** Debt rises by Rs. 40,000.  
**Feedback:** Borrowing may be necessary when accessible money is insufficient.  
**Short-term consequence:** Monthly debt pressure increases.  
**Later consequence:** Future contributions may need to fall.

## Recommended Decision Logic

**Generally strongest:** Use protected emergency savings for a genuine emergency when available, then rebuild them without assuming a market path.

**Other reasonable paths:**
- Accessible cash plus a temporary contribution pause is reasonable when enough cash exists.
- A reviewed sale or necessary borrowing may be required when protected resources are insufficient.

**Trade-off:** Protecting investments may reduce cash or emergency savings; protecting cash may require a sale, pause, or debt.

## Updated State Screen

**Title:** Five-Year Simulation Complete

- **final_investment_balance:** balance_at_initial_decline → selected_path.final_balance. Market movement, contributions, sales, and concentration affect final value.
- **total_additional_contributions:** 0 → sum_of_confirmed_contributions. Contributions are separate from market movement.
- **emergency_fund:** before_year_2 → after_year_2_choice. The genuine emergency uses protected money only when selected.
- **debt_balance:** before_year_2 → after_year_2. Borrowing creates obligations independent of market performance.

**Learning message:** Long-term investing creates time for possible outcomes, not a guarantee of recovery.

**Next teaser:** Review the dashboard and see which decisions—not luck—shaped the score.

## Retry Behaviour
Insufficient choices must be revised. Risky feasible choices may continue. Replaying a path does not change the decision score.

## Accessibility Alternative
Use Previous and Next buttons for years and paths, followed by labelled emergency choices. Hear balances, contributions, losses, emergency savings, debt, and concentration at every point.

# 10. Connected Consequence Rules

| Earlier Decision | Persistent Value | Later Stage | Later Consequence | Educational Purpose |
| --- | --- | --- | --- | --- |
| J4-BM4-ST1-C1 | realised_losses | J4-BM4-ST5 | The Rs. 50,000 decline remains realised and later paths affect only new contributions. | Separate a sale decision from later market luck. |
| J4-BM4-ST1-C3 | monthly_debt_payment | J4-BM4-ST4 | Rs. 5,000 of the monthly contribution budget must cover debt repayment first. | Show that investment debt reduces future flexibility. |
| J4-BM4-ST2-C1 | emotional_decision_score | J4-BM4-COMPLETE | Final feedback highlights reliance on another person’s prediction. | Connect social pressure with emotional decisions. |
| J4-BM4-ST3-C2 | portfolio_concentration_level | J4-BM4-ST5 | Weak paths receive a larger concentration adjustment. | Show how one-company dependence can magnify outcomes. |
| J4-BM4-ST4-C3 | emergency_fund | J4-BM4-ST5 | The Year 2 emergency may require cash, a sale, or debt. | Show that emergency money and long-term investments have different purposes. |
| J4-BM4-ST4-C1 | total_additional_contributions | J4-BM4-ST5 | Affordable contributions purchase at several prices. | Connect regular investing with contributions rather than guaranteed profit. |

# 11. Interaction-Specific Requirements

- **Decision Tree:** Stages 1, 2, 4, and 5 define choices, consequences, state changes, and context-sensitive outcomes.
- **Predict Outcome:** Stages 2 and 5 separate opinion from evidence and uncertain paths from guarantees.
- **Before vs After:** Stage 3 compares two Rs. 200,000 portfolios and the hidden concentration difference.
- **Budget Builder:** Stage 4 allocates a Rs. 10,000 monthly budget after required debt repayment.
- **Timeline Slider and Investment Simulator:** Stage 5 shows three fictional paths, contributions, withdrawals, and market movement separately.

# 12. Mid-Mission Checkpoint

**Title:** Crash Checkpoint

**Current Financial Summary:**

- investmentBalanceSource: current_investment_balance
- cashSource: cash_outside_portfolio
- realisedLossesSource: realised_losses
- unrealisedGainLossSource: unrealised_gain_loss
- debtSource: debt_balance
- concentrationSource: portfolio_concentration_level
- emotionalDecisionScoreSource: emotional_decision_score

**Positive feedback rules:**

- reviewed_before_acting: You created space for evidence before making a permanent decision.
- social_pressure_rejected: You did not treat another person’s prediction as certainty.

**Emerging risk rules:**

- debt_balance_above_zero: Investment debt is already reducing future flexibility.
- portfolio_concentration_level_equals_highly_concentrated: The portfolio remains heavily dependent on one outcome.
- current_investment_balance_equals_zero: The original portfolio cannot participate in later movement.

**Reflection:** Continue to the contribution decision, or review an earlier crash response?

**Primary Button:** Plan the Contribution  
**Review Button:** Review My Decisions

# 13. Final Combined Challenge

**Title:** The Year 2 Emergency

**Situation:** During uncertain market conditions, an essential Rs. 40,000 household repair occurs. The strongest available choice depends on whether emergency savings, cash, investments, and debt were protected earlier.

**Concepts Combined:** emergency_savings_protection, long_term_investing, regular_investing, responsible_debt, emotional_control

**Interaction:** timeline_slider_investment_simulator_decision_tree

**Recommended Reasoning:** Use protected emergency money when available. Otherwise compare accessible cash, a temporary contribution pause, a reviewed sale, and necessary borrowing without assuming recovery.

# 14. Concept Reveal and Debrief

**Title:** The Crash Did Not Decide Everything

You faced a sharp decline, confident predictions, concentration risk, a contribution decision, three possible market paths, and a genuine emergency. The fall did not prove permanent failure, but it also did not guarantee recovery. Reviewing the goal and investment quality separated evidence from fear or hope. Diversification reduced dependence on one outcome without preventing loss. Affordable regular contributions added money at several prices, while emergency savings and debt changed your flexibility. Selling, pausing, or remaining invested may each be reasonable after review. The strongest behaviour was not predicting the market—it was protecting essential money and making informed decisions.

**Suggested Visual:** A market chart branches into three paths beside a review checklist, emergency shield, and debt meter.

**Explain It Simply:** Review first, protect emergency money, and accept uncertainty without panic or guaranteed-recovery assumptions.

# 15. Performance Scoring System

**Maximum Score:** 100

## Emotional Decision-Making — 25 points

**Decisions:** J4-BM4-ST1, J4-BM4-ST2, J4-BM4-ST5

**Positive Rules:**

- 25 for evidence-based review and uncertainty awareness.
- 18 for mostly thoughtful choices with one emotional assumption.
- 8 for one panic sale or guaranteed-recovery assumption.
- 0 for repeated prediction-led decisions.

**Deductions:**

- 8 for selling solely from a friend’s prediction.
- 8 for assuming guaranteed recovery.
- 10 for borrowing mainly to recover losses.

**Minimum:** 0

**Learner Explanation:** Measures whether evidence, fear, hope, or social pressure guided the response.

## Diversification — 20 points

**Decisions:** J4-BM4-ST3, J4-BM4-ST5

**Positive Rules:**

- 20 for correct comparisons and reducing extreme concentration.
- 14 for correct understanding while knowingly keeping concentration.
- 6 for expecting diversification to prevent every loss.
- 0 for ignoring concentration.

**Deductions:**

- 5 for selling solely because the diversified example also declined.

**Minimum:** 0

**Learner Explanation:** Measures understanding of concentration reduction without treating diversification as protection from all loss.

## Emergency Savings Protection — 20 points

**Decisions:** J4-BM4-ST4, J4-BM4-ST5

**Positive Rules:**

- 20 for protecting emergency money until the genuine emergency.
- 16 for using accessible cash and a temporary pause.
- 8 for a necessary reviewed investment sale.
- 4 for necessary borrowing.
- 0 for emergency-fund investing followed by avoidable debt.

**Deductions:**

- 12 for investing emergency money.
- 8 for avoidable emergency borrowing.

**Minimum:** 0

**Learner Explanation:** Measures whether emergency money remained accessible for its intended purpose.

## Long-Term Discipline — 20 points

**Decisions:** J4-BM4-ST1, J4-BM4-ST4, J4-BM4-ST5

**Positive Rules:**

- 20 for reviewing and following an affordable plan.
- 16 for pausing or reducing for a clear reason.
- 8 for inconsistent decisions without emergency misuse.
- 0 for repeated borrowing, panic, or ignoring affordability.

**Deductions:**

- 10 for abandoning the plan only because prices fell.
- 12 for borrowing to invest.
- 8 for ignoring the portfolio without review.

**Minimum:** 0

**Learner Explanation:** Measures whether the long-term plan stayed affordable, reviewed, and adaptable.

## Financial Adaptability — 15 points

**Decisions:** J4-BM4-ST1, J4-BM4-ST3, J4-BM4-ST4, J4-BM4-ST5

**Positive Rules:**

- 15 when later decisions fit actual cash, debt, emergency, and concentration state.
- 10 when one weak choice is corrected later.
- 5 when the plan works but creates avoidable pressure.
- 0 when later choices ignore the state created earlier.

**Deductions:**

- 5 for an unaffordable monthly allocation.
- 5 for an insufficient emergency funding source.

**Minimum:** 0

**Learner Explanation:** Measures whether the plan changed thoughtfully as conditions changed.

Market-path results are separated from decision quality.

# 16. Final Results Dashboard

## Realised Losses

- Starting: startingState.realisedLosses
- Final: realised_losses
- Change: final_minus_starting
- Status rules:
  - value_equals_zero: No Loss Realised
  - value_between_1_and_50000: Developing
  - value_above_50000: Needs Attention
- Explanation: Shows losses locked in through sales below cost.

## Remaining Portfolio Value

- Starting: startingState.investmentBalance
- Final: selected_simulated_path.final_investment_balance
- Change: final_minus_post_decline_start
- Contributions: total_additional_contributions
- Market movement: final_balance_minus_remaining_opening_balance_minus_contributions_plus_withdrawals
- Status rules:
  - decision_quality_strong_regardless_of_value: Plan Followed Thoughtfully
  - portfolio_zero_after_reviewed_sale: Exited After Review
  - portfolio_zero_after_panic_sale: Emotionally Influenced
- Explanation: Separates contributions, withdrawals, and fictional market movement.

## Total Contributions

- Starting: startingState.additionalContributions
- Final: total_additional_contributions
- Change: final_total_contributions
- Status rules:
  - affordable_plan_followed: Consistent
  - paused_for_clear_reason: Adapted
  - stopped_only_from_fear: Needs Review
- Explanation: Shows new money separately from investment growth or decline.

## Emergency Savings Protected

- Starting: startingState.emergencyFund
- Final: emergency_fund
- Change: final_minus_starting
- Status rules:
  - protected_until_genuine_emergency: Fully Protected
  - partly_invested_or_used: Partially Protected
  - below_40000_before_emergency: At Risk
  - value_equals_zero: Depleted
- Explanation: Shows whether emergency money stayed accessible until a genuine need.

## Debt Created

- Starting: startingState.debtBalance
- Final: debt_balance
- Change: final_minus_starting
- Secondary value: monthly_debt_payment
- Status rules:
  - value_equals_zero: Strong
  - necessary_emergency_debt: Managed
  - investment_debt_above_zero: At Risk
- Explanation: Separates necessary emergency borrowing from debt used to chase losses.

## Emotional Decision Score

- Starting: startingState.emotionalDecisionScore
- Final: emotional_decision_score
- Change: final_minus_starting
- Status rules:
  - value_greater_than_or_equal_to_80: Calm and Informed
  - value_between_60_and_79: Mostly Thoughtful
  - value_between_35_and_59: Emotionally Influenced
  - value_below_35: Highly Reactive
- Explanation: Measures whether evidence, fear, hope, or social pressure guided decisions.

## Diversification Score

- Starting: startingState.diversificationScore
- Final: diversification_score
- Change: final_minus_starting
- Status rules:
  - value_greater_than_or_equal_to_80: Broadly Spread
  - value_between_50_and_79: Moderately Concentrated
  - value_below_50: Highly Concentrated
- Explanation: A stronger score reduces dependence on one outcome but does not make the portfolio loss-free.

## Long-Term Discipline Score

- Starting: startingState.longTermDisciplineScore
- Final: long_term_discipline_score
- Change: final_minus_starting
- Status rules:
  - value_greater_than_or_equal_to_80: Strong
  - value_between_60_and_79: Stable
  - value_between_35_and_59: Developing
  - value_below_35: Needs Attention
- Explanation: Measures affordable contributions, review, emergency protection, and avoidance of investment debt.

## Financial Confidence Score

- Starting: 0
- Final: final_score
- Change: final_score
- Status rules:
  - 0_to_39: Crash Response At Risk
  - 40_to_69: Building Market Discipline
  - 70_to_89: Financially Prepared
  - 90_to_100: Strong Crash Discipline
- Explanation: Rewards decision quality rather than the luckiest fictional market path.

# 17. Performance Levels

| Score | Level | Description |
| --- | --- | --- |
| 0–39 | Crash Response At Risk | The plan created major emotional, debt, concentration, or emergency-fund pressure. |
| 40–69 | Building Market Discipline | Some decisions were thoughtful, but important risk, emergency, or affordability habits need work. |
| 70–89 | Financially Prepared | The learner balanced review, diversification, emergency protection, and long-term planning effectively. |
| 90–100 | Strong Crash Discipline | The learner consistently made informed and adaptable decisions. This does not guarantee recovery or future wealth. |

# 18. Personalised Final Feedback

## Performance Headlines

- score_90_to_100: You stayed thoughtful through uncertainty.
- score_70_to_89: Your crash plan remained mostly balanced.
- score_40_to_69: Your plan has a foundation, with pressure points to improve.
- score_0_to_39: The crash exposed important planning risks.
## Strengths

- reviewed_before_acting: You reviewed the goal and portfolio before making a permanent change.
- emergency_fund_protected_until_year_2: You kept emergency money available for a genuine household need.
- diversification_score_at_least_80: You reduced dependence on one company or sector without assuming losses were impossible.
- affordable_contribution_followed: You adjusted contributions according to affordability rather than fear alone.
## Improvements

- panic_or_social_pressure_sale: A sale was driven mainly by fear or another person’s prediction. Review the goal and quality first.
- investment_debt_above_zero: Borrowing increased certain repayment pressure while market results remained uncertain.
- emergency_money_invested: Using emergency money reduced the protected options available when a real emergency arrived.
- assumed_guaranteed_recovery: Remaining invested may fit the plan, but guaranteed recovery is not a reliable reason.
## Trade-Offs

- sold_after_review: Selling reduced future market exposure but locked in the current loss.
- regular_contributions_continued: Regular contributions purchased at several prices but increased market exposure.
- contributions_paused_for_clear_reason: Pausing protected cash and affordability but reduced long-term contributions.
- emergency_fund_used_for_genuine_emergency: The repair was funded without an investment sale, but emergency savings now need rebuilding.

**Practical Principle:** Review first, protect emergency money, and let affordability—not fear or guaranteed recovery—shape the plan.

**Replay Invitation:** Replay with another first response or contribution plan to compare realised losses, debt, and emergency options.

# 19. Boss Mission Quiz

## J4-BM4-Q1 — combined_recognition

**Question:** Which response combines volatility awareness and long-term planning?

- Sell because the decline feels permanent: A feeling does not prove permanent failure.
- Review the goal, portfolio quality, and need for the money **(Correct)**: Correct. The choice uses both the price movement and the original plan.
- Borrow because prices are lower: Lower prices do not guarantee profit while debt still requires repayment.
- Assume every investment will recover: Some investments may remain weak or permanently lose value.

**Correct Explanation:** Reviewing connects volatility with quality, time horizon, and purpose.

**Concepts Tested:** volatility, long_term_investing, emotional_control

**Misconception:** A major decline automatically proves permanent failure.

## J4-BM4-Q2 — combined_misconception

**Question:** A diversified portfolio falls during a crash. What does this prove?

- Diversification failed completely: Diversification reduces dependence on one outcome; it does not promise zero loss.
- The portfolio must recover: Recovery is possible but not guaranteed.
- Diversification cannot remove all market risk **(Correct)**: Correct. Several holdings may still decline together.
- All holdings should be sold immediately: Selling should follow a review of the goal and investments.

**Correct Explanation:** Diversification may reduce concentration risk while the portfolio still loses value.

**Concepts Tested:** diversification, volatility, risk

**Misconception:** Diversification prevents all losses during a crash.

## J4-BM4-Q3 — new_application

**Question:** A long-term investment falls 20%, and a medical bill is due. The person has emergency savings and no debt. What is the strongest first response?

- Borrow to avoid touching emergency savings: Emergency savings exist for genuine unexpected needs; borrowing creates repayment pressure.
- Use emergency savings and review the investment separately **(Correct)**: Correct. The urgent need and long-term investment have different purposes.
- Invest the emergency savings at the lower price: This removes accessible money when a genuine emergency already exists.
- Sell everything because the bill appeared: The investment can be reviewed separately when emergency money covers the bill.

**Correct Explanation:** Emergency savings cover the urgent need while the investment remains a separate evidence-based decision.

**Concepts Tested:** emergency_savings, long_term_investing, emotional_control

**Misconception:** Investment money and emergency money should be treated as the same resource.

# 20. Boss Mission Completion

**Headline:** Crash Plan Completed!

**Achievement:** You managed a major decline by balancing evidence, diversification, affordability, emergency protection, and long-term uncertainty.

**Score:** Dynamic 0–100  
**Performance Level:** Dynamic  
**Concepts Mastered:** Dimensions at or above 70%  
**Concept Needing Practice:** Lowest-scoring dimension  
**XP Reward:** 225 XP

**Journey Progress:** Journey Boss complete in Grow Wealth Wisely.

**Next Teaser:** Next, use these habits to recognise pressure, scams, and decision traps.

**Animation:** A falling chart branches into three paths while a checklist, emergency shield, and diversified portfolio remain visible.

**Replay Button:** Try Another Crash Plan  
**Continue Button:** Continue Journey

# 21. Real-Life Challenge

**Title:** Write a Crash Checklist

**Instruction:** Write four questions you would ask before changing a fictional long-term investment after a price decline. Do not invest, sell, or share private financial information.

**Button:** My Checklist Is Ready

# 22. Content Safety and Accuracy Review

| Review Item | Status | Notes |
| --- | --- | --- |
| Reviews only previously taught concepts | PASS | Uses J4-M21, J4-M23, J4-M24, J4-M25, and J4-M26 concepts. |
| Does not introduce unexplained major concepts | PASS | Realised loss, diversification, contributions, and emergency protection are explained in context. |
| Concepts are combined accurately | PASS | Volatility, concentration, contributions, planning, and emergency savings affect one scenario. |
| Financial amounts are internally consistent | PASS | The initial 25% decline equals Rs. 50,000; borrowing and emergency values reconcile. |
| Persistent values update correctly | PASS | Investments, cash, debt, losses, concentration, and emergency money carry forward. |
| Earlier decisions affect later stages | PASS | Sales, borrowing, concentration, and emergency-fund use change later options. |
| Interaction choices have meaningful consequences | PASS | Each major choice changes state, scoring, or later choices. |
| Multiple reasonable paths are allowed where appropriate | PASS | Reviewed selling, pausing, continuing, cash use, and necessary borrowing may be defensible. |
| Financially accurate | PASS | No recovery, profit, or loss-reduction guarantee is made. |
| Appropriate for the target age | PASS | Uses adult savings, debt, emergencies, and long-term goals. |
| Difficulty is Easy | PASS | Uses simple amounts, percentages, and direct consequences. |
| No personalised investment advice | PASS | All holdings and paths are fictional educational examples. |
| No guaranteed return claims | PASS | Regular contributions and long-term investing remain uncertain. |
| No stock-price predictions | PASS | The three paths are fictional simulations. |
| No claims that markets always recover | PASS | The continued-weakness path directly rejects guaranteed recovery. |
| Simulated results are not presented as forecasts | PASS | Decision quality is separate from fictional market paths. |
| No shaming around money | PASS | Risky choices receive calm feedback. |
| No misleading oversimplification | PASS | Selling, pausing, borrowing, and staying invested are contextual. |
| Scenario is culturally understandable | PASS | Uses PKR, household emergencies, debt, and long-term planning. |
| Interactions reinforce the learning objective | PASS | All five stages apply crash-response skills. |
| Scoring rewards decision quality rather than luck | PASS | The selected path cannot increase the decision score. |
| Enjoyable spending is not automatically treated as irresponsible | NOT APPLICABLE | The scenario focuses on investment and emergency decisions. |
| Risk-taking is not automatically rewarded | PASS | Borrowing and emergency-fund investing reduce the score. |
| Quiz corrects the combined misconception | PASS | The quiz addresses permanent failure, diversification, and emergency-money purpose. |
| Mission can be completed within the specified duration | PASS | Five compact stages, a checkpoint, dashboard, and quiz fit nine minutes. |
| Language matches the target reading level | PASS | Uses clear adult beginner language. |
| Accessibility alternatives are provided | PASS | Every interaction includes labelled non-gesture controls. |
| Final dashboard matches the simulation outcomes | PASS | Every dashboard item references tracked state or formulas. |
| JSON matches the human-readable version | PASS | Both artifacts are generated from the same mission data. |
