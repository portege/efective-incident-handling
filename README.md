# Overview
Having an always available service is almost not possible to have 100% uptime guarantee. What happens in the every organization is that they try to anticipate to any disruption by using some of the opproach such as multi data-center, auto-scale, CDN, Caching etc. And also to set error-budget to give a flexibility to engineer for product improvement.

Effective Incident Handling is a framework to handle any incident to safe the error-budget, and increasing product SLO. The process can be simplify by using following formula:
TIME-TO-RESPOND + TIME-TO-RESOLVE < ERROR-BUDGET

This framework has 4 main focus, Acknowledgement, Investagion, Mitigation and Fixing.

# Acknowledgment
## Objective
To be alarmed as early as possible
* Ticket system
* Logging system
* SLO
* Metrics
  * APM
  * Infrastructure
  * Service rates
* Alarm
  * Trend
  * Actual
  * Anomalies
* Dashboard
* Communication Channel

# Investigation
## Objective
To understand the overall situation, including the impact and the root cause. and to plan what's the action item to resolve the incident.
* Logging system
  * API Call
  * Activity / event timeline
  * Changes logs
* Tools
* Dashboard
* Metrics
* RCA
* Documentation
  * Business flow
  * Architecture
  * Pipeline diagram

# Mitigation
## Objective
Usualy this is a temporary solution to restore the service back to normal.
* Collaboration
* Communication
* Run-book
* Documentation
* Knowledge Transfer / Sharing
* CICD
* Permission / Role
* Post-Mortem review
* Change management process

# Fixing
## Objective
The phase to find out the root cause and give a permanent solution
* Escalation Path
* Impact analysis
