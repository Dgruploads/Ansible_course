#To skip any tasks that matches the tag name.
ansible-playbook tags.yml --skip-tags "java"

#To execute tasks that matches the tag name.
ansible-playbook tags.yml --tags "java"

