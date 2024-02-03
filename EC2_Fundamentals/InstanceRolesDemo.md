### Random commands

aws --version

aws iam list-users

Never ever enter access key and secret access key into the aws cli
these crendentials  should nbever be enterd into an ec2 instance.
Insteqad use IAM roles, with required policies attached.
