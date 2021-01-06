# Using Ansible to Deploy and Update my Config

## Pre-Reqs
> You must have ansible installed

The only way I am able to get this working is by using sudo and running a command before using ansible-pull.
	```
	sudo apt update && ansible-pull -U https://github.com/zer0sense/ansible_desktop
	```

	```
	sudo pacman -S && ansible-pull -U https://github.com/zer0sense/ansible_desktop
	```