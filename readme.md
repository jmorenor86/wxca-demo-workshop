# WXCA4A Storage virtualization
## About The Project
![Diagram](images/createVolume.drawio.png)

This is a project to manage volumes and volume groups into IBM Flash System 9100 to automatize the task using IBM Watson code asistant for ansible lightspeed.  

The automatization task include:

- Create Volume group
- Create or Delete volume
- Print info about volumes, volumegroups
- pools and policies.

### Built With

[![WatsonX][WatsonX]][WatsonXURL]  [![Ansible][Ansible]][AnsibleURL] [![Storage][Storage]][StorageURL]  


## Getting Started
### Prerequisites

to start the project you need to install the following:

- ansible
- python > 3.10
- Watson code assistant for ansible lightspeed (trial version)
- Ansible Automation platform (trial version)
- Visual studio code
- Data to connect IBM Storage Flash System



### Installation
1. Clone the repo
 ```sh
    git clone git@github.ibm.com:tech-garage-spgi/wxca-ibm-storage-virtualize.git
 ```
2. Fill the parameters into vars.yml

```yml
_clustername_: IP
_username_: user
_password_: password
_volume_group_: volume_name
_pool_: pool_name

```

3. Execute the playbook

![Execute](images/execute.gif)







[WatsonXURL]: https://www.ibm.com/products/watsonx-code-assistant

[WatsonX]: https://img.shields.io/badge/Watson%20Code%20Assistant-006699?style=for-the-badge&logo=Watsonx

[AnsibleURL]: https://www.redhat.com/en/technologies/management/ansible/ansible-lightspeed

[Ansible]:https://img.shields.io/badge/Ansible%20lightspeed-ee0000?style=for-the-badge&logo=Ansible

[Storage]:https://img.shields.io/badge/IBM%20Storage%20Flash%20System-006699?style=for-the-badge&logo=Spectrum

[StorageURL]: https://www.ibm.com/flashsystem?utm_content=SRCWW&p1=Search&p4=43700077352506608&p5=p&gad_source=1&gclid=CjwKCAjwrcKxBhBMEiwAIVF8rKpt6glwcFCvNTu1FCp1yfmGOU6SO0OSLHNmDJE0T580n-1fvqsgWRoClj4QAvD_BwE&gclsrc=aw.ds