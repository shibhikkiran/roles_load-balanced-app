# roles_load-balanced-app
This is 3 stack setup (ngnix proxy, web servers and backend database server)

The traffic is load balanced between 2 webservers using frontend nginx loadbalancer in rr mode. 

playbooks included to restart the entire stack and check end-to-end status of the stack.
