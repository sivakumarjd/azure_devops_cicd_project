# azure_devops_cicd_project
PROJECT # AZURE DEVOPS CI/CD MULTI-TIER JAVA APPLICATION DEPLOYED IN AKS
AWS – EC2 (Azure Agent)
update package
>sudo apt update
 
java install
>sudo apt install openjdk-17-jre-headless
 

maven install
>sudo apt install maven
 
docker install
>sudo apt install docker.io
 
>sudo chmod 666 /var/run/docker.sock
Login – GitHub
 

Login – DockerHub

 
>docker run -d -p 9000:9000 mc1arke/sonarqube-with-community-branch-plugin
 
Trivy Installation
 
AWS Security Groups
 
SonarQube – admin/Full*****123
 
Agent Setup
 
>wget https://vstsagentpackage.azureedge.net/agent/4.252.0/vsts-agent-linux-x64-4.252.0.tar.gz
 
 

 
 
 

 
 
 
Writing Pipeline
 
1.	Use the classic editor to create a pipeline
2.	Use YAML to create a pipeline
 

 
 
 
 
 
 
 
 

 
Adding SonarQube from Market Place
 

 

 

Save&Queue
 
 
Trivy Plugin
 

Docker Plugin
 

 
 
 

 

 
 


 

Release pipeline(CD Stage)

 

 

 
 

 
Azure – Launch AKS for deployment
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 

 

 

 
Enable Auth to connect Microsoft azure account – connect with browser enable popup in case blocked

 
 

Source changes in Azure Repo
 


CI PIPELINE Triggered
 

CD PIPELINE Triggered
 


 
 

Agent – Bring up to listen job
 

AKS Deployment:
 
Logs:
 
 
 
 
 
 

http://48.217.193.231/

 

 
   


 

 

