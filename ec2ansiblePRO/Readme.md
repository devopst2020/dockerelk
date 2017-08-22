Approach followed:

1. Created elk and wordpress (docker hub) containers using dockerile and executed using docker-compose up in local vagrant machine. ELK container is hosted on elk instance and
wordpress on wordpress instance.(mywp.zip , elk-docker.zip)
 
2. Created two ec2 instances with elastic IP attached , all ingress and egress ports  for wordpress and elk instances using ansible playbook (allec2.yml)
3. Installed oracle java 8 , docker and docker-compose using ansible playbook. (java_doc_doccomp.yml)
4. Copied the zip files of wordpress, elk dockerfiles and docker-compose to respective instances and fired docker-compose up.(elkshahu.yml , shahuscp.yml)
5. Access the wordpress url (http://52.51.150.252:8080/) , kibana (http://34.251.177.202:5601/) for dashboard setup.
