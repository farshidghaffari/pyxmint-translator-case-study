# Problem and constraints

## Problem and existing friction

PyxMint addresses a face-to-face conversation workflow across languages. The design concern is keeping turns understandable and manageable, rather than treating each translation as a disconnected task. This is product framing, not a measured account of a customer's workflow or cost baseline.

## DOCUMENTED DESIGN

The approved scope is a browser-based conversation MVP with push-to-talk, an optional transcript and an active-speaking allowance. The language set is Persian, Armenian, English, German and Russian. Coverage is not evidence of equal performance or tested support for every language direction.

An active-speaking allowance is an approved product feature. Its numeric amount, accounting algorithm, reset rules and commercial terms are not specified here. Optional transcript describes the user-facing feature; it does not establish retention, deletion or storage behavior.

## OBSERVED constraints

Café testing in Gyumri exposed noisy-input observations and sentence-start issues in some Armenian → Persian attempts. Synthetic Armenian input performed better than some live/noisy attempts; longer turns introduced more noticeable latency. No controlled causal conclusion follows from these observations.

## Intended value

The workflow is designed to reduce conversation friction and the effort of managing repeated turns. There is no verified time-saving, cost-saving, accuracy or ROI claim.

## Documentation constraints

Use only owner-approved facts. Do not expose application code, real conversation content, participant information, infrastructure or deployment details. Diagrams must explain functional scope without inventing internal components. See [privacy and public scope](privacy-and-public-scope.md).
