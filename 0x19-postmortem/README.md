My first Postmortem

Duration: The outage occurred from 11:00 AM to 12:30 PM (WAT+1).
Impact: The login service of our web application was inaccessible, affecting approximately 70% of active users who were unable to log in during the outage.
Root Cause:
The root cause of the outage was traced to a misconfiguration in the authentication service's database connection pool settings. This misconfiguration led to inadequate management of database connections, resulting in a bottleneck and subsequent failure of the login service.

Timeline:

11:00 AM (WAT+1): Monitoring alerts indicated a surge in failed login attempts, prompting investigation.
11:05 AM: Engineering team initiated investigation into the issue.
11:10 AM: Initial focus on reviewing server logs for any anomalous errors.
11:20 AM: Analysis of database performance metrics to detect abnormalities.
11:30 AM: Investigative efforts temporarily diverted to explore network connectivity and hardware issues.
11:45 AM: Incident escalated to senior database administrator and system architect.
12:00 PM: Root cause identified as misconfiguration in database connection pool settings.
12:15 PM: Configuration settings adjusted to optimize database connection management.
12:30 PM: Login service restored, allowing users to access their accounts again.
Root Cause and Resolution:
The misconfiguration in the database connection pool settings caused an overload of connections, leading to service failure. This issue was resolved by reconfiguring the settings to properly manage database connections, alleviating the bottleneck and restoring normal service operation.

Corrective and Preventative Measures:

Improvements/Fixes:
Implement automated monitoring for database connection pool health.
Conduct regular audits of database configurations to detect and rectify potential misconfigurations.
Tasks to Address the Issue:
Apply patches to database connection pool settings for optimized performance.
Introduce automated alerts for abnormal database connection behavior.
Schedule periodic reviews of database configurations to prevent recurrence of misconfigurations.
By addressing the root cause and implementing corrective measures, we aim to mitigate the risk of similar incidents in the future and uphold the reliability of our services.


