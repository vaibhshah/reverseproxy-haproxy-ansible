# reverseproxy-haproxy-ansible

Whenever we launch any website, we must think that load should come equally on all our webservers and all our them should remain secure, these all can be done by a Reverse Proxy.
It becomes hectic when we have to manually configure all servers and Reverse Proxy.
So #automation is the need and we can configure it very easily using #Ansible.


📌 Use Ansible playbook to Configure Reverse Proxy i.e. HAProxy and update it's configuration file automatically on each time new Managed node (Configured With Apache Webserver) join the inventory.

🔹 Using the Ansible playbook, we can add as many web servers and we just have to make that IP entry in ansible inventory file and all other configurations will be done dynamically by the ansible.
