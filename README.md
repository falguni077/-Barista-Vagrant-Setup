# ☕ Barista Café Website - Vagrant IAC Setup

This project is a simple Infrastructure as Code (IaC) setup using **Vagrant** and **Shell provisioning** to automatically deploy a static café-themed website (from [Tooplate Barista Template](https://www.tooplate.com/view/2137-barista-cafe)) inside a **CentOS Stream 9** virtual machine.

---

## 📦 What's Included

- **Vagrantfile**: Defines a CentOS Stream 9 virtual machine using `bandit145/centos_stream9_arm` box.
- **Provisioning Script**: Installs Apache, downloads and unzips the Barista Cafe template, and sets it up automatically.
- **Firewall Commands**: Ensures HTTP traffic is allowed through firewalld.
- **Host-Only Networking**: The VM is accessible at [http://192.168.56.28](http://192.168.56.28).

---

## 🚀 Getting Started

### Prerequisites

- [Vagrant](https://www.vagrantup.com/)
- [VMware Desktop provider](https://developer.hashicorp.com/vagrant/docs/providers/vmware/)
- [VMware Utility plugin for Vagrant](https://www.vagrantup.com/docs/providers/vmware/installation)

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/falguni077/-Barista-Vagrant-Setup.git
   cd baristaIAC

2.	Start the VM:
    ```bash
    vagrant up
    
3.Visit http://192.168.56.28 on your browser to see the site.

## 📂 Folder Structure:
```
baristaIAC/
├── Vagrantfile
├── .gitignore
├── LICENSE
└── README.md
```

## 📜 License

This project uses multiple open-source licenses. See the LICENSE file for details.

##💡 Why This Project?

This is a learning project to understand:
	•	Vagrant IAC principles
	•	Shell provisioning in Vagrant
	•	Automating web server setups
	•	Hosting static sites in virtual machines


   
