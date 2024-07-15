# DG8245W2-10_DOS
DOS exploit against DG8245W2-10 gateway from Huawei web admin login page

#PLATFORM
LINUX

#TARGET APP
Huawei DG8245W2-10 home gateway (may be others) web admin login page.

#Description
If someone tries 3 incorrect passwords, they will be blocked for 60 seconds based on their IP address. If attackers manage to change their IP addresses and have more than 3 attempts with incorrect passwords, the website will block everyone for 60 seconds. This script will trigger this continuously, effectively causing a DoS attack on the page!

