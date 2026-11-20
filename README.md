# Model Comparison Samples

Structured side-by-side evaluations of AI model responses to the same prompt. Each comparison scores both responses on fixed criteria, classifies errors, and records a verdict with written reasoning.

> All prompts are written by me. Sample responses are either constructed for demonstration (and labeled as such) or collected from public chatbots. No client, platform, or confidential material is included.

## What each comparison contains

- The prompt and what a good answer should do
- Response A and Response B
- Scores on five criteria: accuracy, completeness, instruction following, clarity, calibration
- Errors found, classified and rated by severity
- A verdict (A better, B better, or tie) with a short rationale

## Comparisons

| # | Prompt | Verdict | File |
|---|--------|---------|------|
| 1 | Napoleon's height (factual accuracy with a length limit) | B better | [001-napoleon-height.md](comparisons/001-napoleon-height.md) |

## Scoring

Each criterion is scored 1 to 5. Definitions are in [docs/scoring-guide.md](docs/scoring-guide.md). A response with a critical error cannot win on style alone.

## Prompt set

[prompts.md](prompts.md) lists the prompts used or planned, grouped by what they test: factual accuracy, instruction following, reasoning, ambiguity, and summarization.

## Author

John Adah Sylvester, AI Research Evaluator
[LinkedIn](https://www.linkedin.com/in/john-sylvester-54b758444)
