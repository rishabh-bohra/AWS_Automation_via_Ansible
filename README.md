# ansible-aws-services
ansible roles for various aws services

### To create an aws services via these role you must have aws-cli configured

To create any service open "launch.yml" playbook and edit commented portion with "- name of role"(according to aws-serrvce) which you want to run.

Then run command 
```bash
ansible-playbook launch.yml
```

to successfully create the aws-service
