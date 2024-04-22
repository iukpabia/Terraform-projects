<h1>Terraform-Projects</h1>

 

<h2>Description</h2>
Terraform is an open-source Infrastructure as Code (IaC) tool developed by HashiCorp. 
It allows users to define and provision infrastructure resources using a declarative configuration language. 
With Terraform, you can manage infrastructure components such as virtual machines, networks, storage, 
and more across various cloud providers and on-premises environments.In this project, I used terraform to deploy
Resource group, Virtual network, Subnets, and  Storage account on Azure cloud.

<br />


<h2>Tools</h2>

- <b>Azure cloud Account</b> 
- <b>Azure Cli</b>
- <b>Visual Studio</b>    
- <b>Terraform</b>
  

<h2>Deployment Destination </h2>

- <b>Azure Cloud</b> 

<h2>Project walk-through:</h2>

<p align="center">

create a terraform resource block for resource group <br/>

<img width="450" alt="Picture1 rg" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/10a4b3b9-184a-406e-a8ae-09c9ec6e7b6c">

<br />
<br />

Open a terminal and initiate terraform init, terraform plan and terraform apply <br/>

<img width="450" alt="Picture2 rg" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/4d384df9-3e34-46c4-a173-7899986cd3c1">
<br />
<br />

Confirm resource group deployement in Azure cloud <br/>

<img width="450" alt="Picture3 rg" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/2ea2d3e8-4487-4946-814b-e8c9c3ecb8d3">
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






