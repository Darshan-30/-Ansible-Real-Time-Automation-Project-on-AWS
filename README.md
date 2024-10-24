# 🔧 Ansible Real-Time Automation Project on AWS! 🚀
I just completed an exciting automation project using Ansible to manage AWS EC2 instances and automate tasks in a real-world scenario! Here’s a breakdown of the steps:
Task 1: 
>>Creating EC2 Instances with Ansible Loops
Using Ansible loops, I spun up 3 EC2 instances:
--> 2 Ubuntu instances
--> 1 Linux instance
📍 The key was leveraging connection: local on the Ansible Control Node to directly manage AWS resources through the Ansible ec2 module.
Task 2: 
>>Setting up Passwordless Authentication:
--> For smoother automation, I configured passwordless SSH authentication between my Ansible Control Node and the newly created EC2 instances.
🔑 This step ensures secure and seamless communication between the control node and managed instances without the need for entering passwords manually.
Task 3: 
>>Automating Shutdown of Ubuntu Instances Only:
--> Using Ansible Conditionals, I automated the shutdown of only the Ubuntu instances. 🛑💡
--> I applied the when condition in the Ansible playbook, gathering facts to filter only Ubuntu-based EC2 instances before proceeding with the shutdown process.
✨ Technologies & Skills used:
- Ansible Playbooks & Loops
- AWS EC2 management with Ansible
- SSH Key-based authentication
- Conditional execution in Ansible (when condition)
