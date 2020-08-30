Ubuntu provision
----------------
Use this playbook to provision your local Ubuntu host with:

- Guake3 terminal
- git
- htop
- vim
- python3-pip
- wget
- Keepass2
- Google Chrome
- Dropbox

## Usage

```shell script
# 1. Install ansible
$ sudo ./install-ansible.sh

# 2. Install required roles by playbook
$ ansible-galaxy install -r requirements.yml

# 3. Run the ansible playbook
$ ansible-playbook playbook.yml
```