# aws-tags
It is a common requirement to enforce tags and tag values in organizations. This can be done using SCPs and Tag policies under AWS Organizations.

## Service Control Policies
SCPs can be used to enforce tags during resource creation.

## Tag Policies
Tag policies can be used to:
- Enforce tagging policy (e.g. tag `environment` can have only `prod` and `dev`)
- Deny resource creation if tag is missing
- Deny users from deleting tags on AWS resources
Please note tag policies can't enforce the presence of a tag. This is done by SCPs.
