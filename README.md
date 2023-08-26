
### ABOUT THE ROLE ###

This is an ansible task that creates and configures ubuntu ( or other ) cloud init image over proxmox. 
If you haven't heard about ansible tasks, they are basicly segmented playbooks.
This playbook would be possible with out colbylol's ansible task, that the role is based for so credits for him ( gist:https://gist.github.com/colbylol/78a4dec09043f450bb1c8b8d8cdc5e19 )

### REGUIREMENTS ###

The only reguiremen't for this playbook is community.general.proxmox_kvm and it can be installed with ansible-galaxy collection install community.general

### USAGE ###

make changes only to ./cloudinit/defaults/main.yml

The manings of the variables are explained in there

Good luck on troubleshooting, because I can couranteen that it won't work fist time
