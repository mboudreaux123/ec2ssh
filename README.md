# ec2ssh

A bash/zsh function to SSH into an EC2 instance quicker.

NOTE: Won't work if ec2 default username is changed from "ec2-user".

## Usage

Syntax:

```
ec2ssh ec2-ip-address path-to-keyfile
```

Example:

```
ec2ssh 192.168.1.1 ~/Downloads/key.pem
```
