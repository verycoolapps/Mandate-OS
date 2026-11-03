# Opportunity Cost Engine

## PURPOSE

The Opportunity Cost Engine ensures that every resource allocation decision acknowledges what cannot be done as a result. It answers the critical question: "If we do X, what must we NOT do?"

---

## CORE PHILOSOPHY

**Resources are finite. Every choice excludes other choices.**

Opportunity cost is the value of the next best alternative foregone. Professional decision-making requires:

1. Explicit acknowledgment that choosing A means not choosing B
2. Quantification (where possible) of what is sacrificed
3. Assessment of whether the chosen option provides superior value
4. Consideration of timing constraints and resource windows

**The Opportunity Cost Engine prevents:**
- Optimistic resource planning that assumes unlimited capacity
- Ignoring the value of alternatives not chosen
- Failing to account for what could have been achieved
- Resource overcommitment without recognizing consequences

---

## OPPORTUNITY COST DIMENSIONS

### 1. Financial Opportunity Cost
**Money spent here cannot be spent elsewhere**

**Examples:**
- Investing $1M in Product A means not investing $1M in Product B
- Hiring 5 engineers means not hiring 5 salespeople
- Building in-house means not buying a solution
- Marketing spend on Channel A means not spending on Channel B

**Calculation:**
- Explicit: Compare expected returns of alternatives
- Implicit: Estimate expected value of foregone opportunities

### 2. Time Opportunity Cost
**Time spent here cannot be spent elsewhere**

**Examples:**
- 3 months on Project A means 3 months not on Project B
- Executive attention on Strategy X means not on Strategy Y
- Team capacity on Maintenance means not on New Features
- Quarter spent on Integration means not on Innovation

**Calculation:**
- Calendar time: What could be achieved in the same period?
- Attention time: What strategic focus is sacrificed?
- Window time: Is this a time-sensitive opportunity being missed?

### 3. Talent Opportunity Cost
**People assigned here cannot be assigned elsewhere**

**Examples:**
- Senior engineer on refactoring means not on new product
- Designer on marketing means not on product UX
- Sales lead on Enterprise means not on SMB
- Executive on acquisition means not on organic growth

**Calculation:**
- Skill-specific opportunity: What is this person uniquely capable of?
- Team capacity: What other work could this team do?
- Talent development: What growth opportunities are foregone?

### 4. Strategic Opportunity Cost
**Strategic focus here means not elsewhere**

**Examples:**
- Geographic expansion means not product expansion
- Enterprise focus means not SMB focus
- Horizontal integration means not vertical
- Cost leadership means not differentiation

**Calculation:**
- Market opportunity: What market segments are being ignored?
- Competitive positioning: What competitive advantages are not pursued?
- Option value: What strategic options are being closed?

### 5. Innovation Opportunity Cost
**Innovation here means not innovation elsewhere**

**Examples:**
- Technology investment in AI means not in blockchain
- Product innovation in mobile means not in web
- Process innovation in automation means not in human-centric design
- Business model innovation in subscription means not in marketplace

**Calculation:**
- Technology stack: What technologies are not being explored?
- Product innovation: What product directions are not pursued?
- Business model: What monetization approaches are not tested?

---

## OPPORTUNITY COST ANALYSIS PROTOCOL

### Step 1: Identify Resource Commitment
**What is being allocated?**

Document the resource being committed:
- **Financial:** Amount, timing, recurring vs. one-time
- **Time:** Duration, person-hours, calendar window
- **Talent:** Who, how many, what skills, what duration
- **Strategic:** What focus, what positioning, what market
- **Capacity:** What percentage of total resources

### Step 2: Identify Alternatives
**What else could this resource be used for?**

Generate alternative uses:
- **Direct alternatives:** Similar initiatives competing for same resources
- **Indirect alternatives:** Different initiatives that could use these resources
- **Deferral alternatives:** Doing this later vs. now
- **Non-investment alternatives:** Not investing at all (saving resources)

**For each alternative:**
- Description of alternative
- Expected value/benefit
- Resource requirements
- Timing considerations
- Risk profile

### Step 3: Calculate Opportunity Cost
**What is the value of the best foregone alternative?**

**Quantitative Approach (when possible):**
- Expected monetary value of best alternative
- Expected strategic value of best alternative
- Expected learning value of best alternative
- Expected risk reduction of best alternative

**Qualitative Approach (when quantification not possible):**
- High/Medium/Low value assessment
- Strategic importance assessment
- Fit with organizational priorities
- Urgency assessment

### Step 4: Compare Chosen vs. Foregone
**Is the chosen option superior to the best alternative?**

**Comparison Framework:**

| Dimension | Chosen Option | Best Alternative | Comparison |
|-----------|--------------|-----------------|------------|
| Expected Return | [Value] | [Value] | [Better/Worse/Similar] |
| Time to Value | [Timeline] | [Timeline] | [Faster/Slower/Similar] |
| Risk Profile | [Level] | [Level] | [Lower/Higher/Similar] |
| Strategic Fit | [Score] | [Score] | [Better/Worse/Similar] |
| Resource Efficiency | [Score] | [Score] | [Better/Worse/Similar] |
| **Overall** | **[Score]** | **[Score]** | **[Decision]** |

### Step 5: Document Opportunity Cost Statement
**Explicitly state what is being sacrificed**

**Format:**
"By allocating [resource] to [chosen option], we are foregoing [best alternative], which would have provided [expected value]. This is justified because [rationale]."

**Example:**
"By allocating $500,000 and 3 months to build a custom CRM, we are foregoing purchasing Salesforce, which would cost $300,000 upfront and be operational in 1 month. This is justified because the custom CRM will provide unique competitive differentiation and avoid $100,000/year in licensing fees, with a break-even at 18 months."

### Step 6: Identify Reversibility
**Can this decision be reversed?**

**Reversibility Assessment:**
- **Fully reversible:** Can be undone with minimal cost
- **Partially reversible:** Can be changed but with significant cost
- **Irreversible:** Cannot be undone or cost is prohibitive

**For irreversible decisions:**
- What makes it irreversible?
- What is the cost of being wrong?
- Is the opportunity cost acceptable given irreversibility?

---

## OPPORTUNITY COST CALCULATION METHODS

### Method 1: Expected Value Comparison
**When alternatives have quantifiable expected returns**

**Formula:**
```
Opportunity Cost = Expected Value of Best Foregone Alternative
Net Benefit = Expected Value of Chosen Option - Opportunity Cost
```

**Example:**
- Chosen Option: Expected value $1M
- Best Alternative: Expected value $700K
- Opportunity Cost: $700K
- Net Benefit: $300K

### Method 2: Return on Investment Comparison
**When comparing investments with different ROIs**

**Formula:**
```
ROI Chosen = (Return Chosen - Cost Chosen) / Cost Chosen
ROI Alternative = (Return Alternative - Cost Alternative) / Cost Alternative
Opportunity Cost = Cost Chosen × ROI Alternative
```

**Example:**
- Chosen: $500K investment, $750K return → ROI = 50%
- Alternative: $500K investment, $600K return → ROI = 20%
- Opportunity Cost = $500K × 20% = $100K
- Net Benefit from choosing = $250K - $100K = $150K

### Method 3: Time-Value Comparison
**When timing differences matter**

**Formula:**
```
PV Chosen = Value Chosen / (1 + r)^t
PV Alternative = Value Alternative / (1 + r)^t
Opportunity Cost = PV Alternative
```

**Example:**
- Chosen: $1M in 2 years → PV = $1M / 1.1² = $826K
- Alternative: $800K in 1 year → PV = $800K / 1.1 = $727K
- Opportunity Cost = $727K
- Net Benefit = $826K - $727K = $99K

### Method 4: Scoring Comparison
**When quantification is not possible**

**Scoring Framework:**
1. Define evaluation criteria (5-7 dimensions)
2. Assign weights to criteria based on priorities
3. Score each option on each criterion (1-10)
4. Calculate weighted scores
5. Opportunity cost = weighted score of best alternative

**Example:**

| Criterion | Weight | Chosen | Alternative |
|-----------|--------|--------|-------------|
| Strategic Fit | 30% | 8 | 7 |
| Financial Return | 25% | 7 | 6 |
| Risk Level | 20% | 6 | 8 |
| Time to Value | 15% | 5 | 9 |
| Resource Efficiency | 10% | 7 | 6 |
| **Weighted Score** | **100%** | **6.95** | **7.05** |

**Opportunity Cost:** 7.05 (Alternative has higher score)
**Decision:** Alternative may be superior

---

## COMMON OPPORTUNITY COST SCENARIOS

### Scenario 1: Build vs. Buy
**Build:**
- **Resource Commitment:** $500K, 6 months, 3 engineers
- **Opportunity Cost:** Could have purchased solution for $200K, deployed in 1 month, freed 3 engineers for other work
- **Analysis:** Build justified only if unique capabilities required or long-term savings exceed difference

### Scenario 2: Feature Prioritization
**Feature A:**
- **Resource Commitment:** 2 months, 1 engineer
- **Opportunity Cost:** Could have built Feature B in same time, which serves larger customer segment
- **Analysis:** Feature A justified only if customer value or strategic importance exceeds Feature B

### Scenario 3: Geographic Expansion
**Enter Market A:**
- **Resource Commitment:** $1M, 12 months, local team
- **Opportunity Cost:** Could have entered Market B with larger addressable market
- **Analysis:** Market A justified only if growth potential, competitive position, or strategic value exceeds Market B

### Scenario 4: Talent Allocation
**Assign Senior Engineer to Refactoring:**
- **Resource Commitment:** 3 months of senior engineer time
- **Opportunity Cost:** Could have led new product development, potentially generating $2M revenue
- **Analysis:** Refactoring justified only if technical debt risk or efficiency gains exceed $2M opportunity

### Scenario 5: Marketing Channel Investment
**Invest $100K in Channel A:**
- **Resource Commitment:** $100K marketing budget
- **Opportunity Cost:** Could have invested in Channel B with higher conversion rate
- **Analysis:** Channel A justified only if expected CAC or LTV improvement exceeds Channel B

---

## OPPORTUNITY COST IN PORTFOLIO DECISIONS

### Portfolio Optimization
When allocating resources across multiple initiatives:

**Step 1:** List all potential initiatives with resource requirements and expected value
**Step 2:** Rank by expected value per unit of resource (ROI ratio)
**Step 3:** Select top initiatives until resources are exhausted
**Step 4:** Opportunity cost = sum of expected values of foregone initiatives

**Example:**

| Initiative | Resource Required | Expected Value | Value/Resource | Selected? |
|------------|-------------------|----------------|----------------|-----------|
| Initiative A | $100K | $300K | 3.0 | Yes |
| Initiative B | $200K | $400K | 2.0 | Yes |
| Initiative C | $150K | $300K | 2.0 | Yes |
| Initiative D | $100K | $150K | 1.5 | No |
| Initiative E | $50K | $50K | 1.0 | No |

**Total Budget:** $450K
**Selected:** A, B, C ($450K total)
**Opportunity Cost:** $150K (Initiative D) + $50K (Initiative E) = $200K

### Dynamic Opportunity Cost
Opportunity costs change over time:

**Time-Dependent Factors:**
- Market windows close
- Competitive dynamics shift
- Technology evolves
- Talent availability changes
- Strategic priorities adjust

**Re-evaluation Triggers:**
- Major market changes
- Competitive moves
- Technology breakthroughs
- Resource availability changes
- Strategic pivot

---

## OPPORTUNITY COST COMMUNICATION

### How to Present Opportunity Cost

**Good Presentation:**
- "By investing $500K in Project A, we are foregoing Project B, which would have generated $300K. Project A is justified because it aligns with our long-term strategy and has higher expected value over 3 years."

**Bad Presentation:**
- "We should invest $500K in Project A." (No opportunity cost mentioned)

### Stakeholder-Specific Communication

**For Executives:**
- Portfolio-level opportunity costs
- Strategic opportunity costs
- High-level resource trade-offs
- Long-term implications

**For Product/Engineering:**
- Feature-level opportunity costs
- Technical debt opportunity costs
- Capacity constraints
- Timeline implications

**For Finance:**
- Financial opportunity costs
- ROI comparisons
- Budget trade-offs
- Investment efficiency

---

## OPPORTUNITY COST PITFALLS

### Common Mistakes

**1. Ignoring Opportunity Cost Entirely**
- Presenting decisions without acknowledging alternatives
- Acting as if resources are unlimited
- Failing to consider what could have been done

**2. Overestimating Chosen Option**
- Optimism bias in expected returns
- Underestimating risks and costs
- Ignoring implementation challenges

**3. Underestimating Alternatives**
- Dismissing alternatives without proper analysis
- Failing to recognize value of foregone options
- Not considering deferred alternatives

**4. Fixed Resource Assumption**
- Assuming resources cannot be reallocated
- Not considering resource acquisition
- Ignoring resource optimization opportunities

**5. Single-Point Analysis**
- Not considering timing differences
- Ignoring sequencing possibilities
- Failing to consider portfolio effects

---

## INTEGRATION WITH OTHER CORE MODULES

- **Decision Intelligence Engine:** Uses opportunity cost in option evaluation
- **Trade-Off Analysis Engine:** Opportunity cost is a key trade-off dimension
- **Impact Analysis Framework:** Assesses impact of foregone alternatives
- **Risk Intelligence Framework:** Evaluates risks of choosing vs. alternatives
- **Evidence and Confidence Protocol:** Manages certainty in opportunity cost assessment

---

## STANDARDS

**OPPORTUNITY COST ENGINE**
- Every resource allocation decision includes opportunity cost analysis
- The best foregone alternative is identified and valued
- Opportunity cost is explicitly stated in recommendations
- Quantification is used where possible
- Qualitative assessment is structured where quantification is impossible
- Portfolio-level opportunity costs are considered for major decisions
- Opportunity costs are communicated clearly to stakeholders
- Reversibility is assessed for irreversible commitments
