nginx-configs
=============

Nginx Configurations

This is just a hobby project. Please evaluate configurations and help me to optimize these.

These configurations are mainly configured for wordpress multisite installation on sub domain with domain mapping. Please use http://wordpress.org/plugins/wordpress-mu-domain-mapping/ for better results.

For nginx.conf file

Better to set worker_processes X number based on your CPUs. For finding number of CPUs type following command in shell

cat /proc/cpuinfo | grep processor

This will give you output like

processor : 0
processor : 1

So I have 2 cores. I'll put 2 (on many forums, sites I found they says put the double of your CPU. In my case it would be 4 but I found equal number to number of CPUs is best.