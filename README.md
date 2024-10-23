## Project Highlight: Ansible Realtime Project on AWS 🛠

# I recently worked on a project using Ansible to automate cloud infrastructure deployment and management on AWS EC2 instances. This hands-on project provided a great opportunity to dive deep into automation and configuration management, leveraging the power of Ansible for real-world scenarios.

🔧 Task 1: Create EC2 Instances using Ansible Loops:

Automated the creation of 3 EC2 instances:
* 2 Ubuntu Instances
* 1 CentOS Instance
Used Ansible Loops to ensure the process was efficient and streamlined.
Connection was configured as local to the Ansible control node for easy management.
🔐 Task 2: Passwordless Authentication:

Set up passwordless authentication between the Ansible control node and the newly created instances to allow seamless remote execution of commands.
This setup ensured better security and faster operations by eliminating the need to input passwords manually.
⚡ Task 3: Automate Shutdown of Ubuntu Instances:

Automated the shutdown of Ubuntu instances only using Ansible Conditionals.
Leveraged the when condition on gather_facts to differentiate between the Ubuntu and CentOS instances and apply the task accordingly.

💡 Why is This Important?: Automation is a key element in modern cloud infrastructure management. By using Ansible:

* We reduce manual effort.
* Increase efficiency.
* Improve the reliability of routine administrative tasks.
* Strengthen security through consistent processes like passwordless SSH.

📚 Learning Outcomes:

* Improved proficiency in Ansible for cloud automation.
* Hands-on experience in using Ansible loops and conditionals.
* Enhanced knowledge of managing AWS infrastructure with configuration management tools.
