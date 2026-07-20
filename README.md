# Shell Scripting Zero to Hero 🐚

A complete hands-on guide to mastering Bash Shell Scripting from beginner to advanced level.

This repository documents my journey of learning Bash scripting through practical examples, automation tasks, system administration projects, and real-world DevOps use cases.

---

# 📖 Table of Contents

- Introduction
- What is Shell Scripting?
- Why Learn Bash?
- Prerequisites
- Getting Started
- Variables
- User Input
- Operators
- Conditional Statements
- Loops
- Functions
- Arrays
- String Operations
- File Operations
- Command Line Arguments
- Exit Codes
- Error Handling
- Logging
- Scheduling with Cron
- Automation Projects
- Best Practices
- Repository Structure
- Learning Roadmap
- Resources
- License
- Author

---

# 📌 Introduction

Shell scripting is one of the most valuable skills for Linux System Administrators, DevOps Engineers, Cloud Engineers, and Site Reliability Engineers (SREs).

Bash scripts automate repetitive tasks, simplify server administration, and improve productivity.

This repository contains practical examples, exercises, and projects designed to build real-world scripting skills.

---

# 🚀 What You'll Learn

- Bash fundamentals
- Writing executable scripts
- Variables
- Reading user input
- Conditional statements
- Loops
- Functions
- Arrays
- File processing
- Process management
- Error handling
- Logging
- Cron jobs
- Linux automation
- DevOps scripting

---

# 🛠 Topics Covered

## Bash Basics

- Shebang
- Comments
- Script execution
- Permissions

Example:

```bash
#!/bin/bash

echo "Hello World"
```

---

## Variables

```bash
name="Nozel"

echo $name
```

---

## User Input

```bash
read -p "Enter your name: " username

echo "Welcome $username"
```

---

## Arithmetic Operations

```bash
a=10
b=20

echo $((a+b))
```

---

## Conditional Statements

```bash
if [ $age -ge 18 ]
then
    echo "Adult"
else
    echo "Minor"
fi
```

---

## Case Statements

```bash
case $option in
1)
echo "Install"
;;
2)
echo "Update"
;;
*)
echo "Invalid"
;;
esac
```

---

## Loops

### For Loop

```bash
for i in {1..5}
do
echo $i
done
```

### While Loop

```bash
count=1

while [ $count -le 5 ]
do
echo $count
((count++))
done
```

---

## Functions

```bash
greet() {
    echo "Hello $1"
}

greet Nozel
```

---

## Arrays

```bash
fruits=("Apple" "Orange" "Banana")

echo ${fruits[0]}
```

---

## File Operations

- touch
- cat
- grep
- sed
- awk
- cut
- sort
- uniq
- head
- tail

---

## Process Management

- ps
- top
- kill
- jobs
- nohup
- bg
- fg

---

## Logging

```bash
echo "$(date) Backup completed." >> backup.log
```

---

## Error Handling

```bash
if [ $? -eq 0 ]
then
    echo "Success"
else
    echo "Failed"
fi
```

---

## Cron Jobs

Example:

```bash
0 2 * * * /home/user/backup.sh
```

Runs every day at 2 AM.

---

# 💻 Real-World Automation Projects

- Automatic Backup Script
- User Creation Script
- Password Generator
- Server Health Monitor
- Disk Usage Monitor
- CPU Monitoring
- Memory Monitoring
- Log File Analyzer
- Nginx Installer
- Apache Installer
- Docker Installer
- SSL Certificate Checker
- Website Availability Monitor
- Database Backup Automation
- AWS CLI Automation Scripts

---

# 📂 Repository Structure

```
shell-scripting-zero-to-hero/

├── basics/

├── variables/

├── conditions/

├── loops/

├── functions/

├── arrays/

├── file-operations/

├── automation/

├── projects/

├── exercises/

├── cheatsheets/

├── images/

└── README.md
```

---

# 🧪 Hands-on Labs

- Build a Calculator
- Password Generator
- Backup Automation
- User Management Script
- Server Monitoring
- Log Analysis
- Cron Automation
- Process Monitoring
- Service Health Check
- Package Installation Automation

---

# 🚀 Final Projects

- Linux Server Automation Toolkit
- DevOps Utility Scripts
- Automated Deployment Script
- Monitoring Toolkit
- Backup & Restore System
- Server Hardening Script
- Log Management System
- Interactive Linux Administration Menu

---

# 🎯 Learning Goals

- Master Bash Scripting
- Automate Linux Administration
- Improve Problem-Solving Skills
- Build Reusable Automation Scripts
- Prepare for DevOps Roles
- Develop Production-Ready Scripts

---

# ⭐ Best Practices

- Write readable scripts
- Use meaningful variable names
- Add comments where necessary
- Validate user input
- Handle errors properly
- Test scripts before production
- Follow consistent formatting
- Keep scripts modular
- Log important events
- Secure sensitive information

---

# 📚 Recommended Resources

- GNU Bash Manual
- Bash Reference Guide
- Linux Documentation Project
- ShellCheck
- ExplainShell
- TLDR Pages
