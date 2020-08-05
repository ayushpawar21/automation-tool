#   Requirement  for installation

ansible package install in your system  
httpd package install in your system  


## Check your Packages install not with command

```bash
= > rpm -q ansible 
= > rpm -q httpd
```


## Check your ansible service running 

```bash
= > systemclt restart ansible

```


## Installation


```bash
 => git clone  https://github.com/ayushpawar21/automation-tool.git  #download the repo
 => cd automation-tool                                              #Change The directory
  
 => ansible-playbook Rhel8_DockerInstalltion.yml 
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

