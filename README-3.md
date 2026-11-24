AWS Monitoring and Maintenance

1. Monitoring and Status Checks

The portfolio website is hosted using Amazon S3 Static Website Hosting.

The following checks are used to monitor the website:

- Open the website endpoint in a browser to verify availability.
- Check whether website files are present in the S3 bucket.
- Verify that the website loads correctly without access errors.

2. Logging and Monitoring

Amazon CloudWatch can be used for monitoring AWS resources.

Potential monitoring activities include:

- Monitoring S3 storage metrics.
- Reviewing available AWS service metrics.
- Monitoring website availability through suitable monitoring tools.

Note: CloudWatch monitoring has been documented as a proposed approach. No CloudWatch alarm has been deployed in this project.

3. Simple Alert Idea

A future monitoring setup could send an email notification if the website becomes unavailable or an important service metric crosses a defined threshold.

4. Cost Management Checklist

- Monitor AWS billing regularly.
- Remove unused files and resources.
- Avoid unnecessary paid AWS services.
- Check storage usage periodically.
- Review AWS Free Tier eligibility and usage.

5. Security Checklist

- Keep private information out of the public S3 bucket.
- Allow only necessary public read access for website files.
- Never upload passwords, secret keys, or personal documents.
- Review bucket permissions regularly.
- Protect AWS account credentials with MFA.

Conclusion

The portfolio website was successfully deployed using Amazon S3 Static Website Hosting. Basic status checks, monitoring concepts, alert planning, cost management, and security practices have been documented.
