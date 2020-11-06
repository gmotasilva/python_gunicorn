## Commands to deploy

This playbook was created to run into ubuntu machines only. 

First set your target machines into the inventory file, also provide the key to make connection to targets. 

``` 
ansible-playbook ./hello-playbook.yaml -i inventory --key-file=$PATH_TO_KEY -e "ansible_python_interpreter=/usr/bin/python3" -u ubuntu
```