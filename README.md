# Mac Development Ansible Playbook

_inspired by https://github.com/geerlingguy/mac-dev-playbook/tree/master_

## Initial config of brand new machine

After completing the mandatory macOS setup wizard:

* Ensure Apple's command line tools are installed `xcode-select --install`
* Install Homebrew
* Install ansible via homebrew `brew install ansible`
* Clone this repo `git clone git@github.com:twesterhuys/ansible.git`
* Install required collections and roles: `ansible-galaxy install -r requirements.yml`
* Run the playbook `ansible-playbook main.yml --ask-become-pass`
