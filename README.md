🚀 Ansible Role Project – Web Server Automation
📌 Project Description

This project demonstrates automation of web server setup using Ansible. It uses Ansible roles to install and configure Nginx, deploy a static website, and manage services efficiently.

⚙️ Features

Install and configure Nginx web server

Deploy static website using Ansible

Use of Ansible roles for structured automation

Implement handlers to restart services on changes

Manage inventory and execute playbooks

🛠️ Tools & Technologies

Ansible

Linux (Ubuntu)

Nginx

📁 Project Structure
 ansible-project/
├── inventory
├── site.yml
└── roles/
    └── webserver/
        ├── tasks/
        ├── handlers/
        ├── files/
        ├── vars/
        └── defaults/
 
 
 ▶️ How to Run

Clone the repository:

git clone https://github.com/your-username/ansible-role-project.git
 
 cd ansible-role-project

Run the playbook:

ansible-playbook -i inventory site.yml -K

Enter your system password when prompted.

🌐 Output

After successful execution, open your browser and visit:

http://localhost

You should see the deployed web page.

🎯 Learning Outcomes

    Understanding of Ansible playbooks and roles

    Hands-on experience with configuration management

    Automation of web server deployment

    Working with handlers, modules, and inventory
