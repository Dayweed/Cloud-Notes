# Key things to note
# Chapter 1
* ### Cloud Computing enables computing services which provide IT-related capabilities such as computers, storage and apps with pay-per-use models
* ### Virtualization shares the physical IT resource with multiple users via different Cloud service models
* ### Hypervisor is a form of virutalization that allows one computer to host multiple guest VMs by sharing the resources such as memory and processing
* ### Container Runtime Engine is a form of OS virtualization that support multiple applications to run on the same OS
* ### New cloud computing technologies such as microservices, serverless computing, etc enable app modernization and deploy and run cloud services in dynamic cloud environments
# Chapter 2
## 3 Models IaaS PaaS SaaS
* ### IaaS
![](ImageAssets/Cpt2.2.png)
* ### PaaS
![](ImageAssets/Cpt2.5.png)
* ### SaaS
![](ImageAssets/Summary.1.png)
* ### Rough Look on all 3 models
![](ImageAssets/Cpt2.1.png)
## 2 New models CaaS FaaS
![](ImageAssets/Cpt2.7.png)
# Chapter 3
## 4 Cloud Deployment Models
* ### Public
![](ImageAssets/Summary.2.png)
* ### Private
![](ImageAssets/Summary.3.png)
* ### Hybrid
![](ImageAssets/Summary.4.png)
* ### Multi
![](ImageAssets/Summary.5.png)
## 3 Types of Cloud Architectures
* ### Simple Basic Architecture
![](ImageAssets/Cpt3.3.png)
![](ImageAssets/Cpt3.4.png)
* ### Cloud architecture with Load Balancer (Redundancy)
![](ImageAssets/Cpt3.5.png)
![](ImageAssets/Summary.6.png)
  * Redundancy is duplication/back-up of data to allow individual failures
* ### Cloud architecture with Elasticity
![](ImageAssets/Cpt3.7.png)
  * Elasticity is just auto scaler
# Chapter 4
* ## Cloud data storages comes in 4 different types
![](ImageAssets/Summary.7.png)
  * ### Object Storage
  * ### Block Storage
  * ### Networked file systems
  * ### Data archiving storage
* ## Cloud database allows users to use cloud managed database solutions
![](ImageAssets/Summary.8.png)
  * ## SQL database
    * ### Uses sql
    * ### store in row/col table
    * ### fixed schema
    * ### vertical scaling
  * ## NoSQL database
    * ### use a variety of query lang
    * ### stored in/with key-val/document/ wide col/graph
    * ### flexible schema
    * ### horizontal scaling
  * ### Graph database
  * ### In-memory database
* ### Cloud AI tools and services use various technologies across AI lifecycle to support, develop, deploy,, monitor and sharing of AI solutions
* ### Cloud data analytic tools and services provide online tools for data operations such as data warehouse query data transformation, stream operations, scalable data processing, visualization and BI analytics
# Chapter 5
* ## In Cloud shared respondsibility model both user and cloud service providers are respondsible for security and compliance. Specific Responsibilities vary on the service model
* ## Identity and Access Management(IAM) is a fine grant control specifying who or what resources can access. It also maanges identites across single or multiple AWS accounts and refine access perms using IAM policies
* ## VPCs and subnets isolate sections containing a pool of resources from the public cloud. Users can set rules in Firewall/Security Groups and specify the route tables to control network access
* ## Data encryption is a process converting plaintext data into ciphertext to protect data. One of the most effective ways to protect cloud data *in transit or at rest*