# ansible
ansible playbooks

Below roles are created and used in playbooks.

Roles:
1.elasticsearch
2.iptables
3.jave7
4.java8
5.nginx
6.packages
7.rabbitmq
8.blackbox_exporter
9.node_exporter
10.pushgateway
11.prometheus
12.memcached_exporter
13.consul
14.consul_exporter
15.memcached
16.rabbitmq_exporter
17.redis_cluster
18.redis_exporter

Below Playbooks are created and some playbooks need to have specific inventory format to work. You can go to each playbook and refer ansible_host file.
1.blackbox_exporter
2.consul
3.consul_exporter
4.elasticsearch
5.java7
6.java8
7.memcached
8.memcached_exporter
9.node_exporter
10.prometheus
11.pushgateway
12.rabbitmq
13.rabbitmq_exporter
14.redis_cluster (Refer this playbook readme to create cluster)
15.redis_exporter

#Requirement:
All playbooks are specific to work for only centos 7.

#Future Releases:
Same playbooks will be updated to work for debian based system and centos 6 and 8 as well.