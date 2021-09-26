OPENSTACK
=
Installation all in one node.
-

Execute the below commands:
1. ansible-playbook -i inventory play-openstack.yml
2. kolla-ansible -i all-in-one bootstrap-servers
3. kolla-ansible -i all-in-one prechecks
4. kolla-ansible -i all-in-one deploy
