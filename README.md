# Check_mk and AWS
I stood up a `check_mk` container to monitor my internal network.  I see it has `AWS` and `sts:assume` capabilities.

# What's created

This template creates the following:

- IAM user with API access
- IAM Role for the user to assume into
- Appropriate IAM Policy for the role
- API Access Key and Secret stored in param store

# Helpful links:

- https://docs.checkmk.com/latest/en/monitoring_aws.html

