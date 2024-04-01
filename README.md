install ansible

git clone this repo

cd Setup

ansible-playbook local.yml -K --ask-vault-pass

skip tags with the --skip-tags [tag1],[tag2]