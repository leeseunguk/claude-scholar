# Record Density and Report Triggers

Use this reference when deciding how much to record during research work in a project KB.

## Principle
Record conclusions, evidence, and judgments that changed a conclusion. Do not record every action.

## Experiment run cards (`Experiments/`)
- Create a run card only when a result is used as a number in a claim or a report.
- Do not create one for every run.
- Fields: question, code commit hash, data version, settings, seed, result path.
- Leave out discarded attempts unless they changed the conclusion.

## Daily log (`Daily/`)
- One or two lines per day: what was done and what changed.
- Put experiment details in run cards, not here.

## Report triggers (`Results/Reports/`)
Write a report when one of these happens:
1. A research question has an answer.
2. A result changes or overturns an earlier claim.
3. A meeting, presentation, or manuscript needs a consolidated summary.

If one question accumulates 3 to 5 run cards, consider an interim summary. This number is a working guideline, not a rule.

Minimum report contents:
- question and conclusion
- evidence (run card links and numbers)
- limits and open items
- next question

## Claim promotion gate
- A claim is written only when at least one run card or `Sources/` note supports it through a link.
- Disagreeing sources: write both values, mark `(확인 필요)`, add the item to the unresolved list in the index, and add a question.
