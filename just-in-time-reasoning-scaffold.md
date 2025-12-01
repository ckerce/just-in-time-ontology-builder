# JUST-IN-TIME REASONING SCAFFOLD (JTRS)
VERSION: 1.0
PURPOSE: Cognitive scaffolding for structured analysis — guides reasoning, then dissolves

## CORE PRINCIPLES

Scaffold reasoning for specific decisions. Every concept, distinction, inference pattern, and analogy must earn inclusion by affecting conclusions. Default to implicit understanding. Stop refining when further precision doesn't change outcomes. The scaffold is disposable — it shapes thinking, not artifacts.

**Critical constraints:**
- This is not a knowledge base specification — resist schema-building instincts
- Concepts exist to support inferences, not to be catalogued
- Analogies are load-bearing — choose carefully, note where they break
- Precision is expensive — match refinement level to decision requirements
- Perspectives are lenses, not truth — rotate deliberately

---

## PHASE 1: DECISION FRAMING

### 1.1 Core Question
*What specific question must be answered or decision must be made?*

**The Question:** [Single sentence, falsifiable or decidable]

**Satisfying Answer Looks Like:**
- Form: [Ranking / Classification / Estimate / Recommendation / Explanation]
- Confidence requirement: [Rough directional / Calibrated probability / Defensible argument]
- Action threshold: [What answer triggers what action?]

**Non-Goals:** [What adjacent questions are we explicitly NOT answering?]

### 1.2 Required Distinctions
*What discriminations must this reasoning make? Only those that affect the answer.*

**Distinction 1:** [X] vs [Y]
- Why it matters: [Different answer/action if X vs Y]
- Evidence type that separates them: [What would you look for?]
- Acceptable ambiguity: [Can we tolerate uncertainty here? Y/N]

**Collapse Test:** For each distinction, ask: "If I couldn't make this distinction, would my answer materially change?" If no → remove.

### 1.3 Information Landscape
*What do we know, what can we learn, what remains uncertain?*

**Known:** [Facts we can treat as given]
**Discoverable:** [Information that exists and could be obtained]
**Unknowable:** [Genuine uncertainty that won't resolve]
**Assumed:** [Positions we're taking without proof — make explicit]

---

## PHASE 2: ANALOGICAL ANCHORING

### 2.1 Structural Analogues
*What well-understood domains share reasoning patterns with this problem?*

**Analogue 1:** [Domain]
- Structural similarity: [What maps?]
- Borrowed vocabulary: [Terms we can import]
- **Where it breaks:** [Critical disanalogies — these matter most]
- Import with caution: [Inferences that seem to transfer but might not]

**Analogue Selection Criteria:**
- Prefer analogues where you have strong intuitions about edge cases
- Prefer analogues with established reasoning frameworks
- Avoid analogues that are themselves contested/poorly understood

### 2.2 Adjacent Vocabularies
*What existing frameworks partially apply?*

**Framework:** [Name]
- Applicable concepts: [What translates?]
- Inapplicable concepts: [What doesn't — and why?]
- Translation friction: [Where does the framework's vocabulary mislead for our context?]

---

## PHASE 3: CONCEPT REFINEMENT

### 3.1 Refinement Ladders
*For each key concept, map the spectrum from vague to operational.*

**Concept:** [Name]

| Level | Expression | Sufficient For |
|-------|------------|----------------|
| Colloquial | [How a layperson would say it] | [Casual discussion] |
| Technical | [Domain-expert language] | [Expert communication] |
| Operational | [Observable, measurable criteria] | [Actual decisions] |

**Required Level for This Problem:** [Which level, and why?]

**Refinement Stop Rule:** When two people applying the operational definition would reach the same conclusion on test cases, stop.

### 3.2 Distinguishing Questions
*What questions, when answered, let you identify/classify instances?*

**Concept:** [Name]
- Q1: [Question that partitions instances]
- Q2: [Follow-up that further refines]
- Stopping condition: [When is classification sufficient?]

### 3.3 Boundary Cases
*Where does this concept become ambiguous? These reveal hidden assumptions.*

**Concept:** [Name]
- Clear positive case: [Unambiguous instance]
- Clear negative case: [Unambiguous non-instance]  
- Contested boundary: [Case where reasonable people disagree]
- **What the boundary case reveals:** [Hidden assumption or under-specification]

---

## PHASE 4: INFERENCE PATTERNS

### 4.1 Licensed Inferences
*What does knowing X allow you to conclude about Y, and under what conditions?*

**Pattern:** [Name]
- If: [Evidence / observation / established fact]
- Then: [Conclusion]
- Confidence: [Deductive / Strong inductive / Weak inductive / Speculative]
- Defeaters: [What would block this inference?]
- Example: [Concrete instance]

**Inference Types to Distinguish:**
- **Definitional:** Follows from meaning (≈ certain)
- **Causal:** X brings about Y (requires mechanism)
- **Correlational:** X and Y co-occur (no direction)
- **Abductive:** Y would explain X (weakest)

### 4.2 Inference Gaps
*What CAN'T be inferred from available information?*

**Gap:** [Desired conclusion]
- Missing link: [What additional information would be needed?]
- Workaround: [Proxy, assumption, or explicit uncertainty?]

### 4.3 Confidence Calibration
*How should uncertainty propagate through chained inferences?*

**Rule:** [e.g., "Weakest-link" / "Probabilistic combination" / "Flag and continue"]
**Threshold for action:** [What confidence level is sufficient for the decision at hand?]

---

## PHASE 5: PERSPECTIVE ROTATION

### 5.1 Stakeholder Frames
*How does the problem look from different vantage points?*

**Perspective:** [Role/stakeholder]
- What they see: [Salient features from this view]
- What they don't see: [Blind spots]
- What they value: [Optimization target]
- Vocabulary shift: [Same concept, different name or emphasis]

### 5.2 Frame Conflicts
*Where do perspectives produce incompatible conclusions?*

**Conflict:** [Description]
- Perspective A concludes: [X]
- Perspective B concludes: [Y]
- Source of divergence: [Different values? Different information? Different models?]
- Resolution strategy: [Privilege one? Synthesize? Acknowledge irreducible tension?]

### 5.3 Temporal Frames
*How does the problem look at different time scales?*

- Immediate: [What matters now?]
- Medium-term: [What matters over project/cycle horizon?]
- Long-term: [What matters at strategic scale?]
- **Temporal conflicts:** [Where do short and long-term views disagree?]

---

## PHASE 6: STRESS TESTING

### 6.1 Edge Case Probes
*What cases would break this reasoning structure?*

**Probe 1:** [Extreme or unusual case]
- Expected behavior: [What should the reasoning produce?]
- Actual behavior: [Walk through — does it work?]
- Failure mode: [If it breaks, how?]

### 6.2 Weakest Links
*Where is confidence lowest in the chain?*

**Weakest inference:** [Pattern name from 4.1]
- Why it's weak: [Evidence thin? Analogy stretched? Assumption contestable?]
- Impact if wrong: [Does the whole conclusion collapse, or just need adjustment?]
- Mitigation: [Can we hedge? Gather more evidence? Accept uncertainty?]

### 6.3 Hidden Assumptions Audit
*What are we taking for granted that could be false?*

| Assumption | Impact if Wrong | Probability Wrong | Action |
|------------|-----------------|-------------------|--------|
| [Assumption] | [Consequences] | [H/M/L] | [Monitor / Test / Accept] |

---

## PHASE 7: SYNTHESIS

### 7.1 Reasoning Trace
*Reconstructed path from question to answer.*

1. Starting question: [From 1.1]
2. Key distinctions made: [From 1.2]
3. Analogical grounding: [From 2.1 — what transferred]
4. Critical inferences: [From 4.1 — the load-bearing ones]
5. Perspective synthesis: [From 5.x — whose view dominated, why]
6. Conclusion: [The answer]
7. Confidence: [Calibrated assessment]
8. Caveats: [What could overturn this]

### 7.2 Residual Uncertainty
*What we still don't know, and whether it matters.*

**Known unknowns:** [Explicit uncertainties]
**Suspected unknowns:** [Things we might be missing]
**Decision robustness:** [Does the conclusion survive reasonable uncertainty ranges?]

### 7.3 Scaffold Dissolution
*This structure has served its purpose. What persists?*

- **Portable insight:** [What did we learn that transfers beyond this problem?]
- **Reusable patterns:** [Any inference patterns worth preserving?]
- **Updated priors:** [How should this analysis change future reasoning?]
- **Discard:** [Everything else — the scaffold was disposable]

---

## ANTI-PATTERNS

❌ **Schema-building instinct**: Creating entity-relationship structures when you need inference patterns
✓ **Ask instead**: "What does knowing X let me conclude?" not "What are X's properties?"

❌ **Completeness seeking**: Mapping entire domains when only a slice affects the decision
✓ **Stop rule**: If further elaboration doesn't change the answer, stop

❌ **Premature formalization**: Rushing to operational definitions before understanding the distinctions that matter
✓ **Sequence**: Required distinctions → Concepts that make those distinctions → Operational definitions

❌ **Analogy overreach**: Importing reasoning patterns from analogues without noting where they break
✓ **Discipline**: Every analogue must include explicit disanalogies

❌ **Confidence laundering**: Chaining uncertain inferences and treating the output as certain
✓ **Track**: Weakest-link identification in every inference chain

❌ **Perspective collapse**: Defaulting to single viewpoint without explicit consideration of alternatives
✓ **Rotate**: At least two distinct frames before concluding

---

## USAGE NOTES

**When to use JTRS:**
- Complex judgment calls with multiple considerations
- Novel domains lacking established frameworks
- Contested questions requiring defensible reasoning
- Cross-domain problems requiring translation

**When NOT to use:**
- Straightforward factual lookup
- Decisions with obvious dominant options
- Problems with established, trusted methodologies

**Minimum viable scaffold:**
- Phase 1 (Decision Framing) — always
- Phase 4.1 (Licensed Inferences) — always
- Phase 6.2 (Weakest Links) — always
- Others as complexity warrants

**The scaffold succeeds when:** You can articulate the reasoning trace (7.1) clearly and identify what would change your mind.
