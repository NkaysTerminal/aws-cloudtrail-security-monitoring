
# CloudTrail Failed Sign-In Investigation

## Objective
To investigate a controlled failed AWS console sign-in using AWS CloudTrail.

## Service Used
AWS CloudTrail

## Event Investigated
- Event name: `ConsoleLogin`
- Result: Failed sign-in
- Investigation location: CloudTrail Event History

## Investigation Process
1. Opened CloudTrail Event History.
2. Located the `ConsoleLogin` event.
3. Opened the event details.
4. Checked the recorded sign-in result.

## Security Significance
Failed sign-in events can help security analysts investigate possible unauthorized access. However, one failed sign-in alone does not prove malicious activity.

## Conclusion
This lab demonstrated how AWS CloudTrail records account activity and how its event details can support an initial security investigation.

