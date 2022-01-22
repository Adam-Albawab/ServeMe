# ServeMe-System
These labs cover some of the most common vulnerabilities and attacks exploiting these vulnerabilities. All the labs are presented in the form of PDF files, containing some screenshots.

## Table of Contents 

- [Getting Started](#getting-started)
- [Motivation](#motivation)
- [List of Attacks](#list-of-attacks)
- [Key Learnings](#key-learnings)
- [References](#references)


## Getting Started

These instructions will get you to set up the virtual environment and run the code to host the website on your machine.

Step 1: Download the src file and its contents \
Step 2: Open your terminal \
Step 3: Navigate to the src folder \
Step 4: Run the following code in your terminal \

Step 5: python -m venv "virtual environment name of your choosing" \
  
MacOS: 
Step 6: source "environment-name"/bin/activate \
Step 7: export FLASK_APP=serveme \
Step 8: export FLASK_DEBUG=1 \
 
Windows: 
Step 6: "environment-name"\Scripts\Activate \
Step 7: set FLASK_APP=serveme \
Step 8: set FLASK_DEBUG=1 \

Step 9: pip install -r requirements.txt

Step 10: flask run

## Motivation
The labs were completed as a part of the Computer Security (CSE643) course at Syracuse University. The course is well structured to understand the concepts of Computer Security.

## List of Attacks

1. **Environment Variable and Set-UID Vulnerability**
>*Description:* Set-UID is an important security mechanism in Unix operating systems. When a Set-UID program runs, it assumes the owner's privileges. For example, if the program's owner is root, then when anyone runs this program, the program gains the root's privileges during its execution. This can be very well exploited, as seen in the lab. The lab also demonstrates the effect of environment variables on the behavior of Set-UID programs.

2. **Buffer Overflow Vulnerability**
>*Description:*  Buffer overflow is defined as the condition in which a program attempts to write data beyond the boundaries of pre-allocated fixed-length buffers. This vulnerability can be utilized by a malicious user to alter the flow control of the program, even execute arbitrary pieces of code. The task in this lab is to develop a scheme to exploit the buffer overflow vulnerability and finally gain the root privilege.
