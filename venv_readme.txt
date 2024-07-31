1. Move one dir back to install venv out of ansible-place
2. sudo apt install python3.10-venv
3. python3 -m venv myenv
4. source myenv/bin/activate
5. pip install ansible docker kubernetes
6. pip freeze
7. set the vars in playbook which you plan to run (See jenkins-deploy.yaml for example)
8. set the vars in inventory/hosts as well
9. exit from the venv
10. run the playbook
