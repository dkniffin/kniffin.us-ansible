# Usage

1. Create a server on AWS or elsewhere
1. Log in and set up an ssh key for the root user, so you can log in
1. Add the ip or host name to `hosts`
1. Install ansible roles from ansible galaxy
  - `ansible-galaxy install --force -r requirements.yml`
1. Run ansible
  - `ansible-playbook -i hosts playbook.yml`
1. (first time only) Change mysql root password (default: root)
