Configuring Mac OS X with Ansible
=================================

Automating instalation of software and configuring settings for my OS X setup.
Adapted based on scripts of my friend Adam (https://github.com/adamchainz). 

Dependencies:

- Ansible 1.6
-  `homebrew`
- `homebrew_cask` 

To run:

    ansible-playbook playbook.yml

Optionally add `--skip-tags brew` to skip the slow brew stuff.
