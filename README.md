# This is ansible playbook for Apache Mesos.(for ubuntu xenial) #

## How to use ##

1. Modify `hosts` file for your own connection way.
   Remember define 
     * `connection_interface`: for every host to specify network interface which host used to connect to each other.

     * `master_id`: for every master host to specify unique id of zookeeper masters.

2. Execute playbook, `main.yml`.