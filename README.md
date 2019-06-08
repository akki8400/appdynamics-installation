# appdynamics-installation
This repo contains complete installation of appdynamics in ansible


Usages:

Clone the repository to your ansible server

Enter all host address in hosts file

First fill all key values of file:
```
vars/main-vars.yml
```

To setup the enterprise console

Run command:
```
ansible-playbook -i hosts enterprise-console.yml
```
To setup the controller
Run command:
```
ansible-playbook -i hosts controller.yml
```

To setup the machine agent:
Run command:
```
ansible-playbook -i hosts agent.yml
```


Soon will provide for installtion of other agents also.
