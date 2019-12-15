# debian-vm-boilerplate
A simple bash script to handle boilerplate configurations for cloned Debian VMs.

# Usage
Run the following command from a bash session, you will be prompted for a new hostname, and whether you wish to reboot the system.

<b>NOTE: Make sure you wait for all services to start before running this script, otherwise weirdness may ensue!</b>

`sudo bash -c "bash <(wget -qO- https://raw.githubusercontent.com/turkicnomad/debian-vm-boilerplate/master/run.sh)"`
