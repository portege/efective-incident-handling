# Overview
The purpose of this framework is to help any organization or team to align their SRE team with common practice or want to start to utilize the current team to handling for any unexpected event in production.

# Preface
Nobody likes downtime in production. But downtime is inevitable, this can be from an expected event like migration cut-over, scheduled maintenance, major changes -- or downtime because of unexpected events such as security breach, data leak, sudden load.

We usually have a time estimation on an expected event, but when it comes to unexpected events like production issues or incidents, the timeframe can be wider and unknown, and this unknown may spend the Error budget unexpectedly will impact the SLO.

## Production issue
The root cause of production issue or any incident that happens in production -- can be from the code, infrastructure, or from abuse of resources or privilege. There are 4 common steps or practices to handle an incident.

| [acknowledgment](acknowledgement/index.md) | [investigation](investigation/index.md) | [mitigation](mitigation/index.md) | [fix](fix/index.md) |

The time from the incident until the acknowledgment called meantime-time-to-detect. And when first start the investigation until the service gets restored is called meantime-to-recover. While to get a permanent solution or fix the issue it is called meantime-to-resolve. And the total overall process to handle the incident should be lesser than or equal to the Error budget.

> ∑(meantime-to-detect + meantime-to-mitigate + meantime-to-resolve) ≤ error-budget
