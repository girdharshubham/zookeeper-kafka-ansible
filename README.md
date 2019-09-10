This xlr8r requires the following variables:
  - user
  - group
  - device_name
  
** This xlr9r assumes that the ipv4 interface is eth0

`ansible-playbook -i <path/to/inventory> kafka_playbook.yml -e user=<shubham> -e group=<group> -u <user>`
