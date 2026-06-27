# cybersecurity-journey-2026
# From Zero to Something

Hi, I'm Anubhav.

I started this repository after discovering IIT Kanpur's B.Cyber program.

My goal is to learn cybersecurity, programming, networking, and problem-solving from the ground up.
I use online resources, documentation, and AI tools to plan learning roadmaps and clarify concepts. All projects in this repository are designed, implemented, tested, and debugged by me as part of my learning process.

## Progress

## Background
- ISC Computer Science (Java)
- Strong foundation in mathematics and problem solving

## Current Learning Focus
- Python Fundamentals
- Networking Basics
- Linux Fundamentals
- Cybersecurity Fundamentals

### Day 1
- Created GitHub account
- Created repository
- Started learning cybersecurity basics
- Completed TryHackMe: Intro to Offensive Security
- Completed TryHackMe: Defensive Security Intro
- Completed TryHackMe: Careers in Cybersecurity

### Day 2
- More on Python (Revision)
- Completed Project #1: Password Strength Checker
- Continuing with TryHackMe
- Completed TryHackMe: What is Networking?

### Day 3
- Started Bandit on OverTheWire to sharpen terminal skills
- Completed OverTheWire Bandit Levels upto level 11
- Learned and practiced:
  - SSH login to remote server
  - File navigation (ls, cd)
  - Hidden/special files handling
  - File search using find
  - Reading files using cat
  - Text processing using pipelines (|)
  - Sorting and filtering data using sort and uniq
  - Pattern searching using grep
  - File type identification using file
  - Basic encoding/decoding concepts:
    - base64 decoding
    - ROT13 transformation using tr
  - Working with compressed files (gzip concept introduced)
  - Understanding process control basics (jobs, Ctrl+Z vs Ctrl+C)
- Current Focus: Trying to figure out Level 12 by investigating binary files and extracted data
  
### Day 4
- More on Python (File Handling, Dictionaries)
- Completed Project #2: Log Analyzer

### Day 5
- Continuing with OverTheWire Bandit
- Completed OverTheWire Bandit level 12 to level 16
- Learned and Practiced:
  - File Analysis & Data Extraction:
    - Investigated binary file structures and embedded data
    - Converted hexadecimal dumps back to binary using xxd
    - Extracted data from multiple nested archive and compression formats
    - Practiced analysis of unknown files rather than relying on file extensions
  - Compression & Archiving Concepts: gzip, bzip2, tar archives:
    - Learned how different compression and archive formats interact
    - Practiced extracting data from multiple layers of compressed files
  - Networking & Service Enumeration
    - Discovered open ports on localhost using nmap
    - Learned the difference between port scanning and service detection
    - Performed service fingerprinting using nmap -sV
    - Distinguished between plain TCP services and SSL/TLS-enabled services
  - SSL/TLS Fundamentals:
    - Connected to encrypted services using openssl s_client
    - Interpreted TLS handshake output
    - Observed certificates, session tickets, and encrypted connections in practice
    - Learned how to communicate with services running over TLS
  - Authentication & Access Control:
    - Submitted credentials to network services
    - Checked multiple services to find the correct one
    - Retrieved an RSA private key from a remote service
    - Used SSH public-key authentication instead of passwords
    - Logged into the next level using a private key
  - Cybersecurity Concepts Practiced
    - Information gathering and investigation of unknown systems
    - Discovering open network ports and available services
    - Identifying service types through network probing
    - Understanding encrypted network communication (SSL/TLS)
    - Authenticating with passwords and SSH keys
    - Working with RSA private keys
    - Systematic troubleshooting and problem-solving

## Day 6
- Continuing with OverTheWire Bandit
- Completed OverTheWire Bandit level 17 to level 23
- Learned and Practiced:
  - Using SSH to execute commands when a normal shell is restricted
  - Understanding how SetUID programs can run commands with another user's permissions
  - Creating local TCP listeners using nc(netcat)
  - Sending and receiving data between processes over localhost
  - Exploring scheduled tasks managed by cron
  - Reading cron configurations and following the scripts they execute
  - Understanding Bash variables and command substitution
  - Generating MD5 hashes and reproducing values used by scripts
  - Finding files whose names were generated automatically from known inputs
- Started Networking Basics from Cisco Networking Academy
- Completed Module 1: Communication in a Connected World
- Started Module 2: Network Components, Types, and Connections

## Day 7
- Planned to continue with new Bandit levels
- Had to re-complete OverTheWire Bandit Levels 1 to 23 after the password chain reset
- Good revision of Linux commands, file analysis, SSH, SSL/TLS, cron jobs and permission concepts
  
## Day 8
- Continuing with OverTheWire Bandit
- Completed OverTheWire Bandit Level 24
- Learned, Explored and Practiced:
  - How Linux cron jobs execute scripts under a different user
  - File ownership, permissions, and execution context
  - Commands like whoami, pwd, ls and cat to debug script behavior instead of repeatedly guessing
  - Gained experience with mktemp, temporary directories, and scheduled task automation
  - Learned that cron jobs run in a different environment than an interactive shell
- Today's biggest lesson wasn't the password — it was learning to debug systems methodically
- ### Reflection:
  - Bandit Level 23 took me nearly six hours... It was the first challenge where the real obstacle wasn't Linux syntax—it was understanding how a system behaves when a program runs under a different user and in a different execution environment. Although I eventually solved it...the more valuable takeaway was learning to debug methodically instead of repeatedly guessing...that mindset will be useful far beyond this challenge.
- Continued Networking Basics from Cisco Networking Academy
- Completed Module 2: Network Components, Types and Connections

## Day 9
- Continuing with OverTheWire Bandit
- Completed OverTheWire from level 25 to level 27
- Learned, Explored and Practiced:
  - Bash Scripting & Automation:
    - Wrote a Bash script to automate brute-force attempts
    - Practiced for loops and command substitution
    - Learned to generate formatted output using printf
    - Understood format specifiers (%04d, %s) and zero-padding
    - Learned why printf is preferred over echo for structured output
  - Unix Pipelines & Standard Streams:
    - Used pipes (|) to connect independent programs together
    - Learned how one program's output becomes another program's input
    - Sent generated input directly to network services using nc
    - Understood that multiple requests can be sent over a single network connection
  - Interactive Network Communication:
    - Practiced communicating with services using netcat
    - Learned the difference between repeatedly creating connections and maintaining one persistent connection
    - Automated interaction with a network service through shell scripting
  - Login Shells & Restricted Environments:
    - Investigated how Linux stores user login shells in /etc/passwd
    - Explored custom login shells and why not every user starts in /bin/bash
    - Read and analyzed a shell script that replaced the default login shell
    - Learned how the exec command replaces the current process instead of creating a child process
  - Working with Linux Pagers:
    - Learned how more behaves differently depending on terminal size
    - Investigated interactive features of more
    - Read the pager documentation to understand its features
  - Vim Exploration:
    - Entered Vim through more
    - Learned about Ex commands and Vim's interaction with external programs
    - Used Vim to obtain an interactive shell from a restricted environment
  - Executable Analysis:
    - Distinguished executable binaries from ordinary files
    - Used file to identify executable types
    - Used strings to inspect printable strings embedded inside ELF binaries
    - Learned how to investigate an unknown executable before running it
  - Linux Permissions & SetUID (SUID)
    - Explored Linux permission bits in detail
    - Learned the purpose of the Set User ID (SUID) permission
    - Understood how SUID programs execute with the file owner's privileges instead of the executing user's privileges
    - Executed commands through a SUID binary to access resources owned by another user
- ### Reflection:
  - Bandit Levels 25 and 26 were very different from previous levels...instead of focusing on Linux commands, they required understanding how Unix systems are designed. I spent several hours reading documentation, investigating shell scripts, experimenting with more and vim, analyzing executables, and understanding how permissions affected execution before finally solving them. The most valuable lesson wasn't learning a specific command — it was learning to investigate unfamiliar systems methodically and test my assumptions by experimenting instead of guessing.

## Planned Projects (To familiarize myself with python)
- Port Scanner

## Completed Projects (Code Available on the Repository)
- Password Strength Checker
- Log Analyzer
