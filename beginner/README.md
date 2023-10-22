# Infrastructure as a Code (IaC) DevOps Beginner Class 

IaC DevOps terbagai kepada dua kelas. 
1. IaC DevOps Beginner Class (VM)
2. IaC DevOps Beginner Class (Container)

## IaC DevOps Beginner Class (VM)

### Apa yang anda akan belajar?

IaC DevOps (VM) adalah kelas yang akan memberi pelajaran tentang:

### Teori:
1. Pengenalan Teknologi Hypervisor - Kenapa perlu tahu?
2. Hypervisor Type 1 dan Hypervisor Type 2
3. Pengenalan Infrastructure as a Code (Iac)
    1. Prinsip IaC
    2. Automation use case
    3. Idempotence use case
    4. Modularity use case
    5. Immutable use case
4. Senarai Enterprise IaC Tools yang akan digunakan didalam kelas ini
    1. Vagrant
    2. Ansible
    3. Github Actions
5. Pengenalan Source Version Control (Git)

### Praktikal:
1. Pemasangan Vagrant
    1. Unix/Linux
    2. Windows

2. Pemasangan Ansible
    1. Unix/Linux
    2. Windows
    
3. Pemasangan Hypervisor type 2 di Local PC
4. Pemasangan Virtual Machine (VM's) menggunakan Vagrant
    1. Konfigurasi Compute - CPU's & Memory
    2. Konfigurasi Storage
        1. Storage size
        2. Storage backup (Primary and Secondary)
    3. Konfigurasi Networks
        1. Private IP
        2. Public IP
        3. DHCP/Static IP
        4. Port Forwarding - External Firewall System
5. Konfigurasi OS Linux sebagai Web Application Server menggunakan Ansible
    1. Deploy Nginx Service
    2. Konfigurasi internal Firewall system (Firewalld) - To allow port 80 dan 22
6. Konfigurasi OS Linux sebagai Database Application Server menggunakan Ansible
    1. Deploy MySQL Service
    2. Konfigurasi internal Firewall system (Firewalld) - To allow port 3306 dan 22
6. Deploy Aplikasi Cockpit menggunakan Ansible - User Friendly Web GUI Base Server Management Tool
    1. Walkthrough the application
        1. Overview
        2. Server Resources Monitoring (Compute,Storage,Networking)
        3. Service Monitoring
        4. Firewall Monitoring
7. Deploy Aplikasi Laravel (No Automated CI/CD yet. Automated CI/CD will be introduced in Advance Class)

8. Menguji Prinsip Infra as a Code - UAT
    1. Automation
    2. Idempotence dan Immutable
    3. Modularity dan Scalibility (Template Ready to Deploy)

## IaC DevOps Beginner Class (Container)

### Apa yang anda akan belajar?

IaC DevOps (Container) adalah kelas yang akan memberi pelajaran tentang:

### Teori:
1. Pengenalan Teknologi Container - Kenapa Container?
2. Pengenalan Docker dan Podman - Apa perbezaan?
3. Memahami Container Build Process - Docker
3. Pengenalan Container Registry (Docker Registry)
5. Pengenalan Container Orchestrator & Microservice Applications

### Praktikal:
1. Pemasangan dan Konfigurasi Docker dalam Linux Server meggunakan Ansible
2. Docker Build Process - Step by Step
    1. Preparing the local workspace
    2. Membina dan deploy PHP Docker Image
    3. Membina dan deploy MySQL Docker Image
    4. Membina dan deploy Python Docker Image
    5. Image Versioning Strategy
    6. Simple Zero Downtime Application Deployment Strategy
3. Konfigurasi external (Hypervisor Firewall) - To allow port 80,3306 (Optional)
4. Konfigurasi internal Firewall system (Firewalld) - To allow port 80,3306  (Optional)
5. Menguji Prinsip Infra as a Code - UAT
    1. Automation
    2. Idempotence dan Immutable
    3. Modularity dan Scalibility (Template Ready to Deploy)


### Course Learning Outcome (CLO)
1. Students are able to build up the fundamental knowledges on Infrastructure and IaC as an enabler to DevOps practice.
2. Students are able to demonstrate the difference between VM's and Containers administrations using IaC tools.
3. Students are able to demonstrate autonomy of Application Rollout & Rollback to meet DevOps principles.
4. Students are able to carry out Production Enterprise ready VM's and Container servers with IaC solutions.
5. Students are able to undestand the value,benefits, and needs of IaC to become a Junior DevOps
6. Students are able to simulate the IaC knowledge over any  Enterprise IaC tools that available in this world
