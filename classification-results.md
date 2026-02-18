# AI Incident Severity Classifier – Test Results

This document contains severity classification results generated using the LLM-based severity classifier prompt.

---

Incident 1: Login service throwing 500 errors for all users

Severity: SEV-1 (Critical)

Reason:
All users are unable to log in; core production functionality unavailable.

Business Impact:
Complete service outage preventing system access.

Recommended Action:
Immediate escalation to engineering; restore service and identify root cause.

---

Incident 2: One user unable to access reporting module

Severity: SEV-3 (Medium)

Reason:
Issue isolated to single user; limited scope.

Business Impact:
Minimal operational impact.

Recommended Action:
Check user permissions, access roles, and profile configuration.

---

Incident 3: Payment gateway timeout intermittently

Severity: SEV-2 (High)

Reason:
Revenue-impacting functionality degraded; intermittent failures affecting multiple users.

Business Impact:
Delayed or failed transactions; potential revenue loss.

Recommended Action:
Investigate gateway latency, dependencies, and upstream integrations.

---

Incident 4: Typo in UI dashboard

Severity: SEV-4 (Low)

Reason:
Cosmetic issue with no functional impact.

Business Impact:
No operational or financial impact.

Recommended Action:
Fix in next UI release cycle.

---

Incident 5: Database CPU 95%, system slow

Severity: SEV-2 (High)

Reason:
High resource utilization causing system-wide performance degradation.

Business Impact:
Reduced system performance affecting multiple users.

Recommended Action:
Investigate heavy queries, optimize database, and scale resources if required.

