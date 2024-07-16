# DOS attack against DG8245W2-10 Gateway from Huawei. On Web Admin Login Page

## Platform:

Linux

## Target App:

Huawei DG8245W2-10 home gateway (and possibly others) web admin login page.

## Description:

If someone tries 3 incorrect passwords, they will be blocked for 60 seconds based on their IP address. If attackers manage to change their IP addresses and have more than 3 attempts with incorrect passwords, the website will block everyone for 60 seconds. This script will trigger this continuously, effectively causing a DoS attack on the page!

## impact:

no administrative actions can be taken!

## disclamer:

For educational purposes only.

## POC:

https://github.com/user-attachments/assets/b636cb5b-def8-43a9-bbf0-9f225c150a03

