# ONS-ODL-Tutorial

Instructions:</br>

1.  You must be able to SSH to the virthost machine as root without a password from the machine running Ansible:</br>
    $ ssh-keygen root@127.0.0.2
    
2.  Clone tripleo quickstart git repo:</br>
    $ git clone https://github.com/openstack/tripleo-quickstart
    
3.  run quickstart</br>
    $ bash quickstart.sh -R master --nodes config/nodes/1ctlr_1comp.yml --config config/general_config/featureset031.yml 127.0.0.2

    
