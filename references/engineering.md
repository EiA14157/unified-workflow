# Engineering

- Inspect the affected interface and existing test/run instructions first. For a multi-step change, split work by independently verifiable outcomes; one or two lines are enough when the change is small.
- For a defect, reproduce with a minimal safe case. Compare to a working path or baseline, isolate one plausible cause, and keep diagnostics sanitized. If attempts stop producing new evidence, reassess the hypothesis rather than repeating the same operation.
- When feasible, show the regression test failing for the expected reason on an isolated baseline. Do not delete or revert a user's work to manufacture a failing test. Apply the smallest justified fix and rerun the relevant checks plus any required project gate. If only a static review or stub check was possible, say so.
