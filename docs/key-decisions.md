# Key decisions

## DOCUMENTED DESIGN

Farshid identified the product problem, designed the conversation workflow, made product/system decisions, used AI-assisted implementation, tested real-world behavior, reviewed failures and iterated the product.

The table states approved choices and their scope. The trade-off questions are editorial analysis for further validation, not claims about measured benefits or a recovered historical decision log.

| Approved choice | Product scope | Trade-off question for validation |
| --- | --- | --- |
| Browser-based conversation | A browser surface for face-to-face exchanges | Which browser/device conditions need explicit testing? |
| Push-to-talk | An explicit speaking action | How does turn length affect conversational flow? |
| Optional transcript | Transcript is optional in the workflow | When does viewing text help conversation continuity? |
| Active-speaking time allowance | A speaking allowance is part of the product | How should allowance behavior be explained and tested without exposing private rules? |
| Five-language scope | Persian, Armenian, English, German and Russian | Which directions and conditions need stronger evidence? |
| Real-world testing | Café field testing in Gyumri | Which observations repeat under controlled conditions? |

## AI-assisted implementation

AI-assisted implementation supports Farshid's workflow design, product decisions, review and iteration. The case study does not equate code volume with delivered value and does not claim independent hand-coding of every component.

## OBSERVED feedback

The approved observations are recorded in [field testing](field-testing.md). They informed review and iteration, but no individual fix, causal diagnosis or resolved defect is asserted here.

## PROPOSED NEXT TESTS

Test the questions above using controlled synthetic inputs and an explicit test matrix. These are proposed evaluations, not completed tests or promised features.
