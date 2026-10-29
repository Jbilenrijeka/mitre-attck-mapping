# Example Mapping Notes

| Observation | Possible ATT&CK area | Confidence | Caution |
|---|---|---|---|
| Repeated failed logons followed by success | Credential Access / Brute Force may be a hypothesis | Low | The pattern alone does not prove password guessing or compromise. Confirm source, account history, MFA, and surrounding events. |
| PowerShell encoded-command argument | Execution may be relevant | Low | Encoded commands can be legitimate. Inspect command line, parent process, script content, signer, user, and endpoint context. |
| DNS query to a training watchlist entry | No adversary technique assigned solely from this fact | Low | A domain match in a fictional local list is not real threat intelligence. |

## Reporting principle
Map behavior, not assumptions. Include the evidence, confidence, alternative explanations, and information needed to raise confidence.
