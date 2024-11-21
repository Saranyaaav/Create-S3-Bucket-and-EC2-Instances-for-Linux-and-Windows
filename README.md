 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS

## AIM :
To create an S3 bucket and EC2 instances for both Linux and Windows operating systems on AWS.

## PROBLEM STATEMENT :
This experiment demonstrates the process of setting up cloud infrastructure on AWS by creating an S3 bucket for storage and EC2 instances to host Linux and Windows environments. The goal is to provide an overview of how to configure and interact with these resources effectively, along with commands and screenshots to document the process.

## ALGORITHM :

#### Step 1:
Log in to AWS Console</br>

#### Step 2: Create an S3 Bucket</br>
Navigate to the S3 service.</br>
Click on Create bucket.</br>
Enter a Bucket name and select a Region.</br>
Configure Bucket settings as required (e.g., versioning, public access).</br>
Click on Create bucket to finalize.</br>

#### Step 3: Create an EC2 Instance (Linux)
Go to the EC2 service.</br>
Click on Launch Instance.</br>
Select an Amazon Machine Image (AMI) for Linux (e.g., Amazon Linux 2).</br>
Choose an Instance Type (e.g., t2.micro for free tier).</br>
Configure Instance Details, Storage, and Security Group.</br>
Review and click Launch with a key pair (or create one if needed).</br>

#### Step 4: Create an EC2 Instance (Windows)
Return to the EC2 service and click Launch Instance.</br>
Select a Windows AMI (e.g., Windows Server 2019).</br>
Choose the Instance Type.</br>
Configure Instance Details, Storage, and Security Group.</br>
Review and launch with a key pair (for future login).</br>

#### Step 5: Verify and Connect to Instances
Verify the status of both instances in the EC2 dashboard.</br>
Connect to the Linux instance using SSH.</br>
Connect to the Windows instance using RDP.</br>

### REG NUMBER : SARANYA V
### NAME : 212223040188

## OUTPUT

### S3 BUCKET CREATION:
![Screenshot 2024-11-21 222457](https://github.com/user-attachments/assets/fd64e469-4abf-45d9-a413-2c05e4f8c079)

### CONTENT IN BUCKET :
![Screenshot 2024-11-21 222734](https://github.com/user-attachments/assets/178a497b-471c-49a2-8e7b-c8f114015e97)

### REPLICATION :
![Screenshot 2024-11-21 222809](https://github.com/user-attachments/assets/220c0e63-8d38-4384-91b2-92caa5250bda)

![Screenshot 2024-11-21 222853](https://github.com/user-attachments/assets/f9dc53c3-d93e-4c0b-b071-9d21f3d4e720)


### VERSIONING :


### EC2 LINUX:

### EC2 WINDOWS :

## RESULT :
Successfully created an S3 bucket and EC2 instances for both Linux and Windows, demonstrating cloud resource management on AWS.
 

  


