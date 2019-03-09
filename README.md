# AWS-CIS-alert

## Control of CIS v1.2.0

### Monitoring
1. Ensure a log metric filter and alarm exist for unauthorized API calls
2. Ensure a log metric filter and alarm exist for Management Console sign-in without MFA : [Console-slack](https://github.com/4ndersonLin/Console-slack)
3. Ensure a log metric filter and alarm exist for usage of "root" account : [Console-slack](https://github.com/4ndersonLin/Console-slack)
4. Ensure a log metric filter and alarm exist for IAM policy changes
5. Ensure a log metric filter and alarm exist for CloudTrail configuration changes : TBD
6. Ensure a log metric filter and alarm exist for AWS Management Console authentication failures : [Console-slack](https://github.com/4ndersonLin/Console-slack)
7. Ensure a log metric filter and alarm exist for disabling or scheduled deletion of customer created CMKs : TBD
8. Ensure a log metric filter and alarm exist for S3 bucket policy changes : [S3-slack](https://github.com/4ndersonLin/S3-slack)
9. Ensure a log metric filter and alarm exist for AWS Config configuration changes : TBD
10. Ensure a log metric filter and alarm exist for security group changes : [AWS Security Blog](https://aws.amazon.com/tw/blogs/security/how-to-automatically-revert-and-receive-notifications-about-changes-to-your-amazon-vpc-security-groups/)
11. Ensure a log metric filter and alarm exist for changes to Network Access Control Lists (NACL) : [Networking-slack](https://github.com/4ndersonLin/Networking-slack)
12. Ensure a log metric filter and alarm exist for changes to network gateways : [Networking-slack](https://github.com/4ndersonLin/Networking-slack)
13. Ensure a log metric filter and alarm exist for route table changes : [Networking-slack](https://github.com/4ndersonLin/Networking-slack)
14. Ensure a log metric filter and alarm exist for VPC change : [Networking-slack](https://github.com/4ndersonLin/Networking-slack)

## Additional alert
GuardDuty : It can cover multiple controls and enhance the security of AWS account : [Guardduty-slack](https://github.com/4ndersonLin/guardduty-slack)
SecurityHub : Provide multiple security service and 3rd-party service. TBD
AWS Health: The availability monitor of AWS account resource : [Health-slack](https://github.com/4ndersonLin/Health-slack)