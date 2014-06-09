Mutillidae-II-Amazon-EC2-Init-Script
====================================
Mutillidae II Amazon EC2 Deployment Script V1.0
Last update: 06/09/14

Written by SkeyeLlama 
	http://l4m3rs.blogspot.com
	https://twitter.com/SkeyeLlama

Automated configuration script for Amazon Linux Instances
Inspiration and reference:
	AWS LAMP sample script http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/user-data.html
	AWSlab by @averagesecguy https://github.com/averagesecurityguy/AWSlab

Mutillidae is accessed at http://host/mutillidae/ after script completion.

Automatic configuration script to launch a Mutillidae II instance using an Amazon Linux AMI

PLEASE NOTE: Line 50 changes the default connection restriction for Mutillidae.
Mutillidae restricts access using .htaccess. By default it restricts incoming connections to 
the localhost and 192.168.0.0/16 addresses. This script modifies .htaccess to allow connections
from any address. 

Ensure your EC2 security group is properly configured to prevent public access to your Mutillidae instance! 
