# terraform-RDS-tf-reusable
rds - vpc - vpc_security_group - aws_db_vpc_security_group - aws_db_subnet_group - ++
Go to /envtfvars/Dev.tfvars and enter your values of choice before running the code. Developed in terraform v0.14+
Adjust the s3 backend too
the aws_db_security_group will not be created if your account does not have EC2 Classic. In any case, the rds db instance will come up in the vpc. So the aws_db_security_group is just a redundant capability to the code, just in case.
