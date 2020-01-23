# mani
DevOps Questions & Exercises
information_source  This repo contains questions and exercises on various technical topics, sometimes related to DevOps and SRE :)

bar_chart  There are currently 834 questions

warning  You can use these for preparing for an interview but most of the questions and exercises don't represent an actual interview. Please read Q&A for more details

thought_balloon  If you wonder "How to prepare for a DevOps interview?", you might want to read some of my suggestions here

memo  You can add more questions and exercises by submitting pull requests :) You can read more about it here

DevOps
DevOps
Beginner baby
Advanced star	Jenkins
Jenkins
Beginner baby
Advanced star	Git
Git
Beginner baby
Advanced star	Ansible
Ansible
Beginner baby
Advanced star	Network
Network
Beginner baby
Advanced star	Linux
Linux
Beginner baby
Advanced star	Terraform
Terraform
Beginner baby
Advanced star	Docker
Docker
Beginner baby
Advanced star
coding
Coding
Beginner baby
Advanced star	Python
Python
Beginner baby
Advanced star	Go
Beginner baby
Bash
Shell Scripting
Beginner baby
Advanced star	kubernetes
Kubernetes
Beginner baby
Prometheus
Prometheus
Beginner baby
Advanced star	Mongo
Mongo
Beginner baby
sql
SQL
Beginner baby
Advanced star
Cloud
Cloud
Beginner baby
AWS
Beginner baby
Azure
Beginner baby
Google Cloud Platform
Beginner baby
openstack
OpenStack
Beginner baby
Advanced star	security
Security
Beginner baby
Advanced star	puppet
Puppet
Beginner baby
Advanced star	OpenShift
OpenShift
Beginner baby
Monitoring
Monitoring
Beginner baby
Elastic
Elastic
Beginner baby
Virtualization
Beginner baby
DNS
Beginner baby
Operating System
Beginner baby
Distributed
Distributed	General
Beginner baby
HR
HR
Testing
Testing	Databases
Databases	Design
Design	you
Questions you ask	Exercises
Exercises
DevOps

baby Beginner
What is DevOps?
What are the benefits of DevOps? What it can help us to achieve?
What are the anti-patterns of DevOps?
What is Continuous Integration?
What is Continuous Deployment?
What is Continuous Delivery?
What CI/CD best practices are you familiar with? Or what do you consider as CI/CD best practice?
What systems and/or tools are you using for the following?:
CI/CD
Provisioning infrastructure
Configuration Management
Monitoring & alerting
Logging
Code review
Code coverage
Tests
What are you taking into consideration when choosing a tool/technology?
Explain mutable vs. immutable infrastructure
What ways are you familiar with to deliver a software? What are the advantages and disadvantages of each method?
What is caching? How it works? Why is it important?
Explain stateless vs. stateful
Describe the workflow of setting up some type of web server (Apache, IIS, Tomact, ...)
Explain "Open Source"
Describe me the architecture of service/app/project/... you designed and/or implemented
What types of tests are you familiar with?
You need to install periodically the same package on different operating systems (Ubuntu, RHEL, ...). How would you do it?
SRE
Compare SRE to DevOps
What is Reliability? How does it fit DevOps?
What SRE team is responsible for?
What is an error budget?
What are MTTF (mean time to failure) and MTTR (mean time to repair)? What these metrics help us to evaluate?
What is a post-mortem meeting? Why is it important?
What is "infrastructure as code"? What implementation of IAC are you familiar with?
How do you manage build artifacts?
What Continuous Integration solution are you using/prefer and why?
What deployment strategies are you familiar with or have used?

star Advanced
Tell me how you perform plan capacity for your CI/CD resources (e.g. servers, storage, etc.)
How would you structure/implement CD for an application which depends on several other applications?
How do you measure your CI/CD quality? Are there any metrics or KPIs you are using for measuring the quality?
What is a configuration drift? What problems is it causing?
How to deal with a configuration drift?
Do you have experience with testing cross-projects changes? (aka cross-dependency)
Have you contributed to an open source project? Tell me about this experience
Jenkins

baby Beginner
What is Jenkins? What have you used it for?
What are the advantages of Jenkins over its competitors? Can you compare it to one of the following systems?
Travis
Bamboo
Teamcity
CircleCI
What are the limitations or disadvantages of Jenkins?
Explain the following:
Job
Build
Plugin
Slave
Executor
What plugins have you used in Jenkins?
Explain CI/CD and how you implemented it in Jenkins
What type of jobs are there? Which types have you used?
How did you report build results to users? What ways are you familiar with for reporting results?
You need to run unit tests every time a change submitted to a given project. Describe in details how your pipeline would look like and what will be executed in each stage
How to secure Jenkins?
Can you describe some of Jenkins best practices?
Describe how do you add new slaves to Jenkins

star Advanced
How to acquire multiple slaves for one specific build?
There are four teams in your organization. How to prioritize the builds of each team? So the jobs of team x will always run before team y for example
If you are managing a dozen of jobs, you can probably use the Jenkins UI. How do you manage the creation and deletion of hundreds of jobs every week/month?
What are some of Jenkins limitations?
How would you implement an option of a starting a build from a certain stage and not from the beginning?
Jenkins Dev
Do you have experience with developing a Jenkins plugin? Can you describe this experience?
Have you written Jenkins scripts? If yes, what for and how they work?
Cloud

baby Beginner
What is Cloud Computing? What is a Cloud Provider?
What are the advantages of cloud computing? Mention at least 3 advantages
What types of Cloud Computing are there?
Explain each of the following Cloud Computing Deployments:
Public
Hybrid
Private
What are the differences between Cloud Providers and On-Premise solution?
What is Serverless Computing?
AWS

baby Beginner
Global Infrastructure
Explain the following
Availability zone
Region
Edge location
IAM
What is IAM? What are some of its features?
True or False? IAM configuration is defined globally and not per region
What are Roles?
What are Policies?
S3
Explain what is S3 and what is it used for
What is a bucket?
True or False? A bucket name must be globally unique
What objects in S3 consists of? * Another way to ask it: explain key, value, version id and meta data in context of objects
Explain data consistency
Can you host dynamic websites on S3?. What about static websites?
What security measures have you taken in context of S3?
What is a storage class? What storage classes are you familiar with?
EC2
What is EC2? What is it used for?
What EC2 pricing models are there?
How to increase RAM for a given EC2 instance?
What is an AMI?
How many storage options are there for EC2 Instances?
What happens when an EC2 instance is stopped or terminated?
What are Security Groups?
How to migrate an instance to another availability zone?
What are spot instances?
CloudFormation
Explain what is CloudFormation
Costs
Are you familiar with Cost Explorer tool? Have you used it? What for exactly?
CloudFront
Explain what is CloudFront and what is it used for
Explain the following
Origin
Edge location
Distribution
What delivery methods available for the user with CDN?
True or False?. Objects are cached for the life of TTL
What is AWS Snowball?
Load Balancers
What types of load balancers are supported in EC2 and what are they used for?
AWS Security
What is the shared responsibility model? In other words, what AWS is responsible for and what the user is responsible for in regards to Security?
What is the AWS compliance program?
Explain what each of the following services is used for
AWS Inspector
AWS Artifact
AWS Shield
What is AWS WAF? Give an example of how it can used and describe what resources or services you can use it with
What AWS VPN is used for?
What is the difference between Site-to-Site VPN and Client VPN?
True or False? AWS Inspector can perform both network and host assessments
AWS Databases
What is Amazon RDS?
What are some features or benefits of using RDS?
What is AWS Redshift and how its different than RDS?
What do you if you suspect AWS Redshift performs slowly?
What is EBS?
What is Amazon ElastiCache? For what cases it used?
What is Amazon Aurora
What "AWS Database Migration Service" is used for?
AWS Networking
What is VPC?
What is an Elastic IP address?
Explain Security Groups and Network ACLs
Identify the service or tool
What would you use for easily creating similar AWS environments/resources for different customers?
Using which service, can you add user sign-up, sign-in and access control to mobile and web apps?
Which service would you use for building a website or web application?
Which tool would you use for choosing between Reserved instances or On-Demand instances?
What would you use to check how many unassociated Elastic IP address you have?
What service allows you to transfer large amounts (Petabytes) of data in and out of the AWS cloud?
What provides a virtual network dedicated to your AWS account?
What you would use for having automated backups for an application that has MySQL database layer?
What would you use to migrate on-premise Oracle database to AWS?
What would you use to check why certain EC2 instances were terminated?
AWS Misc
Explain what are the following services and give an use case example for each one them:
CloudTrail
CloudWatch
CloudSearch
Explain what is AWS Lambda
Network

baby Beginner
What is Ethernet?
What is a MAC address? What is it used for?
When is this MAC address used?: ff:ff:ff:ff:ff:ff
What is an IP address?
Explain subnet mask and given an example
What is a private IP address? What do we need it for?
Explain the OSI model. What layers there are? What each layer is responsible for?
For each of the following determine to which OSI layer it belongs:
Error correction
Packets routing
Cables and electrical signals
MAC address
IP address
Sessions between applications
3 way handshake
What delivery schemes are you familiar with?
What is CSMA/CD? Is it used in modern ethernet networks?
Describe the following network devices and the difference between them:
router
switch
hub
How does a router works?
What is NAT?
What is a proxy? How it works? What do we need it for?
What is TCP? How it works? What is the 3 way handshake?
How does SSL handshake work?
What is the difference between TCP and UDP?
True or False? TCP is better than UDP
What TCP/IP protocols are you familiar with?
Explain "default gateway"
What is ARP? How it works?
What is TTL?
What is DHCP? How it works?
What is SSL tunneling? How it works?
What is a socket? Where can you see the list of sockets in your system?
What is IPv6? Why should we consider using it if we have IPv4?
What is VLAN?
What is MTU?
True or False?. Ping is using UDP because it doesn't care about reliable connection
What is SDN?
What is ICMP? What is it used for?
What is NAT? How it works?
What is latency?
What is bandwidth?
Which factors affect network performances

star Advanced
Explain Spanning Tree Protocol (STP)
What is link aggregation? Why is it used?
What is Asymmetric Routing? How do deal with it?
What overlay (tunnel) protocols are you familiar with?
What is GRE? How it works?
What is VXLAN? How it works?
What is SNAT?
Explain OSPF
Explain Spine & Leaf
What is Network Congestion? What can cause it?
What can you tell me about UDP packet format? What about TCP packet format? How is it different?
Using Hamming code, what would be the code word for the following data word 100111010001101?
Linux

baby Beginner
What is your experience with Linux?
Explain what each of the following commands does and give an example on how to use it:
ls

rm

rmdir (can you achieve the same result by using rm?)

grep

wc

curl

touch

man

nslookup or dig

df

Running the command df you get "command not found". What could be wrong and how to fix it?
How do you schedule tasks periodically?
Have you scheduled tasks in the past? What kind of tasks?
Permissions
How to change the permissions of a file?
What does the following permissions mean?:
777
644
750
Explain what is setgid, setuid and sticky bit
You try to delete a file but it fails. Name at least three different reason as to why it could happen
What is systemd?
On a system which uses systemd, how would you display the logs?
Describe how to make a certain process/app a service
How do you kill a process in D state?
Debugging (Beginner)
What are you using for troubleshooting and debugging network issues?
What are you using for troubleshooting and debugging disk & file system issues?
What are you using for troubleshooting and debugging process issues?
What are you using for debugging CPU related issues?
You get a call from someone claiming "my system is SLOW". What do yo do?
Explain iostat output
How to debug binaries?
What kind of information one can find in /proc?
What is the difference between CPU load and utilization?
How you measure time execution of a program?
Kernel
How do you find out which Kernel version your system is using?
What is a Linux kernel module and how do you load a new module?
Explain user space and kernel space
Wildcards are implemented on user or kernel space?
What is KVM?
What is SSH key? How is it used?
What is the difference between SSH and SSL?
What is SSH port forwarding?
Explain redirection
What are wildcards? Can you give an example of how to use them?
What do we grep for in each of the following commands?:
grep '[0-9]{1,3}.[0-9]{1,3}.[0-9]{1,3}.[0-9]{1,3}' some_file
grep -E "error|failure" some_file
grep '[0-9]$' some_file
Tell me everything you know about the Linux boot process
What is an exit code? What exit codes are you familiar with?
Storage & Filesystem (Beginner)
What's an inode?
Which of the following is not included in inode:
Link count
File size
File name
File timestamp
How to check which disks are currently mounted?
You run mount command but you get no output. How would you check what mounts you have on your system?
What is the difference between a soft link and hard link?
True or False? You can create an hard link for a directory
True or False? You can create a soft link between different filesystems
What happens when you delete the original file in case of soft link and hard link?
What is a swap partition? What is it used for?
How to create a * new empty file * a file with text (without using text editor) * a file with given size
You are trying to create a new file but you get "File system is full". You check with df for free space and you see you used only 20% of the space. What could be the problem?
How would you check what is the size of a certain directory?
What do you know about LVM?
Explain the following in regards to LVM:
PV
VG
LV
What is NFS? What is it used for?
What RAID is used for? Can you explain the differences between RAID 0, 1, 5 and 10?
Describe the process of extending a filesystem disk space
What is lazy umount?
What is tmpfs?
Fix the following commands:
sed "s/1/2/g' /tmp/myFile
find . -iname *.yaml -exec sed -i "s/1/2/g" {} ;
Explain what is stored in each of the following paths and if there is anything unique about it:
Processes
How to run a process in the background and why to do that in the first place?
How can you find how much memory a specific process consumes?
What signal is used by default when you run 'kill *process id*'?
What signals are you familiar with?
What kill 0 does?
What kill -0 does?
What is a trap?
What happens when you press ctrl + c?
What are daemons?
What are the possible states of a process in Linux?
What is a zombie process?
How to get rid of zombie processes?
How to find all the
Processes executed/owned by a certain user
Process which are Java processes
Zombie Processes
What is the init process?
How to change the priority of a process? Why would you want to do that?
Can you explain how network process/connection is established and how it's terminated?>
What are system calls? What system calls are you familiar with?
What strace does? What about ltrace?
Find all the files which end with '.yml' and replace the number 1 in 2 in each file
How to check how much free memory a system has? How to check memory consumption by each process?
You run ls and you get "/lib/ld-linux-armhf.so.3 no such file or directory". What is the problem?
How would you split a 50 lines file into 2 files of 25 lines each?
What is a file descriptor? What file descriptors are you familiar with?
What is NTP? What is it used for?
Explain Kernel OOM
Linux Security
What is chroot? In what scenarios would you consider using it?
What is SELiunx?
What is Kerberos?
What is nftables?
What firewalld daemon is responsible for?
Do you have experience with hardening servers? Can you describe the process?
Network
What is a network namespace? What is it used for?
How to check if a certain port is being used?
How can you turn your Linux server into a router?
What is a virtual IP? In what situation would you use it?
Can you have more than one default gateway in a given system?
Which port is used in each of the following protocols?:
SSH

HTTP

DNS

HTTPS

What is the routing table? How do you view it?
How can you send an HTTP request from your shell?
What are packet sniffers? Have you used one in the past? If yes, which packet sniffers have you used and for what purpose?
How to list active connections?
How to trigger neighbor discovery in IPv6?
Linux DNS
What the file /etc/resolv.conf is used for? What does it include?
What commands are you using for performing DNS queries (or troubleshoot DNS related issues)?
Packaging
Do you have experience with packaging? Can you explain how it works?
RPM: explain the spec format(what it should and can include)
How do you list the content of a package without actually installing it?
How to know to which package a file on the system belongs to? Is it a problem if it doesn't belongs to a package?
Applications and Services
What can you find in /etc/services?
How to make sure a Service starts automatically after a reboot or crash?
You run ssh 127.0.0.1 but it fails with "connection refused". What could be the problem?
How to print the shared libraries required by a certain program? What is it useful for?
Users
How do you create users? Where user information is stored?
Do you know how to create a new user without using adduser/useradd command?
What information is stored in /etc/passwd?
How to add a new user to the system without providing him the ability to log-in into the system?
What can you do if you lost/forogt the root password?
What is sudo? How do you set it up?
Random and perhaps useless :)
Give 5 commands which are two letters long
What a double dash (--) mean?
Commands
What the lsof command does? Have you used it? What for?
What the awk command does? Have you used it? What for?

star Advanced
System Calls
Explain the fork system call
Explain the exec system call
What are the differences between exec() and fork()?
Why do we need the wait system call?
What execve() does?
What happens when you execute ls -l?
What happens when you execute ls -l *.log?
What readdir() system call does?
Linux Filesystem & Files
How to create a file of a certain size?
Can you describe how processes are being created?
What does the following block do?:
open("/my/file") = 5
read(5, "file content")
What system call is used for listing files?
What system call is used for creating a new process?
What is the difference between a process and a thread?
You found there is a server with high CPU load but you didn't find a process with high CPU. How is that possible?
Linux Networking
When you run ip a you see there is a device called 'lo'. What is it and why do we need it?
What the traceroute command does? How does it works?
What is network bonding? What types are you familiar with?
How to link two separate network namespaces so you can ping an interface on one namespace from the second one?
What are cgroups?
Explain Process Descriptor and Task Structure
What are the differences between threads and processes?
Explain Kernel Threads
What happens when socket system call is used?
You executed a script and while still running, it got accidentally removed. Is it possible to restore the script while it's still running?
Memory
What is the difference between MemFree and MemAvailable in /proc/meminfo?
Operating System

baby Beginner
What is an operating system?
Processes
Can you explain what is a process?
If you had to design an API for processes in an operating system, what would this API look like?
How a process is created?
True or False? The loading of the program into the memory is done eagerly (all at once)
What are different states of a process?
Concurrency
Explain what is Semaphore and what its role in operating systems
Memory
What is cache? What is buffer?
Virtualization

baby Beginner
Explain what is Virtualization
What is "time sharing"?
What is "space sharing"?
Ansible

baby Beginner
Describe each of the following components in Ansible, including the relationship between them:
Task
Module
Play
Playbook
Role
How Ansible is different from other Automation tools?
What kind of automation you wouldn't do with Ansible and why?
What is an inventory file and how do you define one?
What is a dynamic inventory file? When you would use one?
How do you list all modules and how can you see details on a specific module?
Write a task to create the directory ‘/tmp/new_directory’
You want to run Ansible playbook only on specific minor version of your OS, how would you achieve that?
What would be the result of the following play?
What would be the result of running the following task?
- hosts: localhost
  tasks:
      - name: Install zlib
        package:
          name: zlib
          state: present
Which Ansible best practices are you familiar with?. Name at least three
Explain the directory layout of an Ansible role
Write a playbook to install ‘zlib’ and ‘vim’ on all hosts if the file ‘/tmp/mario’ exists on the system.
Write a playbook to deploy the file ‘/tmp/system_info’ on all hosts except for controllers group, with the following content
The variable 'whoami' defined in the following places:
role defaults -> whoami: mario
extra vars (variables you pass to Ansible CLI with -e) -> whoami: toad
host facts -> whoami: luigi
inventory variables (doesn’t matter which type) -> whoami: browser
According to variable precedence, which one will be used?

For each of the following statements determine if it's true or false:
A module is a collection of tasks
It’s better to use shell or command instead of a specific module
Host facts override play variables
A role might include the following: vars, meta, and handlers
Dynamic inventory is generated by extracting information from external sources
It’s a best practice to use indention of 2 spaces instead of 4
‘notify’ used to trigger handlers
This “hosts: all:!controllers” means ‘run only on controllers group hosts
What is ansible-pull? How is it different from how ansible-playbook works?
What is Ansible Vault?
Demonstrate each of the following with Ansible:
Conditionals
Loops

star Advanced
What are filters? Do you have experience with writing filters?
Write a filter to capitalize a string
You would like to run a task only if previous task changed anything. How would you achieve that?
How do you test your Ansible based projects?
What are callback plugins? What can you achieve by using callback plugins?
File '/tmp/exercise' includes the following content
Goku = 9001
Vegeta = 5200
Trunks = 6000
Gotenks = 32
With one task, switch the content to:

Goku = 9001
Vegeta = 250
Trunks = 40
Gotenks = 32
Terraform

baby Beginner
Can you explain what is Terraform? How it works?
What benefits infrastructure-as-code has?
Why Terraform and not other technologies? (e.g. Ansible, Puppet, CloufFormation)
Explain what is "Terraform configuration"
What is HCL?
Explain each of the following:
Provider
Resource
Provisioner
What terraform.tfstate file is used for?
Explain what the following commands do:
terraform init
terraform plan
terraform validate
terraform apply
How to write down a variable which changes by an external source or during terraform apply?
Give an example of several Terraform best practices
Explain how implicit and explicit dependencies work in Terraform
What is local-exec and remote-exec in the context of provisioners?
What is a "tainted resource"?
What terraform taint does?
What types of variables are supported in Terraform?
What is a data source? In what scenarios for example would need to use it?
What are output variables and what terraform output does?
Explain Modules
What is the Terraform Registry?
Explain remote-exec and local-exec

star Advanced
Explain "Remote State". When would you use it and how?
Explain "State Locking"
What is the "Random" provider? What is it used for
How do you test a terraform module?
Aside from .tfvars files or CLI arguments, how can you inject dependencies from other modules?
Docker

baby beginner
What is Docker? What are you using it for?
How containers are different from VMs?
In which scenarios would you use containers and in which you would prefer to use VMs?
Explain Docker architecture
Describe in detail what happens when you run `docker run hello-world`?
How do you run a container?
What `docker commit` does?. When will you use it?
How would you transfer data from one container into another?
What happens to data of the container when a container exists?
Explain what each of the following commands do:
docker run
docker rm
docker ps
docker pull
docker build
docker commit
How do you remove old, non running, containers?
Dockerfile
What is Dockerfile
What is the difference between ADD and COPY in Dockerfile?
What is the difference between CMD and RUN in Dockerfile?
Do you perform any checks or testing related to your Dockerfile?
Explain what is Docker compose and what is it used for
What are the differences between Docker compose, Docker swarm and Kubernetes?
Explain Docker interlock
What is the difference between Docker Hub and Docker cloud?
Where Docker images are stored?
Explain image layers

star Advanced
What best practices are you familiar related to working with containers?
How do you manage persistent storage in Docker?
How can you connect from the inside of your container to the localhost of your host, where the container runs?
How do you copy files from Docker container to the host and vice versa?
Kubernetes

baby Beginner
What is Kubernetes? What use cases is it good for?
Describe the architecture of Kubernetes
What is a Kubernetes Cluster?
What the Master is responsible for?
What is a Node?
Explain what is Kubelet
What is Minikube?
Explain what is a Kubernetes pod
True or False? A pod can manage multiple containers
How do you monitor your Kubernetes?
You suspect one of the pods is having issues, what do you do?
What the Kubernetes Scheduler does?
What happens to running pods if if you stop Kubelet on the worker nodes?
Describe how roll-back works
Kubernetes Commands
What is kubectl?
How do you:
Check the cluster status?
Check the status of the nodes?
What the following commands do?
kubectl get nodes
kubectl
What is kubconfig? What do you use it for?
Coding

baby Beginner
What programming language do you prefer to use for DevOps related tasks? Why specifically this one?
Explain expressions and statements
What is Object Oriented Programming? Why is it important?
Are you familiar with SOLID design principals?
What are the four pillars of object oriented programming?
Explain recursion
Explain Inversion of Control
Explain Dependency Injection
Explain what are design patterns and describe three of them in detail
Explain big O notation
Common algorithms
Binary search:
How it works?
Can you implement it? (in any language you prefer)
What is the average performance of the algorithm you wrote?
Code Review
What are your code-review best practices?
Do you agree/disagree with each of the following statements and why?:
The commit message is not important. When reviewing a change/patch one should focus on the actual change
You shouldn't test your code before submitting it. This is what CI/CD exists for.
Strings
In any language you want, write a function to determine if a given string is a palindrome
In any language you want, write a function to determine if two strings are Anagrams
Integers
In any language you would like, print the numbers from 1 to a given integer. For example for input: 5, the output is: 12345
Time Complexity
Describe what would be the time complexity of the operations access, search insert and remove for the following data structures:
What is the complexity for the best, worst and average cases of each of the following algorithms?:
Quick sort
Merge sort
Bucket Sort
Radix Sort
Data Structures & Types
Implement Stack in any language you would like
Implement Hash table in any language you would like

star Advanced
Name 3 design patterns. Do you know how to implement (= provide an example) these design pattern in any language you'll choose?
Given an array/list of integers, find 3 integers which are adding up to 0 (in any language you would like)
Python

baby Beginner
What are some characteristics of the Python programming language?
What built-in types Python has?
What is mutability? Which of the built-in types in Python are mutable? How can you show that a certain data type is mutable?
In Python, functions are first-class objects. What does it mean?
What is the result of running [] is not []? explain the result
Explain inheritance and how to use it in Python
Explain and demonstrate class attributes & instance attributes
What is an error? What is an exception? What types of exceptions are you familiar with?
Explain Exception Handling and how to use it in Python
What _ is used for in Python?
Explain what is GIL
What is Lambda? How is it used?
Properties
Are there private variables in Python? How would you make an attribute of a class, private?
Explain the following:
getter
setter
deleter
Explain what is @property
How do you swap values between two variables?
Explain the following object's magic variables:
dict
Write a function to return the sum of one or more numbers. The user will decide how many numbers to use
Print the average of [2, 5, 6]. It should be rounded to 3 decimal places
Python Lists
How do you get the maximum and minimum values from a list? How to get the last item from a list?
How to get the top/biggest 3 items from a list?
How to sort list by the length of items?
Do you know what is the difference between list.sort() and sorted(list)?
Convert every string to an integer: [['1', '2', '3'], ['4', '5', '6']]
How to merge two sorted lists into one sorted list?
How to check if all the elements in a given lists are unique? so [1, 2, 3] is unique but [1, 1, 2, 3] is not unique because 1 exists twice
You have the following function
def my_func(li = []):
    li.append("hmm")  
    print(li)
If we call it 3 times, what would be the result each call?

How to iterate over a list in reverse order?
Sort a list of lists by the second item of each nested list
Combine [1, 2, 3] and ['x', 'y', 'z'] so the result is [(1, 'x'), (2, 'y'), (3, 'z')]
Dictionaries
How to sort a dictionary by values?
How to sort a dictionary by keys?
How to merge two dictionaries?
Common Algorithms Implementation
Can you implement "binary search" in Python?
Files
How to write to a file?
How to print the 12th line of a file?
How to reverse a file?
Sum all the integers in a given file
Can you write a function which will print all the file in a given directory? including sub-directories
Regex
How do you perform regular expressions related operations in Python? (match patterns, substitute strings, etc.)
How to substitute the string "green" with "blue"?
How to find all the IP addresses in a variable? How to find them in a file?
You have the following list: [{'name': 'Mario', 'food': ['mushrooms', 'goombas']}, {'name': 'Luigi', 'food': ['mushrooms', 'turtles']}] Extract all type of foods. Final output should be: {'mushrooms', 'goombas', 'turtles'}
What is List Comprehension? Is it better than a typical loop? Why? Can you demonstrate how to use it?
Python Strings
How to extract the unique characters from a string? for example given the input "itssssssameeeemarioooooo" the output will be "mrtisaoe"
Find all the permutations of a given string
How to check if a string contains a sub string?
Find the frequency of each character in string
Count the number of spaces in a string
Given a string, find the N most repeated words
Given the string (which represents a matrix) "1 2 3\n4 5 6\n7 8 9" create rows and colums variables (should contain integers, not strings)
What is the result of each of the following?
>> ', '.join(["One", "Two", "Three"])
>> " ".join("welladsadgadoneadsadga".split("adsadga")[:2])
>> "".join(["c", "t", "o", "a", "o", "q", "l"])[0::2]
How to reverse a string? (e.g. pizza -> azzip)
What is the output of the following code: "".join(["a", "h", "m", "a", "h", "a", "n", "q", "r", "l", "o", "i", "f", "o", "o"])[2::3]
Explain data serialization and how do you perform it with Python
How do you handle argument parsing in Python?
What is an iterator?
What is a generator? Why using generators?
What is yeild? When would you use it?
Explain the following types of methods and how to use them:
Static method
Class method
instance method
How to reverse a list?
How to combine list of strings into one string with spaces between the strings
You have the following list of nested lists: [['Mario', 90], ['Geralt', 82], ['Gordon', 88]] How to sort the list by the numbers in the nested lists?
Explain the following:
zip()
map()
filter()
Debugging
How do you debug Python code?
How to check how much time it took to execute a certain script or block of code?
What empty return returns?
How to improve the following block of code?
li = []
for i in range(1, 10):
    li.append(i)
Given the following function
def is_int(num):
    if isinstance(num, int):
        print('Yes')
    else:
        print('No')
What would be the result of is_int(2) and is_int(False)?

Data Structures & Types
Implement Stack in Python
Implement Hash table in Python
Python Testing
What is your experience with writing tests in Python?
What is PEP8? Give an example of 3 style guidelines
How would you check if two strings are equal? What about booleans?
How to test if an exception was raised?
What assert does in Python?
Explain mocks
How do you measure execution time of small code snippets?
Why one shouldn't use assert in non-test/production code?
Flask
You wrote you have experience with Django/Flask. Can you describe what is Django/Flask and how you have used it? Why Flask and not Djano? (or vice versa)
What is a route?
How do you manage DB integration?
zip
Given x = [1, 2, 3], what is the result of list(zip(x))?
What is the result of each of the following:
list(zip(range(5), range(50), range(50)))
list(zip(range(5), range(50), range(-2)))
Misc
Implement simple calculator for two numbers

star Advanced
What data types are you familiar with that are not Python built-in types but still provided by modules which are part of the standard library?
Explain what is a decorator
Can you show how to write and use decorators?
Write a decorator that calculates the execution time of a function
Write a script which will determine if a given host is accessible on a given port
Are you familiar with Dataclasses? Can you explain what are they used for?
You wrote a class to represent a car. How would you compare two cars instances if two cars are equal if they have the same model and color?
Explain Context Manager
Tell me everything you know about concurrency in Python
Explain the Buffer Protocol
Explain Descriptors
Do you have experience with web scraping? Can you describe what have you used and for what?
Can you implement Linked List in Python?
Can you implement Linux's tail command in Python? Bonus: implement head as well
You have created a web page where a user can upload a document. But the function which reads the uploaded files, runs for a long time, based on the document size and user has to wait for the read operation to complete before he/she can continue using the web site. How can you overcome this?
How yield works exactly?
Monitoring

baby Beginner
Explain monitoring. What is it? What its goal?
What is wrong with the old approach of watching for a specific value and trigger an email/phone alert while value is exceeded?
What types of monitoring outputs are you familiar with and/or used in the past?
What is the different between infrastructure monitoring and application monitoring? (methods, tools, ...)
Python Geeks :)
Tell me something about Python that you think most people don't know
Prometheus

baby Beginner
What is Prometheus? What are some of Prometheus's main features?
Describe Prometheus architecture and components
Have you set up Prometheus? How did you do it? Describe the process
Can you compare Prometheus to other solutions like InfluxDB for example?
What is an Alert?
Describe the following Prometheus components:
Prometheus server
Push Gateway
Alert Manager
What is an Instance? What is a Job?
What core metrics types Prometheus supports?
What is an exporter? What is it used for?
Which Prometheus best practices are you familiar with?. Name at least three
How to get total requests in a given period of time?
What HA in Prometheus means?

star Advanced
How do you join two metrics?
How to write a query that returns the value of a label?
How do you convert cpu_user_seconds to cpu usage in percentage?
Git

baby Beginner
What is the difference between git pull and git fetch?
Explain the following: git directory, working directory and staging area
How to resolve git merge conflicts?
What is the difference between git reset and git revert?
You would like to move forth commit to the top. How would you achieve that?
In what situations are you using git rebase?
What merge strategies are you familiar with?
How can you see which changes have done before committing them?
How do you revert a specific file to previous commit?
What is the .git directory? What can you find there?
What are some Git anti-patterns? Things that you shouldn't do
How do you remove a remote branch?
Are you familiar with gitattributes? When would you use it?
How do you discard local file changes? (before commit)
How do you discard local commits?
True or False? To remove a file from git but not from the filesystem, one should use git rm

star Advanced
Explain Git octopus merge
Go

baby Beginner
What are some characteristics of the Go programming language?
What is the difference between var x int = 2 and x := 2?
True or False? In Go we can redeclare variables and once declared we must use it.
What libraries of Go have you used?
What is the problem with the following block of code? How to fix it?
func main() {
    var x float32 = 13.5
    var y int
    y = x
}
The following block of code tries to convert the integer 101 to a string but instead we get "e". Why is that? How to fix it?
package main

import "fmt"

func main() {
    var x int = 101
    var y string
    y = string(x)
    fmt.Println(y)
}
What is wrong with the following code?:
package main

func main() {
    var x = 2
    var y = 3
    const someConst = x + y
}
What will be the output of the following block of code?:
package main

import "fmt"

const (
	x = iota
	y = iota
)
const z = iota

func main() {
	fmt.Printf("%v\n", x)
	fmt.Printf("%v\n", y)
	fmt.Printf("%v\n", z)
}
What _ is used for in Go?
What will be the output of the following block of code?:
package main

import "fmt"

const (
	_ = iota + 3
	x
)

func main() {
	fmt.Printf("%v\n", x)
}
Mongo

baby Beginner
What are the advantages of MongoDB? Or in other words, why choosing MongoDB and not other implementation of NoSQL?
What is the difference between SQL and NoSQL?
In what scenarios would you prefer to use NoSQL/Mongo over SQL?
What is a document? What is a collection?
What is an aggregator?
What is better? Embedded documents or referenced?
Have you performed data retrieval optimizations in Mongo? If not, can you think about ways to optimize a slow data retrieval?
Queries
Explain this query: db.books.find({"name": /abc/})
Explain this query: db.books.find().sort({x:1})
OpenShift

baby Beginner
What is OpenShift? Did you use it? If yes, how?
Can you explain the difference between OpenShift and Kubernetes?
Define Pods and explain what are stateful pods
What types of build strategies are you familiar with?
Explain what are labels and what they are used for
Explain what are annotations and how they are different from labels
Explain what is Downward API
Shell Scripting

baby Beginner
Tell me about your experience with shell scripting
What this line in scripts mean?: #!/bin/bash
What do you tend to include in every script you write?
True or False?: when a certain command/line fails, the script, by default, will exit and will no keep running
Today we have tools and technologies like Ansible. Why would someone still use shell scripting?
Explain what would be the result of each command:
echo $0
echo $?
echo $$
echo $@
echo $#
How do you debug shell scripts?
How do you get input from the user in shell scripts?
Explain conditionals and how do you use them
What is a loop? What types of loops are you familiar with?
Explain continue and break. When do you use them if at all?
How to store the output of a command in a variable?
How do you check variable length?
What is the difference between single and double quotes?
Write a script which will list the differences between two directories
Practical
Write a script to determine whether a host is up or down
Write a script to remove all the empty files in a given directory (also nested directories)

Advanced
Explain the following code:
:(){ :|:& };:

Can you give an example to some Bash best practices?
What is the ternary operator? How do you use it in bash?
What does the following code do and when would you use it?
diff <(ls /tmp) <(ls /var/tmp)

SQL

baby Beginner
What does SQL stand for?
How is SQL Different from NoSQL
What does it mean when a database is ACID compliant?
When is it best to use SQL? NoSQL?
What is a Cartesian Product?
SQL Specific Questions
For these questions, we will be using the Customers and Orders tables shown below:

Customers

Customer_ID	Customer_Name	Items_in_cart	Cash_spent_to_Date
100204	John Smith	0	20.00
100205	Jane Smith	3	40.00
100206	Bobby Frank	1	100.20
ORDERS

Customer_ID	Order_ID	Item	Price	Date_sold
100206	A123	Rubber Ducky	2.20	2019-09-18
100206	A123	Bubble Bath	8.00	2019-09-18
100206	Q987	80-Pack TP	90.00	2019-09-20
100205	Z001	Cat Food - Tuna Fish	10.00	2019-08-05
100205	Z001	Cat Food - Chicken	10.00	2019-08-05
100205	Z001	Cat Food - Beef	10.00	2019-08-05
100205	Z001	Cat Food - Kitty quesadilla	10.00	2019-08-05
100204	X202	Coffee	20.00	2019-04-29
How would I select all fields from this table?
How many items are in John's cart?
What is the sum of all the cash spent across all customers?
How many people have items in their cart?
How would you join the customer table to the order table?
How would you show which customer ordered which items?

Advanced
Using a with statement, how would you show who ordered cat food, and the total amount of money spent?
Azure

baby Beginner
Explain Azure's architecture
Explain availability sets and availability zones
What is Azure Policy?
What is the Azure Resource Manager? Can you describe the format for ARM templates?
Explain Azure managed disks
Network
What's an Azure region?
What is the N-tier architecture?
Storage
What storage options Azure supports?
Security
What is the Azure Security Center? What are some of its features?
What is Azure Active Directory?
What is Azure Advanced Threat Protection?
What components are part of Azure ATP?
GCP

baby Beginner
Explain GCP's architecture
What are the main components and services of GCP?
What GCP management tools are you familiar with?
Tell me what do you know about GCP networking
OpenStack

baby Beginner
Tell me about your experience with OpenStack. What do you think are the advantages and disadvantages of OpenStack?
What components/projects of OpenStack are you familiar with?
Can you tell me what each of the following components/projects is responsible for?:
Nova
Neutron
Cinder
Glance
Keystone
Describe in detail how you bring up an instance with an IP you can reach from outside the cloud
You get a call from a customer saying: "I can ping my instance but can't connect (ssh) it". What might be the problem?
What types of networks OpenStack supports?
How do you debug OpenStack storage issues? (tools, logs, ...)
How do you debug OpenStack compute issues? (tools, logs, ...)
Are you familiar with TripleO? What benefits it has?
Networking
What is a provider network?
What components and services exist for L2 and L3?
What is the ML2 plug-in? Explain its architecture
What is the L2 agent? How it works and what is it responsible for?
What is the L3 agent? How it works and what is it responsible for?
Explain what the Metadata agent is responsible for
What networking entities Neutron supports?
How do you debug OpenStack networking issues? (tools, logs, ...)

baby Advanced
Networking
Explain BGP dynamic routing
What is the role of network namespaces in OpenStack?
Security

baby Beginner
Can you describe the DevSecOps core principals?
What DevOps security best practices are you familiar with?
What security techniques are you familiar with?
Explain Authentication and Authorization
How do you manage passwords in different tools and platforms?
Explain what is Single Sign-On
Explain MFA (Multi-Factor Authentication)
Explain RBAC (Role-based Access Control)
Explain Symmetric encryption
Explain Asymmetric encryption
Explain the following:
Vulnerability
Exploits
Risk
Threat
What is XSS?
What is an SQL injection? How to manage it?
What is Certification Authority?
How do you identify and manage vulnerabilities?
Explain "Privilege Restriction"
How HTTPS is different from HTTP?
What types of firewalls are there?
What is DDoS attack? How do you deal with it?
What is the difference between asynchronous and synchronous encryption?
Explain Man-in-the-middle attack
Explain CVE and CVSS
What is ARP Poisoning?
Describe how do you secure public repositories
How do cookies work?
What is DNS Spoofing? How to prevent it?
What can you tell me about Stuxnet?
What can you tell me about Spectre?
Explain OAuth
Explain "Format String Vulnerability"
Explain DMZ
Explain TLS
What is CSRF? How to handle CSRF?
Explain HTTP Header Injection vulnerability
What security sources are you using to keep updated on latest news?
What TCP and UDP vulnerabilities are you familiar with?
Do using VLANs contribute to network security?
What are some examples of security architecture requirements?
What is air-gapped network (or air-gapped environment)? What its advantages and disadvantages?
Explain what is Buffer Overflow
Containers
What security measures are you taking when dealing with containers?
Explain what is Docker Bench

baby Advanced
Explain MAC flooding attack
What is "Diffie-Hellman key exchange" and how does it work?
Explain "Forward Secrecy"
What is Cache Poisoned Denial of Service?
Puppet

baby Beginner
What is Puppet? How it works?
Explain Puppet architecture
Can you compare Puppet to other configuration management tools? Why did you chose to use Puppet?
Explain the following:
Module
Manifest
Node
Explain Facter
What is MCollective?

baby Advanced
Do you have experience with writing modules? Which module have you created and for what?
Explain what is Hiera
Elastic

baby Beginner
What is the Elastic Stack?
Describe what happens from the moment the app logged some information until it's displayed to the user in the dashboard when the Elastic stack is used
Elasticsearch
Explain what is Elasticsearch
What is an Index?
What is an Inverted Index?
What is a Document?
True or False? Elasticsearch indexes all data in every field and each indexed field has the same data structure for unified and quick query ability
What reserved fields a document has?
Explain Mapping
What are the advantages of defining your own mapping? (or: when would you use your own mapping?)
Explain Shards
Explain Replicas
Can you explain Term Frequency & Document Frequency?
Query DSL
Explain Elasticsearch query syntax (Booleans, Fields, Ranges)
Explain what is Relevance Score
Explain Query Context and Filter Context
Logstash
What are Logstash plugins? What plugins types are there?
What are Logstash Codecs?
Kibana
What is Kibana?
What visualization types are supported/included in Kibana?
What visualization type would you use for statistical outliers
Describe in detail how do you create a dashboard in Kibana
Beats
What is Filebeat?

star Advnaced
Describe how would an architecture of production environment with large amounts of data would be different from a small-scale environment
DNS

baby Beginner
What is DNS? What is it used for?
How DNS works?
What types of DNS records are there?
What is a A record?
What is a AAAA record?
What is a PTR record?
What is a MX record?
Is DNS using TCP or UDP?
What is Round Robin DNS?
What is DNS Record TTL? Why do we need it?
What is a zone? What types of zones are there?
Distributed
Explain Distributed Computing (or Distributed System)
Do you know what is "CAP theorem"? (aka as Brewer's theorem)
What is "Shared-Nothing" architecture?
General
HTTP
What is HTTP?
Describe HTTP request lifecycle
True or False? HTTP is stateful
How HTTP request looks like?
What HTTP method types are there?
What HTTP response codes are there?
What is HTTPS?
Explain HTTP Cookies
What is HTTP Pipelining?
What is a proxy?
What is a reverse proxy?
What is CDN?
When you publish a project, you usually publish it with a license. What types of licenses are you familiar with and which one do you prefer to use?
Load Balancers
What is a load balancer?
What load balancer algorithms are you familiar with?
What is an Application Load Balancer?
Random
How a search engine works?
What is faster than RAM?
What is a memory leak?
What is your favorite protocol?
What is Cache API?
What is the C10K problem? Is it relevant today?
HR
Although the following questions are not DevOps related, they are still quite common and part of the DevOps interview process so it's better to prepare for them as well.

Tell us little bit about yourself
Tell me about your last big project/task you worked on
What was most challenging part in the project you worked on?
Why do you want to work here?
How did you hear about us?
How would you describe a good leadership? What makes a good boss for you?
Tell me about a time where you didn't agree on an implementation
How do you deal with a situation where key stakeholders are not around and a big decision needs to be made?
Where do you see yourself in 5 years?
Give an example of a time you were able to change the view of a team about a particular tool/project/technology
Have you ever caused a service outage? (or broke a working project, tool, ...?)
Rank the following in order 1 to 5, where 1 is most important: salaray, benefits, career, team/people, work life balance
You have three important tasks scheduled for today. One is for your boss, second for a colleague who is also a friend, third is for a customer. All tasks are equally important. What do you do first?
You have a colleague you don‘t get along with. Tell us some strategies how you create a good work relationship with them anyway.
What do you love about your work?
What are your responsibilities in your current position?
Why should we hire you for the role?
Team Lead
How would you improve productivity in your team?
Questions you CAN ask

A list of questions you as a candidate can ask the interviewer during or after the interview. These are only a suggestion, use them carefully. Not every interviewer will be able to answer these (or happy to) which should be perhaps a red flag warning for your regarding working in such place but that's really up to you.

What do you like about working here?
How does the company promote personal growth?
What is the current level of technical debt you are dealing with?
What was your favorite project you've worked on?
If you could change one thing about your day to day, what would it be?
Let's say that we agree and you hire me to this position, after X months, what do you expect that I have achieved?
Testing
What types of tests would you run for web application?
What are unit tests?
Explain test harness?
What is A/B testing?
What is network simulation and how do you perform it?
What types of performances tests are you familiar with?
Explain the following types of tests:
Load Testing
Stress Testing
Capacity Testing
Volume Testing
Endurance Testing
Databases
What is a connection pool?
What is a connection leak?
What is Table Lock?
Your database performs slowly than usual. More specifically, your queries are taking a lot of time. What would you do?
What is a connection leak?
What is a Data Warehouse?
What is a data lake?
What is OLTP (Online transaction processing)?
What is OLAP (Online Analytical Processing)?
Design
Architecture
Explain "3-Tier Architecture" (including pros and cons)
What are the drawbacks of monolithic architecture?
What are the advantages of micro-services architecture over a monolithic architecture?
Scalability
Explain Vertical Scaling
Explain Horizontal Scaling
How would you update each of the services in the following drawing without having app (foo.com) downtime?

What is the problem with the following architecture and how would you fix it?

Users report that there is huge spike in process time when adding little bit more data to process as an input. What might be the problem?

How would you scale the architecture from the previous question to hundreds of users?
Migrations
How you prepare for a migration? (or plan a migration)
Explain "Branch by Abstraction" technique
Exercises
Exercises are all about:

Setting up environments
Writing scripts
Designing and/or developing infrastructure apps
Fixing existing applications
Below you can find several exercises

Writing a Dockerfile and running a container
Elasticsearch & Kibana on AWS
Ansible, Minikube and Docker
Cloud Slack bot
Jenkins: writing scripts
Jenkins: writing pipelines
CI for open source project
Flask, Containers and CI
Flask, Containers and CI 2
Credits
Thanks to all of our amazing contributors who make it easy for everyone to learn new things :)

Logos credits can be found here
