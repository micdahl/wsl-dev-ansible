# WSL2 Ubuntu development environment via Ansible
## Preliminaries on a fresh System
1. Set locale to US via `sudo dpkg-reconfigure`
2. Install pip via `sudo apt install python3-pip`
3. Install ansible via `sudo apt install ansible`. Restart shell for ~/.local/bin to be added to bin

## Run
Run via `ansible-playbook ansible-local.yml --ask-pass -K` to run everything localy

