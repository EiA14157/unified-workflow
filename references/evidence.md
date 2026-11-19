# Data, models, and measurement

- Define the unit of comparison, baseline, and quality bar first. Keep the input and evaluation setup matched between candidates; use a holdout when tuning could leak into evaluation.
- Start with a small representative run. Check expected input/output, resource fit, and metric computation before scaling. Do not switch to an external provider, spend money, or run untrusted code without the applicable authorization.
- For token efficiency, record actual end-to-end metered tokens including retries and failed runs. Divide total spend by verified successes; report pass rates and incomplete measurements separately. Compare cache conditions and report latency and monetary cost separately. If no experiment ran or no task passed, do not report a savings figure.
