## POSTMOTERM

On FEBRUARY 10, 2023, from 9:00 AM to 11:00 AM EAT, the website's homepage was not loading for 50% of the users. This issue was caused by a misconfigured SSL crtificate in the load balancer, which caused HTTP 503 errors. The incident was detected at 9:10 AM EAT when a monitoring alert triggered by a sudden spike in HTTP 500 errors was received.
Initially, the investigation started by checking the application and database servers. Later, the load balancer logs were analyzed, which revealed that the SSL certificate was misconfigured. Initially, it was suspected that the issue was due to a sudden spike in traffic, but after analyzing the server logs, this assumption was ruled out.
The incident was escalated to the Network Operations team and the development team. The SSL certificate in the load balancer was renewed, and the load balancer was reconfigured, which fixed the issue.

### To prevent similar incidents from happening in the future, the following corrective and preventative measures were taken:
- Monitoring alerts were added to monitor SSL certificate expiration in the load balancer.
- Regular maintenance of SSL certificates in the load balancer was scheduled.
- A runbook for SSL certificate maintenance was created. Automation for SSL certificate renewal was implemented.

### Conclusion
- The issue was resolved within two hours, and appropriate corrective and preventative measures were taken to prevent similar incidents from happening in the future.
