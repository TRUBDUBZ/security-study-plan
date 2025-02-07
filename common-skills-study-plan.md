# Common Skills for Cybersecurity Study Plan

Whichever domain you choose in Cybersecurity umbrella like Application Security, Cloud Security or DevSecOPs; there are common skills which one must learn to excel in this domain.
I have explained [what you need to learn in those common skills here](https://github.com/jassics/cybersecurity-skills-career-roadmap/blob/master/common-skills.md)

So, I will explain from where to study and how much time you should devote to learn those concepts in these common skills, so that you are job ready and interview ready too!

**These 5 common skills are:**

1. -[ ] [Linux](#linux-basics-and-linux-commands) (1 week)
2. -[ ] [Networking](#networking-fundamentals) (1 week)
3. -[ ] [Programming](#programming-skills) (2 weeks)
4. -[ ] [Cloud Computing Fundamentals](#cloud-computing) (2 weeks)
5. -[ ] [git commands](#git-commands) (1 week)

## Linux basics and Linux Commands (1-2 weeks)
It should not take more than a week to be comfortable with basic linux commands to do day to day activities.
Once you are comfortable with basic command, go fo networking and other security related command in little depth.

Bug bounty hunters, Penetration testers and almost all tech focused security professionals use O.S. like Kali Linux, Parrot OS or BlackArch Linux which have lots of security tools to play with.
But for that you would need to know the basic working of Linux and commands.

### Some common commands I can think of are:
- ls, 
- cd, 
- cp, 
- scp, 
- cat, 
- uname, 
- less, 
- more, 
- sort, 
- ssh, 
- mv, 
- du, 
- df, 
- mount, 
- mkdir, 
- who, 
- locate, 
- chmod, 
- chown, 
- sudo, 
- top, 
- kill, 
- grep, 
- find, 
- sed, 
- awk, 
- ps, 
- zip, 
- tar, 
- service/systemctl

What else you can think of as common linux commands for everyone?

### Beyond basics commands for security professionals (mainly AppSec and Pentesters) are:
1. netcat
2. nslookup
3. host
4. dig
5. netstat
6. traceroute
7. nmap
8. nikto
9. fierce
10. dirb
11. install/uninstall/update/upgrade
12. find 
13. grep
14. ifconfig
15. learn basics of regular expression as well.
16. start and stop services
17. basic understand of /opt /tmp and log, server locations
18. comfortable in running scripts written in various languages like python, ruby, go etc.

### Books
1. [Linux Basics for Hackers: Recommended](https://www.amazon.in/Linux-Basics-Hackers-Networking-Scripting/dp/1593278551/)
2. [The Linux Command Line](https://www.amazon.in/Linux-Command-Line-2nd-Introduction/dp/1593279523/)
3. [How Linux works](https://www.amazon.in/How-Linux-Works-Brian-Ward/dp/1718500408/)

### Courses
1. [Introduction to Linux Commands and Scripting](https://www.coursera.org/learn/hands-on-introduction-to-linux-commands-and-shell-scripting)
2. [Linux Fundamentals for Security Practitioners: Recommended](https://www.cybrary.it/course/linux-fundamentals-for-security-practitioners/)

### Videos
1. [Linux for Ethical Hackers: Recommended](https://www.youtube.com/watch?v=lZAoFs75_cs)
2. [Hacking for beginners: Linux and Common Commands](https://www.youtube.com/watch?v=lZAoFs75_cs)
3. [50 most popular Linux and Terminal Commands](https://www.youtube.com/watch?v=ZtqBQ68cfJc)

## Networking Fundamentals
Except Audit and Compliance role, I assume almost every security professionals need to have basic to intermediate understanding of Computer Network to excel in its domain.

What to learn and what are interview questions related to this are already mentioned in [what you need to learn in those common skills](https://github.com/jassics/cybersecurity-skills-career-roadmap/blob/master/common-skills.md)

### I will brief the common concepts here anyways just for quick reference:
1. IPv4/IPv6
2. concept of CIDR 
3. Public vs Private IPs
4. DMZs
5. Zero Trust Networks
6. Common ports and protocols like 22, 25, ssh, https and so on.
7. Understanding of common cryptographic modules and functions
8. How DNS works
9. How SSL works
10. What are the common network threat around these
11. MiTM
12. Network sniffing
13. Various TCP attacks
14. DoS and DDoS attacks and its preventions
15. Common ideas on firewall or Software defined networks
16. Basic network troubleshooting like why internet is slow or down, why wi-fi is not working, open networks issues et al.

### Books
1. [See if you know basics as mentioned in this presentation](https://www.ece.uvic.ca/~itraore/elec567-13/notes/dist-03-4.pdf)
2. [Computer Networking: A Top-Down Approach by Kurose and Ross: Recommended](https://www.amazon.in/Computer-Networking-Top-Down-Kurose-James/dp/9332585490/r)
3. [Networking All-in-One For Dummies](https://www.amazon.in/Networking-All-One-Dummies-Doug/dp/1119471605)

### Videos
1. [Basics of Computer Networking](https://www.youtube.com/watch?v=0j6-QFnnwQk)
2. [Computer Networking Full Course: Recommended](https://www.youtube.com/watch?v=qiQR5rTSshw&t=14s)

### Courses
1. [Computer Networking by georgia Tech on Udacity: Recommended](https://www.udacity.com/course/computer-networking--ud436)
2. [Bits and Bytes of Computer Networking by Google on Coursera](https://www.coursera.org/learn/computer-networking)

## Programming Skills
Recently, it has become a mandatory skills for any tech security job roles to have a decent knowledge of at least one programming languages.
Common Programming languages that attracts security folks are:

1. Python (recommended)
2. Go (gaining popularity)
3. Ruby

What actually you should try when you are learning any of these programming languages:

1. Learn basic concepts
2. Try few basic projects like 
   1. connecting to db and get some data
   2. extracting data from a webpage
   3. display some info from cloud like AWS Instance details region wise
   4. automate few security stuffs like docker monitor, get public IPs, server details etc
   5. See if you can find any task related to csv, json
   6. Learn the use of crypto modules
   7. simulate few linux or other commands to be comfortable with the language like small nmap simulation
3. Understand OOP concept and at least you should understand others code comfortably
4. Try to review source code form security perspective
5. [Read Python Security Best Practices](https://snyk.io/blog/python-security-best-practices-cheat-sheet/)

### Books
1. [Learn Python 3 the Hard Way](https://www.amazon.in/Learn-Python-Hard-Way-Introduction/dp/0134692888/) - Recommended
2. [Violent Python](https://www.amazon.in/Violent-Python-Cookbook-Penetration-Engineers/dp/1597499579)
3. [Black Hat Python](https://www.amazon.in/Black-Hat-Python-2nd-Programming/dp/1718501129/) - Must Read
4. [Full Stack Python Security](https://www.manning.com/books/full-stack-python-security) - Must for AppSec Professionals
5. [Masterting Python for Networking and Security](https://www.oreilly.com/library/view/mastering-python-for/9781788992510/)

### Videos
1. [Python Security Best Practices](https://www.youtube.com/watch?v=ZDzDpapddPg)
2. [Security Checks for Python Code](https://www.youtube.com/watch?v=zVIfH89oWno)
3. [Intro to Python for Security Professionals](https://www.youtube.com/watch?v=pFMzgPGfl4w)

### Courses
1. [Python for Cybersecurity Specialization](https://www.coursera.org/specializations/pythonforcybersecurity)
2. [SEC573: Automating Information Security with Python](https://www.sans.org/cyber-security-courses/automating-information-security-with-python/)
3. [Python for Pentesters](https://www.pentesteracademy.com/course?id=1)

## Cloud Computing 
Cloud Computing is everywhere these days be it Industrial, Pharma, Finance, IT etc. 
Sooner or later, it will be a mandatory skills to have for any cybersecurity job roles.

Learn any of the famous CSPs like AWS, Azure or GCP and 

1. try to understand the use of it to solve various traditional challenges and 
2. then try to understand what are the new security challenges added because of Cloud concepts. 
3. Understand various service and deployment models
4. Shared Security Responsibility
5. Microservices
6. IAM functionalities (Must understand very well)
7. Data Encryption
8. Cloud Networking concept is very important to succeed in Cloud Security

There are separate plans for Cloud Security Study Plan as listed below:

1. [AWS Security Study Plan](aws-security-study-plan.md)
2. [Azure Security Study Plan](azure-security-study-plan.md)
3. [GCP Security Study Plan](gcp-security-study-plan.md)

### Books
1. Cloud Computing for Dummies
2. [AWS in Action](https://www.manning.com/books/amazon-web-services-in-action)

### Videos
1. [Cloud Computing Playlist by Fkexmind](https://www.youtube.com/playlist?list=PLRTsCutScZnyfH0NLaOJxDEn2ZWZuBlup)
2. [What is Cloud Computing by AWS](https://www.youtube.com/watch?v=mxT233EdY5c)
3. [Inside a Cloud Data Center](https://www.youtube.com/watch?v=XZmGGAbHqa0)

### Courses
1. [Introduction to Cloud Computing by IBM on Coursera](https://www.coursera.org/learn/introduction-to-cloud)
2. [Micro Masters Program in Cloud Computing](https://www.edx.org/micromasters/usmx-umgc-cloud-computing)


## git commands
You must understand any of the Version Control Software and git is one of the famous one at present.
Don't go for gui version like sourcetree rather try to learn and understand common git commands at terminal level.

### Most basic git commands to understand are:
1. git clone
2. git add
3. git commit
4. git branch
5. git pull
6. git fetch
7. git merge
8. git push
9. git config
10. git log

There are many job roles/titles which make it as a mandatory skill, such as:
1. AppSec
2. Pentest
3. DevSecOps
4. API Security

### Books
1. [Pro Git by Appress](https://git-scm.com/book/en/v2) - Highly recommended
2. [Beginning git and github by Apress](https://techviewleo.com/best-books-to-learn-git-version-control/)
3. [github cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)

### Videos
1. [git and github for beginners - crash course by freecodecamp](https://www.youtube.com/watch?v=RGOj5yH7evk)
2. [git fundamentals for beginners - full course for free by Flexmind](https://www.youtube.com/watch?v=zyB-6U7DRKI)

### Courses
1. [Git Fundamentals for everyone on Udemy](https://www.udemy.com/course/git-basics-for-everyone/)
2. [Version Control with Git by Atlassian on Coursera](https://www.coursera.org/learn/version-control-with-git)
3. [Learn git and github by codecademy](https://www.codecademy.com/learn/learn-git)

