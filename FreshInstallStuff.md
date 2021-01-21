#### Installing Kali Linux on AWS EC2 --- Tested on EC2 T2.Micro (EBS HDD Size 28 GB)

> 1. Remember -> Allow TCP 22 and other TCP ports in security groups
> 1. ssh -i [ec2 key.pem] kali@[ec2 Public IP] 
> 1. apt-get update && apt-get upgrade
> 1. apt-get dist-upgrade
> 1. apt-get install xrdp
> 1. service xrdp start
> 1. service xrdp-sesman start
> 1. update-rc.d xrdp enable
> 1. SET PASSWORD for KALI by typing command: $ ssh passwd kali
> 1. apt update && sudo apt install kali-desktop-xfce
> 1. apt install kali-linux-large
