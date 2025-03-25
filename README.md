# SDN_Assignment3_NetAutomation

The first step is to create a VM to host Ansible AWX on Ubuntu 22.04 LTS. Access the AWX web panel. image
Step Two

Next create an inventory with hosts, credentials to the networking devices, and a project that links back to this repository

![image](https://github.com/user-attachments/assets/a3ce6e6c-9659-417a-849f-b58251ca11f0)


![image](https://github.com/user-attachments/assets/81a21e54-49e2-4e0d-bac8-95372fa70120)



![image](https://github.com/user-attachments/assets/2e376079-afbf-4b00-9880-c044ca45b1f0)

![image](https://github.com/user-attachments/assets/cff614e9-37f2-4ffc-97f0-7672781a16ca)



![image](https://github.com/user-attachments/assets/7d346a13-79da-4cf6-a58c-6c981cff5059)

Step Three

Create a job template, this one will use the ShowIpIntBr.yml playbook and the expected outcome should be a success with the IP interfaces displaying.

image

image

Create a workflow template for both jobs running the ShowIpIntBr.yml and configure_banner.yml playbooks. image

image

Create a survey and enable surveys on one of the job templates. Afterwards, launch the job which should display the interfaces. image

image
