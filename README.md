# AWS

## EC2 Instance

1. Create one Ec2 instance with new security group encryption
2. Then we create snapshot of ec2 root volumes 
3. Then we create image using snapshot of ec2 instance 
4. AMI image use to create the new ec2 instance 

## EC2 Instance with encrypted

1. create One Ec2 Instance with new security group encryption
2. Then we have to create snapshot of ec2 using root volumes
3. THen we have create copy of snapshot of ec2 in there we have click encrypted box to make encrypted volumes
4. Then we have to create image using encrypted snapshot of ec2 instance 
5. AMI image use to create the new template ec2 instance and it will show automatically encrpyted id in ec2 


## Extra Protection againdt web attack using conditions you specify. You can define conditions by using characteristics of web request such as:

1) Ip Addresses that request originate from.
2) Country that request originate from
3) Values that request headers
4) String that appear in requests, etiher specific strings or string that match regular expression (regex) Patterns.
5) Length of requests.
6) Presence of sql code that is likely to be malicous (Known as sql injection).
7) Presence of a script that is likely to be malicious (Known as cross-site scripting).
