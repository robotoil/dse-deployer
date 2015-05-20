# dse-deployer
Playbook for building DSE clusters anywhere.

###1 Have SSH access to machines.

###2 Have ansible installed on YOUR machine, no need to install on hosts.

###3 Edit hosts file to include yours.

###4 Edit host_vars to include the config variables.

###5 Edit site.yml to include any new hosts to run against.

###Run ```ansible-playbook -i hosts site.yml``` to build your cluster.

Voila.
