# ansible-example-multi-env

## Running this locally
1. You need Vagrant and Ansible
2. Clone the repo
3. ```cd``` into the repo you just cloned
4. ```vagrant up```
5. ...wait...
6. ```ansible-playbook site.yml -i env/staging/inventory```
7. Check the output, read the debug message
8. ```ansible-playbook site.yml -i env/production/inventory```
9. Check the output, read the debug message
10. SHAZAM!  Multi-environment setup where you scripts don't need to know anything about the environment they are running in
11. ```vagrant destroy```
