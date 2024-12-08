# **Terraform Automation for VMware vSphere**

## **Overview**
This repository contains Terraform configurations for provisioning a virtual machine (VM) in a VMware vSphere environment.
The configuration uses variables and resources to automate the deployment of a VM with customized settings.

## **Features**
* VM Provisioning: Automates the creation of a virtual machine from a template.
* Customizable: Configurations allow setting CPU, memory, disk size, and network settings.
* Windows Customization: Supports setting computer name, administrator password, timezone, and network settings for Windows VMs.
* Environment Variables: Securely pass sensitive credentials using environment variables.

## **Instructions**
1. Clone the repository
2. Export environment variables:
   """export TF_VAR_vsphere_user="your_vsphere_username"""
   "export TF_VAR_vsphere_password="your_vsphere_password"
   "export TF_VAR_vsphere_server="your_vsphere_server_address"
   "export TF_VAR_machine_password="your_machine_admin_password"
