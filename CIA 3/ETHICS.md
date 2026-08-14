# Ethics, fairness, and deployment limits

## Intended use

FairLoan Assist is a **review-prioritisation aid**, not an automated credit decision system. A high risk score should trigger a supportive affordability conversation or request for clarification, not a denial. A low score never removes the need for normal checks.

## Fairness and privacy

Historical repayment labels can reflect unequal access, discriminatory lending, and economic shocks. `personal_status` is excluded from modelling and retained only to calculate a limited post-hoc group audit. That audit reports sample size, selection rate, default recall, and false-positive rate; it does not establish fairness, particularly with small samples or an imperfect demographic proxy. Before deployment, assess relevant legally permitted groups, use representative local data, conduct independent review, and document remediation decisions.

Use only consented, minimised, encrypted data. Do not collect names, addresses, account identifiers, or protected attributes unless a lawful fairness audit requires them; then isolate access and retention.

## Error costs, uncertainty, and oversight

False positives can wrongly burden or exclude an applicant; false negatives can cause unaffordable lending and losses that reduce future access. Thresholds must be set by a multidisciplinary policy process, not chosen solely for accuracy. Scores are uncertain estimates from a small historical dataset: display confidence context, accept appeals/corrections, log decisions, monitor calibration and drift, and suspend the tool when performance or group gaps deteriorate.

The German-credit dataset is educational and not evidence that this tool is valid for any locality or real microfinance provider.
