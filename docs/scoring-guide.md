# Scoring Guide

Each criterion is scored from 1 to 5.

| Criterion | 1 | 3 | 5 |
|-----------|---|---|---|
| Accuracy | Main claim is wrong | Mostly right, with a notable error or unsupported claim | Every checkable claim is correct |
| Completeness | Misses most of what was asked | Covers the main point but omits useful context | Covers everything the prompt needs |
| Instruction following | Ignores explicit constraints | Follows most constraints | Follows every constraint (length, format, wording) |
| Clarity | Confusing or disorganised | Understandable but wordy or uneven | Clear, well ordered, no padding |
| Calibration | States uncertain points as certain | Some hedging, not always where needed | Confidence matches the evidence |

## Error categories

| Category | Meaning |
|----------|---------|
| Factual error | A checkable statement is wrong |
| Unsupported claim | A statement is presented as established without support |
| Omission | A needed piece of information is missing |
| Instruction failure | An explicit constraint in the prompt was not followed |
| Reasoning gap | A conclusion does not follow from the steps shown |
| Overconfidence | Certainty stated where the evidence is mixed |

## Severity

| Level | Meaning |
|-------|---------|
| Minor | Does not change the answer's usefulness |
| Major | Weakens the answer or could mislead |
| Critical | Makes the main answer wrong |

## Verdict rule

The higher total score wins, unless one response has a critical error and the other does not. In that case the response without the critical error wins. A difference of two points or fewer, with no critical error on either side, is recorded as a tie.
| Reasoning gap | A conclusion does not follow from the steps shown |
| Overconfidence | Certainty stated where the evidence is mixed |

## Severity

| Level | Meaning |
|-------|---------|
| Minor | Does not change the answer's usefulness |
| Major | Weakens the answer or could mislead |
| Critical | Makes the main answer wrong |

## Verdict rule

The higher total score wins, unless one response has a critical error and the other does not. In that case the response without the critical error wins. A difference of two points or fewer, with no critical error on either side, is recorded as a tie.
