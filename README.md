# WSL2 Ubuntu development environment via Ansible

## Preliminaries on the Windows Host

1. Install Terminal from the Microsoft Store
2. Install Caskayda Cove Nerd Font from https://www.nerdfonts.com/font-downloads and set it as Font for the Terminal Ubuntu Profile (Settings -> Display)

## Preliminaries on the fresh System

1. Set locale to US via `sudo dpkg-reconfigure`
2. Install pip via `sudo apt update && sudo apt install python3-pip`
2. Install pip via `python3 -m pip install --user ansible`
3. Install ansible via `sudo apt install ansible`. Restart shell for ~/.local/bin to be added to bin

## Run

Run via `ansible-playbook fish_shell.yml --ask-become-pass` to run everything localy
Do same for the other files.

