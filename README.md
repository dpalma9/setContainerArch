```bash
pip install --user https://github.com/pypa/virtualenv/tarball/master
sudo apt install libapt-pkg-dev
virtualenv .venv
source .venv/bin/activate
pip install ansible
ansible-playbook --ask-become-pass ansible/main.yml
```
