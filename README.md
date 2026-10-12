# aws-cloudtrail-security-monitoring

Overview

This project documents my first hands-on AWS cloud security monitoring lab. I used AWS CloudTrail to explore account activity, record events, and investigate a failed console sign-in attempt.

Objectives

- Understand the role of AWS CloudTrail in cloud security.
- Explore CloudTrail Event History.
- Create a trail to record account activity.
- Investigate a failed console sign-in event.
- Understand how audit logs support security monitoring and incident investigation.

Tools and Services

- Amazon Web Services (AWS)
- AWS CloudTrail
- Amazon S3

Practical Activities

1. Explored CloudTrail Event History to inspect recorded account events.
2. Created a trail named "Nkay-CloudSecurity-Trail".
3. Configured the trail to deliver logs to an Amazon S3 bucket.
4. Generated a controlled failed console sign-in attempt.
5. Located and examined the corresponding "ConsoleLogin" event.

Key Learnings

- CloudTrail records account activity and API events for auditing and investigation.
- Failed sign-in events can provide useful evidence when investigating potential unauthorized access.
- Audit logs provide visibility into activity, but additional analysis is needed to identify suspicious patterns and determine appropriate responses.
- Effective cloud security requires more than collecting logs; it also involves detection, investigation, and response.

Evidence

Screenshots documenting the lab will be added to this repository after sensitive information has been removed.

Future Improvements

- Explore additional security-relevant CloudTrail events.
- Develop detection rules for suspicious account activity.
- Investigate how CloudWatch and other AWS security services can support alerting.
- Use these foundational skills toward a future cloud security monitoring project.

Disclaimer

This project was conducted in my own AWS learning environment for educational purposes. The failed sign-in test was intentional and controlled.

Author

Cybersecurity student learning AWS and cloud security through hands-on projects.
