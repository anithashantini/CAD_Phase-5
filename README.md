# CAD_Phase-5 DISASTER RECOVERY WITH IBM CLOUD VIRTUAL SERVERS


OBJECTIVES:
               The IBM Cloud service level objectives documentation provides links to the available high availability, DR, and backup information for the IBM Cloud services that can be used as reference documentation in designing and implementing the DR plan.  To minimize interruptions to   normal  operations. To  limit  the extent of disruption and damage. To minimize  the economic impact of the interruption. To  establish  alternative means of operation in advance.
PHASE 1: PROBLEM DEFINITION AND DESIGN THINKING

Problem Definition:  
                   
                 The project involves creating a disaster recovery plan using IBM Cloud Virtual Servers. The objective is to safeguard business operations by developing a plan that ensures continuity for an on-premises virtual machine in unforeseen events. This plan will include setting up backup strategies, configuring replication, testing the recovery process, and guaranteeing minimal downtime. The project encompasses defining the disaster recovery strategy, implementing backup and replication, validating recovery procedures, and ensuring business continuity. 


Disaster recovery (DR) typically refers to ability to restart IT services from a different geographic location and infrastructure. To implement DR, you need a set of data, compute, and network capabilities in the alternative location and the ability to operate and manage them.

Data can be continuously replicated or periodically refreshed. The time difference between the time of disaster and the age of the data images on the DR site is known as the recovery point objective (RPO). The recovery time objective (RTO) is the time to take the copies of data, associate compute and network, and reprovision the IT service from the alternative location.



The Execution of Code is:

https://github.com/anithashantini/CAD_Phase1


PHASE  2: INNOVATION

AWS services:

Your workload data will require a backup strategy that runs periodically or is continuous. How often you 
run your backup will determine your achievable recovery point (which should align to meet your RPO). 
The backup should also offer a way to restore it to the point in time in which it was taken. Backup with 
point-in-time recovery is available through the following services and resources.

The Execution of Code:

https://github.com/anithashantini/CAD_Phase2










Phase 3: Development Part 1


 




Assessment and Planning:

Identify critical virtual machines (VMs) and their specific roles in your infrastructure.

Determine your Recovery Time Objective (RTO), i.e., how quickly you need to recover after a disaster.

Define your Recovery Point Objective (RPO), which establishes how much data loss is acceptable.

Prioritize VMs based on their importance to your business operations.

Selecting IBM Cloud Services

example, the following are all data plane responsibilities:

Running and hosting the Virtual Server Instance (VSI)

Reading and writing to block storage volumes

Getting and setting objects into Cloud Object Storage Buckets

Running, processing queries and updates to IBM Cloud Databases 
PostegreSQL database.


Listing the Virtual Server Instance instances (VSI) in the account and provisioning a new the Virtual 

Server Instance (VSI) orchestrating the creation of virtual machines from an OS image, block storage 
creation, attachment and configuration of the network endpoints
Configuring, resizing, and mounting block storage volumes.

The code of Execution:

https://github.com/anithashantini/CAD_Phase3



Phase 4: Development part – 2:
 
In this part continuation of building our project.



IBM Cloud CLI or SDKs for various programming languages can be helpful.


Import ibm_boto3
From ibm_botocore.client import CConfi
Cos_credentials = {
 “IAM_SERVICE_ID”: “YOUR_SERVICE_ID”,
 “IBM_API_KEY_ID”: “YOUR_API_KEY”,
 “ENDPOINT”: https://s3.us-south.cloud-object-storage.appdomain.cloud,
 “IBM_AUTH_ENDPOINT”: https://iam.cloud.ibm.com/identity/token,
 “BUCKET_NAME”: “your-bucket-name”
}
Cos = ibm_boto3.client(“s3”,
 Ibm_api_key_id=cos_credentials[“IBM_API_KEY_ID”],
 Ibm_service_instance_id=cos_credentials[“IAM_SERVICE_ID”],
 Ibm_auth_endpoint=cos_credentials[“IBM_AUTH_ENDPOINT”],
 Config=Config(signature_version=”oauth”),
 Endpoint_url=cos_credentials[“ENDPOINT”]
)
Virtual_server_params = {
 “name”: “my-vm”,





The code of execution of disaster recovery is given in below link:
https://github.com/anithashantini/CAD_Phase4


 


The Readme file gives a detailed information about the working of DISASTER RECOVERY WITH IBM CLOUD VIRTUAL SERVERS.
https://github.com/anithashantini/Readme/blob/main/naan%20mudhalvan


