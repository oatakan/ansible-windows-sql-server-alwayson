# ansible-windows-sql-server-alwayson
This repo contains example Ansible playbooks to create a Windows SQL Server Alwayson cluster

It includes the following playbooks:

   - ad_computer_deregister_all.yml # deregister all computer objects including cluster object from AD
   - sql_nodes_infra_multi.yml  # provision infrastructure
   - sql_nodes_remove_multi  # remove infrastructure
   - sql-server-alwayson-cluster-create.yml # create SQL Server AlwaysOn cluster