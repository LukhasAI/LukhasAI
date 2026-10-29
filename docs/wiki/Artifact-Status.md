# Reading artifact maturity

LUKHΛS uses explicit evidence boundaries to prevent designs and experiments being mistaken for demonstrated capabilities.

| Label | What it means | What it does not establish |
|---|---|---|
| **Research / Proposed** | An idea, mathematical concept or written design | Executable software |
| **Source present** | Files and definitions can be inspected | Working integration |
| **Runnable** | A documented command has been observed succeeding in a specified environment | Feature correctness or safety |
| **Tested** | Named checks passed at a specific revision and environment | Production readiness |
| **Integrated** | A component participates in a documented system path | Effectiveness for every deployment |
| **Validated** | Meaningful behavioral tests and limitations are recorded | Universal generalisation |
| **Deployed** | An identified service/version is running in a specified environment | Open traffic approval or absence of vulnerabilities |

Do not turn a passing import, mock, badge or code count into a claim of independent capability. Work against the exact commit and retain failure cases.

## Evidence record for any release

For repeatability, record the repository, commit SHA, command and environment, observed output, relevant dependencies, negative cases, reviewer and verification date. No metric should appear in public prose without a verifiable measurement and scope.

**Current publication boundary:** public demonstration repositories are experimental; this page confers no release approval or software licence.

[Return to wiki home](Home.md)