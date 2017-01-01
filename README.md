# keycloak-env

This is a project that creates a Keycloak environment for application integration tests.  
Hosts:  

|Host     |Description        |
|---------|-------------------|
|kc0      |Keycloak Server    |
|kc1      |Client Host 1      |
|kc2      |Client Host 2      |
|kc3      |Client Host 3      |  

This environment is using Vagrant to provision the keycloak environment. In order to continue you have to [install Vagrant](https://www.vagrantup.com/docs/installation/).

Usage:
```bash  
git clone https://github.com/guaxinim/keycloak-env  
vagrant up
```  


