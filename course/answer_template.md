# Case Study 4: Answer Template

**Student name(s):**

**Student number(s):**

**Date:**

**Models used:** Model A: ___ | Model B: ___

---

## Exercise 1: Shaping Agent Personalities

### 1.1 Version 1

**Prompting style used** (e.g., adjectives only, full sentences, concrete examples):

**`innate` field:**

>

**`learned` field:**

>

**Sample conversation excerpts (2–3):**

>

### 1.2 Version 2

**Prompting style used:**

**`innate` field:**

>

**`learned` field:**

>

**Sample conversation excerpts (2–3):**

>

### 1.3 Version 3

**Prompting style used:**

**`innate` field:**

>

**`learned` field:**

>

**Sample conversation excerpts (2–3):**

>

### 1.4 Analysis

**Which version produced the most confrontational Bernard? Which produced the least?**

Your answer:

**Does Bernard's actual behaviour match what you wrote? Where is the gap largest?**

Your answer:

**Which prompting style was most effective at overriding the LLM's tendency to be polite? Why do you think that is?**

Your answer:

---

## Exercise 2: Comparing Models

### 2.1 Models used

- Model A:
- Model B:

**Which Bernard personality did you use (from Exercise 1)?**

### 2.2 Qualitative comparison

**Do the agents sound different across models? Describe the differences in tone, vocabulary, and interaction style. Provide at least one conversation excerpt from each model.**

Model A excerpt:

>

Model B excerpt:

>

Your analysis:

### 2.3 Valence comparison

(Attach or paste your valence trajectory plot)

**Which model produces more emotional variance?**

Your answer:

### 2.4 JSON validation failures

| | Model A | Model B |
|---|---|---|
| Total LLM calls | | |
| Failed validations | | |
| Failure rate | | |

**What does this tell you about using different models in agent simulations?**

Your answer:

### 2.5 Reflection

**The architecture and personality descriptions are identical. What does it mean that behaviour differs anyway?**

Your answer:

---

## Exercise 3: Enabling the Negativity Bias

### 3.1 Valence trajectories

(Attach or paste your plot of Dolores vs Maeve valence over time)

### 3.2 Descriptive statistics

| Agent | Overall valence | Thought valence |
|---|---|---|
| Dolores (neg. bias) | | |
| Maeve (control) | | |

**Cohen's d:**

**Interpretation (small / medium / large effect):**

### 3.3 Thought description comparison

**Dolores example thought (negative memory):**

>

**Maeve example thought (comparable event):**

>

**Is Dolores's description longer and more sensorially detailed?**

Your answer:

### 3.4 Memory intrusion check

If your simulation included off-duty hours, answer the following. If not, write "Simulation was too short to observe off-duty reflections."

**Did you find work-related content in Dolores's evening reflections? Paste any examples:**

>

**Did you find work-related content in Maeve's evening reflections? Paste any examples:**

>

**Is there a difference between the two agents?**

Your answer:

### 3.5 Consistency across runs (if applicable)

| Run | Dolores valence | Maeve valence | Cohen's d |
|---|---|---|---|
| Run 1 | | | |
| Run 2 | | | |
| Run 3 | | | |

### 3.6 Tracing the mechanism

**You enabled two changes: negative memories get higher retrieval scores, and negative events get stored with more detail. Looking at your logs, can you trace how these two changes could lead to the valence decline you observed? Think about what happens when a negatively-toned reflection gets stored as a new memory.**

Your answer:

---

## Exercise 4: Daily Plan Quality

### 4.1 Original plan problems

**Paste an example of a problematic daily plan and annotate what is wrong with it:**

>

### 4.2 Your planning rules

List the rules you wrote:

1.
2.
3.
4.
5.

### 4.3 Improved plan

**Paste an example of a daily plan generated with your rules:**

>

### 4.4 Downstream effects

**Do agents with better plans behave differently? More social interactions? Different valence patterns?**

Your answer:

---

## General Reflection

**What was the most surprising finding across all exercises?**

Your answer:

**If you were designing an agent simulation for a real application, what would you do differently based on what you learned?**

Your answer:
