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

create provider.tf file in a new folder in terraform <br/>

<img width="450" alt="Picture first pic provideer" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/6fa4b706-164a-4a45-b9d0-b302275effda">

<br />
<br />

create a terraform resource block for resource group <br/>

<img width="450" alt="Picture1 rg" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/10a4b3b9-184a-406e-a8ae-09c9ec6e7b6c">

<br />
<br />

Open a terminal and initiate terraform init, terraform plan and terraform apply <br/>

<img width="450" alt="Picture2 rg" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/4d384df9-3e34-46c4-a173-7899986cd3c1">
<br />
<br />

Confirm resource group deployment in Azure cloud <br/>

<img width="450" alt="Picture3 rg" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/2ea2d3e8-4487-4946-814b-e8c9c3ecb8d3">
<br />
<br />

Create a resource block for Virtual network in terraform <br/>

<img width="450" alt="Picture4 vnet 1" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/018c4d1e-65c3-40a0-8456-6bfcd7be85d1">
<br />
<br />

Create two resource blocks for subnet and apply terraform command <br/>

<img width="450" alt="Picture5 sub 1" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/fe0a33ee-f1c3-4e0a-9a69-9b46d1112097">

<br />
<br />

Deployed Vnet in Azure cloud <br/>

<img width="450" alt="Picture6 vnet 2" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/5ceffb2b-9081-46b6-8397-5921f826dc33">

<br />
<br />

Deployed Subnet in the Vnet created above <br/>

<img width="450" alt="Picture7 sub 2" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/c625996c-9b51-40fd-9d61-dd3802706d38">


<br />
<br />

Create a resource block for resource group in terraform <br/>

<img width="450" alt="Picture8 str 1" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/f6b0c9be-53f8-44de-922c-cc8ade771afd">


<br />
<br />


Create a resource block for storage account in terraform. Apply terraform commands to create resources <br/>

<img width="450" alt="Picture9 str 2" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/30d6d0b1-4f9d-4c96-9ea2-394a9f8a0151">
<br />
<br />

 Resource group deployment confirmation <br/>

<img width="450" alt="Picture10 str 3" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/e424b494-4268-4eb7-8a7a-c2ca9ba0a88b">


<br />
<br />

Storage account deployment confirmation <br/>

<img width="450" alt="Picture11 str 3" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/a4112a9f-83b9-47d6-b1c1-cea5c330097a">


<br />
<br />

<!--






