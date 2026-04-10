#  Linux for DevOps 

---

##  Module 0: Introduction, Setup & DevOps Context

### 0.1 Linux in DevOps Ecosystem

* Why Linux dominates DevOps, Cloud, Containers
* Where you will use Linux (Servers, Docker, Kubernetes)

### 0.2 Linux vs Windows (Practical View)

* CLI vs GUI mindset
* Why terminal skills matter

### 0.3 Environment Setup

* Local setup options (VM / WSL)
* Cloud setup (EC2 or VM)
* Connecting via SSH

### 0.4 Terminal Basics

* Understanding terminal prompt
* Command structure (command + options + arguments)
* Getting help (`man`, `--help`)

---

##  Module 1: File System & Navigation

### 1.1 Linux File System Structure

* Root (`/`) concept
* Key directories:

  * `/home`
  * `/etc`
  * `/var`
  * `/tmp`
  * `/usr`

### 1.2 Navigation Commands

* `pwd`
* `cd` (absolute vs relative paths)
* Tab completion

### 1.3 Listing Files & Directories

* `ls`
* Flags: `-l`, `-a`, `-lh`

### 1.4 File & Directory Operations

* `mkdir`
* `rm` (with caution)
* `cp`
* `mv`

### 1.5 Hidden Files & Dot Files

* `.env`, `.bashrc`
* Importance in DevOps configs

---

##  Module 2: Permissions, Users & Ownership

### 2.1 File Permission Basics

* Read (r), Write (w), Execute (x)
* Permission structure

### 2.2 Modifying Permissions

* `chmod` (numeric & symbolic)

### 2.3 Ownership Management

* `chown`
* `chgrp`

### 2.4 Users & Groups

* Creating users
* Group management

### 2.5 Sudo & Privileges

* `sudo`
* Root vs normal user

---

## ⚙️ Module 3: Process Management & System Monitoring

### 3.1 What is a Process?

* Foreground vs background

### 3.2 Viewing Processes

* `ps`
* `top` / `htop`

### 3.3 Managing Processes

* `kill`
* `kill -9`

### 3.4 System Resource Monitoring

* CPU, Memory basics
* Identifying heavy processes

### 3.5 Background Jobs

* `&`, `jobs`, `fg`, `bg`

---

##  Module 4: Networking Basics for DevOps

### 4.1 Networking Fundamentals (Practical)

* IP, Port, Protocol basics

### 4.2 Connectivity Testing

* `ping`

### 4.3 API & Web Requests

* `curl`
* `wget`

### 4.4 Port & Service Checks

* `netstat` / `ss`

### 4.5 Debugging Network Issues

* Service not reachable scenarios

---

##  Module 5: Package Management

### 5.1 Package Managers Overview

* `apt` vs `yum`

### 5.2 Installing Packages

* Installing Nginx / Git

### 5.3 Updating & Removing Packages

* `update`, `upgrade`, `remove`

### 5.4 Verifying Installations

* Checking service status

---

##  Module 6: Logs & Debugging

### 6.1 Importance of Logs in DevOps

* Why logs matter in production

### 6.2 Log File Locations

* `/var/log`

### 6.3 Viewing Logs

* `cat`
* `less`
* `tail`

### 6.4 Real-Time Monitoring

* `tail -f`

### 6.5 Searching Logs

* `grep`

### 6.6 Debugging Workflow

* Step-by-step troubleshooting approach

---

##  Module 7: Shell Scripting Fundamentals

### 7.1 Introduction to Shell Scripting

* Why scripting is critical in DevOps

### 7.2 Writing Your First Script

* Shebang (`#!/bin/bash`)
* Running scripts

### 7.3 Variables

* Declaring and using variables

### 7.4 Conditional Logic

* `if`, `else`, `elif`

### 7.5 Loops

* `for`, `while`

### 7.6 Functions

* Reusable scripts

### 7.7 Scheduling Jobs

* `cron`

---

##  Module 8: Mini Project (Real DevOps Scenario)

### 8.1 Project Setup

* Launch Linux server

### 8.2 Application Setup

* Install Nginx
* Deploy simple app

### 8.3 Monitoring & Logs

* Check logs
* Debug issues

### 8.4 Automation

* Write script to monitor service

### 8.5 Final Validation

* End-to-end testing

---

#  Final Output of This Course

After completing this TOC, student can:

Navigate Linux confidently
Debug issues using logs & commands
Understand server behavior
Write basic automation scripts
Support DevOps tools (Docker, K8s, CI/CD)

