<h1>Terraform-Projects</h1>

 

<h2>Description</h2>
Terraform is an open-source Infrastructure as Code (IaC) tool developed by HashiCorp. 
It allows users to define and provision infrastructure resources using a declarative configuration language. 
With Terraform, you can manage infrastructure components such as virtual machines, networks, storage, 
and more across various cloud providers and on-premises environments.In this project, I used terraform to deploy
Resource group, Virtual network, Subnets, and  Storage account on azure cloud.

<br />


<h2>Tools</h2>

- <b>Github</b> 
- <b>Azure Kubernetes Service (AKS)</b>
- <b>Azure Container Registry (ACR)</b>    
- <b>Jenkins</b>
- <b>Azure Kubernetes Cluster</b>

<h2>Deployment Destination </h2>

- <b>Azure Kubernetes Cluster</b> 

<h2>Project walk-through:</h2>

<p align="center">

create a VM with Ubuntu 20.04, install Docker and Docker Compose <br/>

<img width="450" alt="Picture1" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/010f520f-72a7-4217-9ba3-bb3d4472d4e5">

<br />
<br />

Create Azure container registry (ACR) and capture details for futher use. <br/>

<img width="450" alt="Picture2" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/785a119a-0530-4d81-9a5e-3c734daa688e">
<br />
<br />

Create an Azure Kurbenetes Cluster (AKS). <br/>

<img width="450" alt="Picture3" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/58433d13-3a2e-4732-81c7-ea91109045b9">
<br />
<br />

Clone Git repository <br/>

<img width="450" alt="Picture4" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/cdd597eb-86dd-4ee1-94eb-d989c9aad48a">

<br />
<br />

Build the Docker image <br/>

<img width="450" alt="Picture5" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/7ba2ad27-f586-46b8-9e43-00ad48a2756e">

<br />
<br />

Confirm image build on the designated port number on browser <br/>

<img width="450" alt="Picture6" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/7ec23259-d6db-425e-b6d2-e8ba0d4ae7be">


<br />
<br />

Tag image <br/>

<img width="450" alt="Picture7" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/94e394cc-253b-43be-ac99-d1489645a758">

<br />
<br />

Push Tagged image to Azure Container Registry (ACR) <br/>

<img width="465" alt="Picture8" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/2ee4c001-3119-4ceb-862f-27efed83347f">



<br />
<br />


Deploy application to Azure Kurbenetes Cluster (AKS) <br/>

<img width="450" alt="Picture9" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/b739e76f-ae59-4f1a-b16f-ac022242ae74">
<br />
<br />

 Confirm application is working <br/>

<img width="450" alt="Picture10" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/73c8144d-f5ce-4f3f-84d7-60d912dc7ac7">

<br />
<br />

Automate the entire deployment process using Jenkins <br/>




<br />
<br />

<!--






