# CyberSecurity Home Labs
This repository showcases my cybersecurity home lab projects, which are a collection of hands-on experiments, labs, and write-ups I’ve built to explore security concepts. Everything here runs in a self-contained environment (virtual machines, Docker, and other lab setups), so I can safely simulate attacks, defenses, and monitoring without touching production systems.

#Table of Contents
____________________________________________________________________________________
#LAB 2
[Lab 2 – User Management and Permissions](Lab2.md)
This lab explains how to manage user and groups, switch between regular users and root, to create and delete users, modify passwords, and grant sudo privileges. Also explores file permissions, changing permissions using chmod, and manage Access Control List using setfacl.

[Lab 3 – Environment Variable and Set-UID Program Lab](Lab3.md)
This lab explores environment variables, how they work, affect, and process programs. It shows how to create, modify, and remove environment variables, and how they are passed from parent to child processes. It also shows how execve() requires environment variables to be passed manually, while system() handles them automatically through the shell. It shows how to manipulate the PATH variable to run my own program instead of the intended one, showing its vulnerability.