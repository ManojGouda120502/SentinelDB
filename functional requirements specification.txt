Note: These are functional requirements only (what the system must do). Non-functional requirements (performance, scalability, security, availability, etc.) will be covered in Lesson 0.3.

Module 1 – Authentication & User Management
User Management
FR-001: The system shall allow administrators to create user accounts.
FR-002: The system shall allow users to register.
FR-003: The system shall allow users to log in.
FR-004: The system shall authenticate users using email and password.
FR-005: The system shall issue a JWT token after successful authentication.
FR-006: The system shall validate JWT tokens for protected APIs.
FR-007: The system shall support Role-Based Access Control (RBAC).
FR-008: The system shall allow administrators to assign roles to users.
FR-009: The system shall allow administrators to update user roles.
FR-010: The system shall allow administrators to activate users.
FR-011: The system shall allow administrators to deactivate users.
FR-012: The system shall allow users to change their passwords.
FR-013: The system shall allow users to update their profile.
FR-014: The system shall record user login history.
FR-015: The system shall log failed login attempts.

Module 2 – Database Registration & Connection Management
FR-016: The system shall allow administrators to register databases.
FR-017: The system shall support PostgreSQL database registration.
FR-018: The system shall validate database connectivity before registration.
FR-019: The system shall securely store connection details.
FR-020: The system shall allow administrators to update database configurations.
FR-021: The system shall allow administrators to delete registered databases.
FR-022: The system shall display all registered databases.
FR-023: The system shall allow administrators to enable monitoring for a database.
FR-024: The system shall allow administrators to disable monitoring.
FR-025: The system shall display database connection status.
FR-026: The system shall reconnect automatically after temporary connection failures.

Module 3 – Health Monitoring
FR-027: The system shall perform scheduled health scans.
FR-028: The system shall allow manual health scans.
FR-029: The system shall monitor database availability.
FR-030: The system shall monitor storage utilization.
FR-031: The system shall monitor table statistics.
FR-032: The system shall monitor index health.
FR-033: The system shall detect long-running queries.
FR-034: The system shall detect failed health scans.
FR-035: The system shall calculate a database health score.
FR-036: The system shall store scan history.

Module 4 – Data Quality Validation
FR-037: The system shall detect duplicate records.
FR-038: The system shall detect NULL values in mandatory fields.
FR-039: The system shall detect orphan records.
FR-040: The system shall detect foreign key violations.
FR-041: The system shall detect invalid data formats.
FR-042: The system shall detect invalid date values.
FR-043: The system shall detect invalid numeric ranges.
FR-044: The system shall detect inconsistent business data.
FR-045: The system shall classify issues by severity.
FR-046: The system shall categorize issues by type.
FR-047: The system shall allow custom validation rules.

Module 5 – AI Diagnosis
FR-048: The system shall generate AI explanations for detected issues.
FR-049: The system shall identify possible root causes.
FR-050: The system shall recommend corrective actions.
FR-051: The system shall generate SQL repair suggestions.
FR-052: The system shall estimate repair risk.
FR-053: The system shall summarize scan results.
FR-054: The system shall prioritize issues.
FR-055: The system shall identify similar historical issues.
FR-056: The system shall generate investigation reports.

Module 6 – Repair Workflow
FR-057: The system shall create repair proposals.
FR-058: The system shall display generated SQL before execution.
FR-059: The system shall allow administrators to approve repair proposals.
FR-060: The system shall allow administrators to reject repair proposals.
FR-061: The system shall allow administrators to edit repair proposals.
FR-062: The system shall execute only approved repairs.
FR-063: The system shall verify execution success.
FR-064: The system shall roll back failed repairs when possible.
FR-065: The system shall record repair outcomes.

Module 7 – Audit Trail
FR-066: The system shall record every detected issue.
FR-067: The system shall record AI recommendations.
FR-068: The system shall record approval decisions.
FR-069: The system shall record executed SQL statements.
FR-070: The system shall record execution timestamps.
FR-071: The system shall record the user who approved the repair.
FR-072: The system shall record execution results.
FR-073: The system shall allow users to search audit records.
FR-074: The system shall export audit reports.

Module 8 – Dashboard & Reporting
FR-075: The system shall display overall database health.
FR-076: The system shall display active issues.
FR-077: The system shall display issue trends.
FR-078: The system shall display scan history.
FR-079: The system shall display repair success rate.
FR-080: The system shall display issue severity distribution.
FR-081: The system shall display recently executed repairs.
FR-082: The system shall generate summary reports.

Module 9 – Notifications
FR-083: The system shall notify administrators about critical issues.
FR-084: The system shall notify users when a repair requires approval.
FR-085: The system shall notify administrators after repair execution.
FR-086: The system shall notify users about failed scans.
FR-087: The system shall support email notifications.
FR-088: The system shall support Slack notifications.
FR-089: The system shall support Microsoft Teams notifications.

Module 10 – API & Integration
FR-090: The system shall expose REST APIs for database management.
FR-091: The system shall expose APIs for health scan execution.
FR-092: The system shall expose APIs for issue retrieval.
FR-093: The system shall expose APIs for repair approval.
FR-094: The system shall expose APIs for audit history.
FR-095: The system shall expose APIs for dashboard statistics.
FR-096: The system shall generate OpenAPI (Swagger) documentation.

Module 11 – Scheduling
FR-097: The system shall schedule automatic health scans.
FR-098: The system shall allow administrators to configure scan frequency.
FR-099: The system shall allow administrators to pause scheduled scans.
FR-100: The system shall resume paused schedules.

Module 12 – Future Enterprise Features
FR-101: The system shall support monitoring multiple database types.
FR-102: The system shall support multi-tenant organizations.
FR-103: The system shall support versioning of validation rules.
FR-104: The system shall support predictive issue detection.
FR-105: The system shall support configurable approval workflows.
FR-106: The system shall support event publishing.
FR-107: The system shall support asynchronous repair execution.
FR-108: The system shall support integration with CI/CD pipelines.
FR-109: The system shall support plugin-based validation rules.
FR-110: The system shall support custom AI providers.