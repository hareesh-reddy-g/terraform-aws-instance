# AWS EC2 Instance

This module creates EC2 instance.

### Inputs

* ami_id - (Optional) Defaults to ```ami-09c813fb71547fc4f```
* instance_type - (Required) User must supply instance type either t2.micro or t3.micro or t3.small
* sg_ids - (Required) user must supply a list of security group IDS to attach Ec2 instance
* tags - (Optional) user can supply the tags attach to EC2 instance

### Outputs

* public_ip - Public IP of the instance created
* private_ip - private IP of the instance created
* instance_id - Instance ID created

