# PaloAlto-FWrules-Decommisioner
Automation of the removal of Security Rules/Address Groups/Address Objects from Palo Alto Firewalls through Ansible
If you are a Network Engineer, and if you are managing the Palo Alto firewalls in your environment, and if you are the one who is doing the tedious job of removing the firewall objects associated with the servers or the appliances that are queued to get decommissioned, then here is the 🆒😎 way to automate that process using Ansible.

Minimum Requirements
A Linux Machine of any distribution
Ansible installed on the linux machine
Python installed on that linux machine
Palo Alto Firewalls

decommisioner.yml  -- The main Playbook
core1.yml  -- Corefile 1 contains first set of tasks that needs to be executed.
core2.yml  -- Corefile 2 contains the intermediate set of tasks that needs to be executed.
vars.yml  -- Variable file, this is where we put the address objects that needs to be removed from the firewalls.
hosts  -- This file contains the list of IP addresses or the hostnames of the PA firewalls that you manage.

Read https://techcraftinator.weebly.com/ for more information.
