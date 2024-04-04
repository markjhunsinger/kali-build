# Building Kali with Ansible

## Instructions
Install Ansible using [these](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#pip-install) instructions
```
python3 -m pip install --user ansible
```

Add local bin folder to PATH variable using
```
export PATH=$PATH:~/.local/bin
```

Clone this repo
```
git clone
cd kali-build
```

Make sure we have a sudo token
```
sudo whoami
```

Run the commands in `commands.txt`