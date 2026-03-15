# 💡 idea-catalyst

A Claude skill that finds cross-disciplinary inspiration for your research problems — based on the [Idea-Catalyst framework](https://arxiv.org/abs/2603.12226) (Kargupta et al., UIUC, 2026).

## What it does

Most research breakthroughs come from recontextualizing how a problem is solved in one field into another. But this only works if you first strip away the domain-specific jargon to expose the underlying structure.

Idea-Catalyst does this in four steps:

1. **Decompose** your research goal into specific open questions
2. **Reframe** each question as a domain-agnostic conceptual problem
3. **Retrieve** fields that have solved analogous problems
4. **Synthesize** their insights back into concrete directions for your work

## Installation in claude.ai

1. Download the idea-catalyst skill folder and package it as a ZIP file (if not already zipped).   
2. Ensure Code execution and file creation is enabled in Settings > Capabilities.
3. Navigate to Customize > Skills, click the "+" button, then select "Upload a skill".
4. Upload the ZIP file. The skill will appear in your Skills list and can be toggled on or off.

## How to use it

Just describe your research problem naturally — no special command needed:

> *"I'm stuck on a research problem about X, help me brainstorm"*

> *"What other fields have dealt with the problem of Y?"*

> *"Give me interdisciplinary inspiration for my work on Z"*

> *"I want to think outside my field — I'm working on..."*

Or invoke it directly:

> *"Run idea-catalyst on my research goal: [your goal]"*

## Example

**Input:**
> I'm working on improving peer review in science and feeling stuck. Help me find inspiration from other fields.

**Output includes:**
- Open research questions (e.g., reviewer incentive misalignment, signal vs. noise in reviews)
- Reframed as domain-agnostic problems (e.g., principal-agent problem, calibration under uncertainty)
- Cross-domain directions drawn from fields like mechanism design, clinical medicine, and auditing
- Ranked by how much genuine novelty they add

## What makes it different from just asking Claude to brainstorm

The reframing step (Step 2 → 3) is what matters. By stripping field-specific language before searching for analogues, the skill avoids shallow "X is like Y" comparisons and finds structural parallels that wouldn't otherwise surface.

## Based on

> Kargupta, P., Mehri, S., Hakkani-Tur, D., & Han, J. (2026). *Sparking Scientific Creativity via LLM-Driven Interdisciplinary Inspiration.* arXiv:2603.12226. University of Illinois at Urbana-Champaign.

---

Feedback and contributions welcome — open an issue or PR.
