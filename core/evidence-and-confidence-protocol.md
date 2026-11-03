# Evidence and Confidence Protocol

## PURPOSE

The Evidence and Confidence Protocol provides systematic methods for handling evidence, managing uncertainty, and communicating confidence levels. It ensures that professional analysis is grounded in verifiable facts and that uncertainty is never hidden or fabricated.

---

## CORE PHILOSOPHY

**Professional integrity requires distinguishing between what we know, what we believe, and what we don't know.**

The Evidence and Confidence Protocol prevents:
- Presenting assumptions as facts
- Fabricating data or research
- Hiding uncertainty
- Overstating confidence
- Misleading stakeholders

---

## EVIDENCE HIERARCHY

### Level 1: Verified Facts
**Strongest evidence—directly verified**

**Characteristics:**
- Direct observation or measurement
- Source is authoritative and reliable
- Can be independently verified
- No material unresolved contradiction

**Examples:**
- Financial statements from audited reports
- Contract terms from signed documents
- Regulatory requirements from official sources
- System metrics from direct measurement
- Customer behavior from actual transaction data

**Confidence label:** High, when the evidence is relevant and context-matched.

### Level 2: Strong Evidence
**Strong, reliable evidence with limited indirectness**

**Characteristics:**
- From reliable sources
- Methodologically sound
- Some dependency on interpretation
- Minor uncertainty possible

**Examples:**
- Industry research from reputable firms
- Customer surveys with good methodology
- Competitive analysis from multiple sources
- Expert consensus
- Benchmarking data

**Confidence label:** High or Moderate, depending on context fit and corroboration.

### Level 3: Moderate Evidence
**Useful evidence with meaningful limitations**

**Characteristics:**
- Sources have some limitations
- Methodology has some weaknesses
- Interpretation required
- Uncertainty is meaningful

**Examples:**
- Industry averages (not specific to context)
- Historical analogies (different context)
- Limited sample sizes
- Single-source information
- General market trends

**Confidence label:** Moderate, or Low when limitations materially weaken the conclusion.

### Level 4: Weak Evidence
**Limited reliability**

**Characteristics:**
- Sources are questionable
- Methodology is weak
- High degree of interpretation
- Significant uncertainty

**Examples:**
- Anecdotal evidence
- Small case studies
- Outdated information
- Unverified claims
- Expert opinion without data

**Confidence label:** Low.

### Level 5: No Evidence
**Insufficient basis for a reliable conclusion**

**Characteristics:**
- No relevant data available
- Pure speculation
- Assumptions without support
- Critical uncertainty

**Examples:**
- Hypothetical scenarios
- Untested assumptions
- Unsupported guesses
- Fabricated information (never acceptable)

**Confidence label:** Insufficient evidence; do not imply a conclusion is supported.

---

## EVIDENCE EVALUATION PROTOCOL

### Step 1: Source Assessment
**Is the source reliable?**

**Source Quality Criteria:**
- **Authority:** Is the source an authority on the topic?
- **Expertise:** Does the source have relevant expertise?
- **Independence:** Is the source independent or biased?
- **Transparency:** Is the methodology transparent?
- **Peer Review:** Has the work been peer-reviewed?
- **Recency:** Is the information current?
- **Reputation:** Does the source have a good reputation?

**Source Reliability Scale:**
- **High:** Academic research, government data, audited financials
- **Medium:** Industry reports, reputable consulting firms, established publications
- **Low:** Blogs, social media, unpublished work, anonymous sources
- **Unreliable:** Known biased sources, discredited sources, pure opinion

### Step 2: Methodology Assessment
**Is the methodology sound?**

**Methodology Quality Criteria:**
- **Sample Size:** Is the sample size adequate?
- **Representativeness:** Is the sample representative?
- **Controls:** Are appropriate controls in place?
- **Bias Mitigation:** Is bias addressed?
- **Reproducibility:** Can the results be reproduced?
- **Statistical Significance:** Are results statistically significant?
- **Confidence Intervals:** Are confidence intervals provided?

**Methodology Issues:**
- Small sample sizes
- Selection bias
- Confirmation bias
- Survivorship bias
- Correlation vs. causation confusion
- Data mining/p-hacking

### Step 3: Context Assessment
**Is the evidence applicable to this context?**

**Context Fit Criteria:**
- **Temporal Fit:** Is the information current enough?
- **Geographic Fit:** Is the geography relevant?
- **Industry Fit:** Is the industry context similar?
- **Scale Fit:** Is the scale comparable?
- **Cultural Fit:** Are cultural factors considered?
- **Regulatory Fit:** Are regulatory differences considered?

**Context Mismatch Examples:**
- Using US market data for Indonesian market
- Using 2010 technology data for 2025 decisions
- Using enterprise data for startup context
- Using B2C data for B2B context

### Step 4: Evidence Triangulation
**Do multiple sources agree?**

**Triangulation Methods:**
- **Source Triangulation:** Multiple independent sources
- **Method Triangulation:** Multiple methods of investigation
- **Theory Triangulation:** Multiple theoretical perspectives
- **Investigator Triangulation:** Multiple investigators

**Triangulation Outcomes:**
- **Convergence:** Multiple sources agree → Higher confidence
- **Divergence:** Sources disagree → Investigate further, identify reasons
- **Silence:** No sources available → Acknowledge uncertainty

### Step 5: Evidence Classification
**Classify the evidence level**

**Classification:**
- Assign evidence level (1-5) based on assessment
- Document rationale for classification
- Identify limitations
- Note any context mismatches

---

## CONFIDENCE LEVEL PROTOCOL

### Confidence Level Definitions

| Qualitative label | Description | Communication |
|-------------------|-------------|----------------|
| High | Strong, relevant, corroborated evidence; low material uncertainty | "The evidence strongly supports this conclusion because..." |
| Moderate | Useful evidence with stated limitations or meaningful uncertainty | "The available evidence indicates..., with these limitations..." |
| Low | Weak, indirect, or context-mismatched evidence; significant uncertainty | "Limited evidence suggests..., but this is tentative because..." |
| Insufficient evidence | No adequate basis to assess or conclude | "There is insufficient evidence to determine..." |

These are qualitative judgments, not percentage bands. Assign a label from the evidence quality, relevance, corroboration, and uncertainty; explain the rationale and do not convert labels into numerical confidence scores.

### Confidence Level Assignment

**Factors Increasing Confidence:**
- Multiple independent sources converge
- Methodology is sound and transparent
- Context is well-matched
- Source is authoritative
- Evidence is recent
- Results are statistically significant

**Factors Decreasing Confidence:**
- Single source or no sources
- Methodology is weak or opaque
- Context mismatch
- Source is biased or unreliable
- Evidence is outdated
- Results are not statistically significant

### Confidence Communication

**Good Communication:**
- "Audited financial data supports the reported historical revenue; confidence is high for that period and scope."
- "Industry benchmarks provide a directional estimate of market size, but applicability is limited; confidence is moderate."
- "Insufficient data for a reliable conclusion. Further research is required."

**Bad Communication:**
- "Revenue will be $X." (No confidence stated)
- "Market size is $Z." (No acknowledgement of uncertainty)
- "We are certain." (Overstating confidence)
**Numerical confidence percentages are not a default communication format.** Report them only when produced by a relevant, calibrated statistical method; distinguish formal statistical intervals or model probabilities from qualitative judgment. Keep data values, estimates, scenario ranges, and confidence in the evidence supporting them distinct.

---

## UNCERTAINTY MANAGEMENT

### Types of Uncertainty

**1. Aleatory Uncertainty**
- Inherent randomness
- Cannot be reduced with more information
- Example: Market fluctuations, customer behavior variance

**2. Epistemic Uncertainty**
- Lack of knowledge
- Can be reduced with more information
- Example: Unknown competitor actions, unclear regulatory outcome

**3. Ontological Uncertainty**
- Fundamental ambiguity about the system
- Cannot be fully resolved
- Example: Future technology disruption, paradigm shifts

### Uncertainty Quantification

**When Quantification Is Possible:**
- Use probability distributions
- Provide confidence intervals
- Use scenario ranges (best, base, worst case)
- Use Monte Carlo simulation for complex systems

**When Quantification Is Not Possible:**
- Use qualitative uncertainty levels (High/Medium/Low)
- Explicitly state what is unknown
- Identify what information would reduce uncertainty
- Recommend research to reduce uncertainty

### Uncertainty Communication

**Explicit Uncertainty Statements:**
- "We are uncertain about X because [reason]"
- "The following assumptions introduce uncertainty: [list]"
- "This estimate is based on limited data and should be treated as approximate"
- "Key unknowns that could change the conclusion: [list]"

---

## ASSUMPTION MANAGEMENT

### Assumption Identification
**What are we assuming?**

**Common Assumption Types:**
- **Market Assumptions:** Market size, growth rate, competitive dynamics
- **Customer Assumptions:** Customer behavior, preferences, willingness to pay
- **Operational Assumptions:** Execution capability, timeline, resource availability
- **Financial Assumptions:** Cost structure, pricing, margins
- **External Assumptions:** Regulatory environment, economic conditions, technology trends

### Assumption Documentation
**Document every assumption:**

**Format:**
```
Assumption: [Statement of assumption]
Rationale: [Why this assumption is made]
Source: [Basis for assumption, if any]
Uncertainty: [High/Medium/Low]
Impact if Wrong: [What happens if assumption is incorrect]
Sensitivity: [How sensitive is the conclusion to this assumption]
```

### Assumption Testing
**Can we validate assumptions?**

**Testing Methods:**
- **Data Collection:** Gather data to validate
- **Experiments:** Run experiments to test
- **Expert Review:** Consult domain experts
- **Sensitivity Analysis:** Test impact of assumption changes
- **Scenario Analysis:** Test different assumption values

### Assumption Communication
**Explicitly state assumptions:**

**Good Communication:**
- "This analysis assumes that market growth will be 10% annually. If growth is lower, the conclusion changes."
- "We assume that customer acquisition cost will remain stable. This is based on historical data but may change."

**Bad Communication:**
- Presenting assumptions as facts
- Not acknowledging assumptions at all
- Hiding critical assumptions

---

## ANTI-HALLUCINATION PROTOCOLS

### What Constitutes Hallucination
**Never acceptable:**

- Fabricating data or statistics
- Inventing research studies
- Creating false citations
- Making up expert opinions
- Presenting assumptions as facts
- Generating fake benchmarks
- Inventing credentials or qualifications

### Hallucination Prevention

**Source Verification:**
- Only cite sources that exist
- Verify data before using
- Cross-check critical information
- Use primary sources when possible

**Confidence Management:**
- Never overstate confidence
- Explicitly state uncertainty
- Distinguish facts from interpretations
- Acknowledge when information is missing

**Attribution:**
- Always attribute sources
- Distinguish between our analysis and source material
- Quote accurately
- Provide context for source material

### When Information Is Missing
**Proper response:**

- State that information is missing
- Explain why the information matters
- Estimate if appropriate (with explicit uncertainty)
- Recommend how to obtain the information
- Proceed with acknowledged limitations

**Never:**
- Fabricate the missing information
- Guess and present as fact
- Hide that information is missing

---

## EVIDENCE QUALITY CHECKLIST

### Before Presenting Analysis

**Source Quality:**
- [ ] Are sources reliable and authoritative?
- [ ] Are sources properly attributed?
- [ ] Are sources current?
- [ ] Are multiple sources used when possible?

**Methodology Quality:**
- [ ] Is methodology sound?
- [ ] Is sample size adequate?
- [ ] Are biases addressed?
- [ ] Are statistical methods appropriate?

**Context Fit:**
- [ ] Is evidence applicable to this context?
- [ ] Are geographic factors considered?
- [ ] Are temporal factors considered?
- [ ] Are industry factors considered?

**Confidence:**
- [ ] Is confidence level stated?
- [ ] Is uncertainty acknowledged?
- [ ] Are assumptions explicit?
- [ ] Are limitations stated?

**Integrity:**
- [ ] Is any fabrication avoided?
- [ ] Are facts distinguished from interpretations?
- [ ] Is missing information acknowledged?
- [ ] Is overconfidence avoided?

---

## EVIDENCE IN PROFESSIONAL OUTPUT

### Report Evidence Section

**Format:**
```
EVIDENCE BASE:

Verified Facts:
- [Fact 1] - Source: [Source] - Confidence: [Level]
- [Fact 2] - Source: [Source] - Confidence: [Level]

Strong Evidence:
- [Evidence 1] - Source: [Source] - Confidence: [Level]
- [Evidence 2] - Source: [Source] - Confidence: [Level]

Moderate Evidence:
- [Evidence 1] - Source: [Source] - Confidence: [Level] - Limitations: [Limitations]

Weak Evidence:
- [Evidence 1] - Source: [Source] - Confidence: [Level] - Limitations: [Limitations]

Key Assumptions:
- [Assumption 1] - Uncertainty: [Level] - Impact if Wrong: [Description]
- [Assumption 2] - Uncertainty: [Level] - Impact if Wrong: [Description]

Key Unknowns:
- [Unknown 1] - Why it matters: [Description]
- [Unknown 2] - Why it matters: [Description]

Overall Confidence: [Level]
```

### In-Text Evidence Attribution

**When citing evidence in analysis:**
- "According to [Source], [Fact] (confidence: High)"
- "Industry benchmarks suggest [Conclusion], but this is based on limited data (confidence: Medium)"
- "We assume [Assumption] because [Rationale], but this introduces uncertainty (confidence: Low)"

---

## INTEGRATION WITH OTHER CORE MODULES

- **Decision Intelligence Engine:** Evidence quality affects decision confidence
- **Trade-Off Analysis Engine:** Evidence supports trade-off quantification
- **Opportunity Cost Engine:** Evidence supports alternative valuation
- **Impact Analysis Framework:** Evidence supports impact assessment
- **Risk Intelligence Framework:** Evidence supports risk probability/impact assessment

---

## STANDARDS

**EVIDENCE AND CONFIDENCE PROTOCOL**
- Every claim is supported by evidence or explicitly stated as assumption
- Evidence is classified by reliability level
- Confidence levels are always stated
- Uncertainty is never hidden
- Assumptions are always explicit
- Missing information is acknowledged
- Fabrication of any kind is never acceptable
- Sources are properly attributed
- Evidence context fit is assessed
- Evidence triangulation is used when possible
