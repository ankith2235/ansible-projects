# Ansible Projects – 5 Assignments

This repository contains Ansible projects completed as part of my Cloud & DevOps training. These projects demonstrate hands-on experience with Ansible cluster setup, ad-hoc automation, role-based configuration management, file deployment, and environment-based orchestration.

---

## 🔹 Project 1: Ansible Cluster Setup with Java and MySQL
**Objective:**  
To set up a basic Ansible cluster and install different software on different slave nodes.

**Tasks Performed:**
1. Set up an Ansible cluster with **1 master and 2 slave nodes**
2. Installed **Java** on **Slave 1**
3. Installed **MySQL Server** on **Slave 2**

**Outcome:**  
Successfully automated software installation on different nodes using a single Ansible playbook.

---

## 🔹 Project 2: Execute Custom Script Using Ansible
**Objective:**  
To run a custom shell script on all managed hosts using Ansible.

**Tasks Performed:**
1. Created a shell script that appends the text  
   *“This text has been added by custom script”* to `/tmp/1.txt`
2. Executed the script on **all hosts** using Ansible

**Outcome:**  
Demonstrated Ansible’s ability to execute scripts across multiple nodes simultaneously.

---

## 🔹 Project 3: Role-Based Installation of Apache and NGINX
**Objective:**  
To use Ansible roles for managing different services on different nodes.

**Tasks Performed:**
1. Created **two Ansible roles**
2. Installed **Apache2** on **Slave 1** using one role
3. Installed **NGINX** on **Slave 2** using another role

**Outcome:**  
Implemented clean, modular automation using role-based Ansible architecture.

---

## 🔹 Project 4: Deploy Custom index.html Using Ansible Role
**Objective:**  
To replace the default web page using Ansible role file management.

**Tasks Performed:**
1. Used the existing Ansible cluster
2. Added a custom `index.html` file in the role’s `files` directory
3. Replaced the original web server index page using Ansible

**Outcome:**  
Successfully deployed a custom web page using Ansible’s `copy` module and roles.

---

## 🔹 Project 5: Five-Node Ansible Cluster with Test and Prod Environments
**Objective:**  
To manage multiple environments using Ansible inventory grouping.

**Tasks Performed:**
1. Created a **5-node Ansible cluster**
   - 1 Master node
   - 2 Test nodes
   - 2 Prod nodes
2. Labeled nodes using inventory groups: **test** and **prod**
3. Installed **Java** on **test nodes**
4. Installed **MySQL Server** on **prod nodes**

**Outcome:**  
Implemented environment-based automation using Ansible inventory groups and roles.

---

## 🛠 Tools & Technologies Used
- Ansible  
- AWS EC2  
- Linux (Ubuntu)  
- Apache2  
- NGINX  
- Java (JDK)  
- MySQL  
- Git & GitHub  

---

## 🎯 Summary
These projects provided strong hands-on experience with Ansible automation, including cluster management, script execution, role-based deployments, file configuration, and environment separation using inventory groups.
