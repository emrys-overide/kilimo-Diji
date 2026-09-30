# Production readiness plan (2026-09-30)

## Assessment: 2% complete
The default branch contains only a 186-byte README describing an AI plant-disease product. There is no application, model, dependency manifest, test, workflow, or deployment configuration in this repository. The percentage is an evidence-based rough estimate of production work completed, not a measured velocity metric.

## Decision needed
Decide whether this repository should become the canonical Kilimo Dijital app or point to the existing `smart-farm-app` repository. Avoid developing two independent copies of the same product.

## Execution plan
1. Define the product owner, users, supported crops, languages, data protection needs, and acceptance criteria.
2. If canonical, import the application deliberately from `smart-farm-app` with history attribution; provide a licensed and independently verified model artifact. If not canonical, mark this repository as a pointer and archive it after stakeholders agree.
3. Add reproducible setup, environment examples, image upload limits, model availability behavior, and privacy policy.
4. Add unit and integration tests for inference, upload validation, and unavailable-model responses; run them in CI.
5. Validate model accuracy on representative Kenyan field images and agronomist-reviewed advice; document limitations and escalation.
6. Deploy to staging, perform security and usability testing, then release with monitoring and rollback.

## Work completed on this branch
This plan records the evidence and the product decision blocking safe implementation. No application code existed to change.
