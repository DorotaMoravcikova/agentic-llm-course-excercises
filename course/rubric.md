# Case Study 4: Grading Rubric

## Grading Scale

- **Excellent (9–10):** Demonstrates deep understanding, provides evidence, draws non-obvious connections, goes beyond the minimum.
- **Good (7–8):** Demonstrates clear understanding, provides adequate evidence, answers are correct and well-reasoned.
- **Sufficient (6):** Demonstrates basic understanding, provides some evidence, answers are mostly correct but shallow.
- **Insufficient (<6):** Missing exercises, no evidence provided, fundamental misunderstandings, or clearly did not run the simulation.

---

## Exercise 1: Shaping Agent Personalities (25%)

| Criterion | Excellent | Good | Sufficient | Insufficient |
|---|---|---|---|---|
| Number of versions | Three or more meaningfully different prompting styles | Three versions with some variation | Two versions | Fewer than two or trivial changes only |
| Log evidence | Multiple conversation excerpts per version showing clear behavioural differences | 2–3 excerpts per version | At least one excerpt per version | No excerpts |
| Comparison across styles | Identifies which style works best, explains why (e.g., concrete examples override instruction tuning where adjectives do not), connects to LLM training | Correctly identifies which style is most effective with reasoning | Notes that some versions worked better | No comparison or incorrect conclusions |
| Understanding of instruction tuning | Explains the tension between persona prompting and RLHF/alignment training, references Park's "overly cooperative" finding or equivalent insight | Correctly identifies that the LLM resists negative personas | Notes that Bernard is softer than intended | No analysis |

---

## Exercise 2: Comparing Models (20%)

| Criterion | Excellent | Good | Sufficient | Insufficient |
|---|---|---|---|---|
| Two models run | Two clearly different models (e.g., one commercial, one local) | Two models, both run correctly | Two models attempted, one may have issues | Only one model or no logs |
| Qualitative comparison | Specific, concrete observations about tone, vocabulary, behaviour with excerpts from both models | General but accurate observations with at least one excerpt per model | Notes that models differ, minimal evidence | No comparison |
| Validation failure count | Accurate counts with failure rate computed, reflects on implications | Counts provided for both models | Mentioned but not precisely counted | Not addressed |
| Reflection on model dependence | Discusses implications for reproducibility, bias inheritance, simulation design | Notes that the model matters, not just the architecture | Acknowledges differences exist | Not addressed |

---

## Exercise 3: Enabling the Negativity Bias (35%)

This is the core exercise and is weighted accordingly.

| Criterion | Excellent | Good | Sufficient | Insufficient |
|---|---|---|---|---|
| Valence trajectory plot | Clear Dolores vs Maeve plot, properly labelled, shows divergence over time | Plot present and readable | Some valence data plotted | No plot |
| Effect size | Cohen's d correctly computed, correctly interpreted (small/medium/large), separately for events and thoughts if possible | Cohen's d computed and interpreted | Cohen's d computed but not interpreted | Not computed |
| Thought description analysis | Specific examples from both agents, measures length difference, identifies sensory language in Dolores's descriptions | Examples provided, length difference noted | Mentions descriptions differ | No comparison |
| Memory intrusion check | Finds and presents evening reflection examples from both agents, notes qualitative differences | Checks evening reflections, finds some evidence | Mentions checking but no examples | Not addressed (acceptable if simulation was too short, if noted) |
| Tracing the mechanism | Correctly traces the feedback loop: negative memory → high retrieval score → negative reflection → stored as new negative memory → retrieved again | Identifies that negative memories compound over time | Notes that Dolores gets more negative | No explanation or incorrect |
| Consistency (optional) | Multiple runs reported with d values, discusses variance | At least two runs | Mentioned | Single run is acceptable |

---

## Exercise 4: Daily Plan Quality (10%)

| Criterion | Excellent | Good | Sufficient | Insufficient |
|---|---|---|---|---|
| Problem identification | Specific, annotated examples of plan problems | General but accurate description of issues | Notes plans are imperfect | No analysis |
| Planning rules | 3–5 well-reasoned rules, clearly justified | 3+ rules that make sense | At least 2 rules | No rules or nonsensical rules |
| Before/after comparison | Side-by-side plan examples showing clear improvement | Shows improvement with examples | Claims improvement without clear evidence | No comparison |
| Downstream effects | Measures whether better plans change interaction patterns or valence, with evidence | Notes downstream effects qualitatively | Mentions plans matter | Not addressed |

---

## General Reflection (10%)

| Criterion | Excellent | Good | Sufficient | Insufficient |
|---|---|---|---|---|
| Surprising finding | Specific, grounded in their own data, shows genuine engagement | Identifies something non-obvious | Generic observation | Not answered |
| Design implications | Concrete, actionable suggestions informed by multiple exercises | Reasonable suggestions | Vague statement about "being careful" | Not answered |

---

## Common Deductions

- **No logs submitted:** −10% per exercise (claims without evidence)
- **Clearly fabricated data:** Automatic fail on that exercise
- **No analysis code submitted:** −5% (using other tools is fine if explained)
- **Only one model used across all exercises:** −5% (requirement was two)
