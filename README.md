Description:
Creation of a EKS Cluster over AWS Cloud. Connect to the cluster using kubectl CLI.

==== Deployment steps:

1. git clone git@github.com:thiru1102/devops-task2.git 

2. files as part of repo devops-task2[7 files]


service.yml\
RBAC.yml\
pdb.yml\
nginx-deployment.yml\
namespace.yml\
hpa.yml\
api_key_secret.yml


3. Execute the below commands.
Command to deploy app : kubectl apply -f devops-task2
** all the manifest files created inside the devops-task2 folder will be applied for the following resources svc account, pdb, deployment, svc, hba.

4. open the browser and hit http://\<loadbalancer FQDN> 
