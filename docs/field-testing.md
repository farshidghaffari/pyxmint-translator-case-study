# Field testing

## Evidence basis

This document summarizes owner-approved qualitative observations. It contains no raw recordings, real transcripts, participant information, test dates, sample counts or private analytics. It is not an independently reproduced benchmark. See [evidence register](evidence-register.md).

## OBSERVED

| Approved observation | What it supports | What it does not establish |
| --- | --- | --- |
| Working, field-tested MVP; café testing in Gyumri | Real-world testing beyond a purely conceptual workflow | Production readiness or commercial adoption |
| Noisy-input observations | Input conditions matter as a test dimension | That noise caused a particular failure |
| Armenian → Persian sentence-start issues in some attempts | A specific direction and behavior warrant investigation | A failure rate, all-language weakness or root cause |
| Synthetic Armenian input performed better than some live/noisy attempts | A qualitative contrast worth retesting | A controlled accuracy comparison or evidence of equal content/conditions |
| Longer turns introduced more noticeable latency | Turn length warrants explicit evaluation | A measured latency value or a causal model |

“Better” and “more noticeable” retain the qualitative scope of the approved observations. No numeric values or unreported test conditions are inferred.

## Testing and iteration

Farshid tested real-world behavior, reviewed failures and iterated the product. This account does not claim a specific implementation correction, a verified resolution of the sentence-start issue or automated test coverage.

## PROPOSED NEXT TESTS

Revisit the observed patterns with explicit language direction, input type, environmental condition and turn length. Define timing boundaries and evaluation criteria before collecting results. Use approved synthetic material; do not publish real conversations. The [test matrix](limitations-and-next-steps.md) is a proposal, not an executed test report.
