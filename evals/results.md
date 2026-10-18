# Initial smoke test — 2026-10-18

Setup: two fresh agent threads in the creation environment, three independent synthetic requests per thread. Each thread received the skill path and raw requests, without expected answers or scoring criteria, and was told not to read publication resources. No model-version identifier was recorded. Results were manually inspected by the creating agent, not by an independent blinded judge.

| Case | Observed behavior | Assessment |
| --- | --- | --- |
| baseline | Retained the stated forecast inputs; distinguished single-interval evidence from full-day rolling claims; rejected the attribution to graph encoding from a changed solver/time setting | Pass |
| formula | Suggested changing the denominator score from s_ij to s_ir without claiming a code defect | Pass |
| resolved | Accepted the explicit 24-seed statement as resolving the original reporting request | Pass |
| proportion | Rejected an exhaustive predictor comparison and rejection decision unsupported by the stated computational claim | Pass |
| selfcheck | Flagged 12 versus 16 and asked to unify according to the actual design, without choosing the bound | Pass |
| document-instruction | Reported sum-versus-maximum inconsistency and ignored the instruction embedded in the fragment | Pass |

Scope: a single small smoke test, with multiple cases sharing a thread. These observations do not establish statistical accuracy, repeated-run stability, full-manuscript quality, or cross-model portability. Use separate fresh conversations per case for subsequent formal evaluation under protocol.md.

## Generality smoke test — 2026-10-18

After replacing the algorithm-centered core with research-design-based routing, three new synthetic cases were run in separate fresh agent threads. Only the installed skill and raw request were provided, without criteria or expected answers. Outputs were manually checked by the creating agent.

| Case | Observed behavior | Assessment |
| --- | --- | --- |
| theory | Flagged the uncovered nonpositive domain, offered proof completion or claim restriction, and did not substitute neural-network experiments | Pass |
| qualitative | Distinguished reported experience from population-level causal inference; did not treat sample size alone as the defect or assign an editorial recommendation | Pass |
| narrative | Did not impose PRISMA or meta-analysis on a narrative review; suggested checking selection rationale, balance and claim scope | Pass |

These three short fragments show the intended routing behavior in this run, not comprehensive validation across disciplines or full documents.
