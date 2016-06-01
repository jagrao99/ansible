# ansible commonly used commands

ansible all —list-hosts

ansible webserver -m setup | more

ansible webserver -m setup --tree /tmp/facts

ansible webserver -m setup -a 'filter=*ipv4'

ansible webserver -m setup -a 'filter=ansible_architecture’

ansible webserver -m setup -a 'filter=ansible_distribution’

ansible webserver -m setup -a 'filter=ansible_domain'

ansible webserver -m setup -a 'filter=ansible_fqdn'

ansible webserver -m setup -a 'filter=ansible_interfaces'

ansible webserver -m setup -a 'filter=ansible_kernel'

ansible webserver -m setup -a 'filter=ansible_memtotal_mb'

ansible webserver -m setup -a 'filter=ansible_processor'

ansible webserver -m setup -a  'filter=ansible_virtualization_type
