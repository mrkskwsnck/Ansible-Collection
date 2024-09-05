# Ansible Collection

My very own collection of Ansible playbooks, roles and tasks.

## Requirements

```bash
# For Debian as a platform
sudo apt install python3-venv
```

## Getting started

```bash
# Clone and enter the project
git clone https://github.com/mrkskwsnck/Ansible-Collection.git
cd Ansible-Collection

# Create and enter the virtual environment
python3 -m venv venv
source venv/bin/activate

# Install Python and Ansible dependencies inside the virtual environment
pip3 install --upgrade --requirement requirements.txt pip
ansible-galaxy collection install --requirements-file requirements.yaml

# Leave virtual environment
deactivate
```

## License

> Copying and distribution of this file, with or without modification,
> are permitted in any medium without royalty provided the copyright
> notice and this notice are preserved.  This file is offered as-is,
> without any warranty.
