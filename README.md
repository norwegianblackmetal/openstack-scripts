OPENSTACK
=
Installation all in one node.
-

Execute the below commands:
1. ansible-playbook -i inventory play-openstack.yml
2. source venv/bin/activate
3. kolla-ansible -i all-in-one bootstrap-servers
4. kolla-ansible -i all-in-one prechecks
5. kolla-ansible -i all-in-one deploy
