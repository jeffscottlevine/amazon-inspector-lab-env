The Amazon CloudFormation template in this repository creates a demo environment for Amazon Inspector.  It creates
a VPC with a public subnet and then sets up Amazon EC2 instances with the
supported Windows and Amazon Linux OS variants along with the Amazon
Inspector target groups and templates.  It does not start the actual
assessments.

The main parameters are:

* An Amazon EC2 key pair

* An Availability Zone

* An Amazon EC2 instance type

* The CIDR block for RDP/SSH permissions for the security groups.  The default is 0.0.0.0/32 which doesn't correspond to a legitimate address.

Note: Although I work for Amazon Web Services, this repository does not express
the position of Amazon Web Services. It is a personal contribution.
