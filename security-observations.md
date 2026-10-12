# Security Observations

## What I Observed
- AWS CloudTrail recorded a failed console sign-in as a `ConsoleLogin` event.
- The event details helped me investigate the sign-in result.
- The trail was configured to deliver logs to Amazon S3.

## What a Security Analyst Should Check
- Whether there are repeated failed sign-in attempts.
- Whether a successful sign-in follows multiple failures.
- Whether the source IP address and login timing are unusual.
- Whether other suspicious account activities occur around the same time.

## Important Limitation
A failed sign-in does not automatically mean an account has been attacked. Analysts should investigate the surrounding evidence before drawing conclusions.

## Next Learning Goal
Learn how to detect suspicious sign-in patterns and generate security alerts using AWS services.
