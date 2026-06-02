<img width="887" height="416" alt="image" src="https://github.com/user-attachments/assets/04a5c950-a119-4573-9772-83fdb6fbc83c" /><img width="896" height="472" alt="image" src="https://github.com/user-attachments/assets/68a15c98-7ab1-4e4b-b046-88e1d3b2f7aa" /># Ex--3-AWS-Account-setup-and-S3-creation-
## Name :sudharsan s
## Reg.no : 212224040335
## Introduction
In this lab, we are going to be introduced to one of the famous Cloud Service providers, Amazon Web Services (AWS). We will work on Amazon Simple Storage Service (S3), which provides storage through web service interfaces (REST, SOAP, and BitTorrent). In S3, the data is stored in the form of buckets. Buckets serve as root folders where we can add, create, or upload files and folders. We can create multiple buckets for different purposes, and each bucket can have different access control policies.

## Objectives

Create a Bucket in Amazon S3.

Add Objects (files and folders) to the bucket.

Access, move, download, and delete the objects.

Delete the Bucket.

Illustration
## Step 1: Choose S3 Service
Choose the S3 service from the list of services provided by AWS.

<img width="887" height="468" alt="image" src="https://github.com/user-attachments/assets/d606202d-82fe-4f71-b32f-eea37e607521" />


## Step 2: Create a Unique Bucket
After selecting the S3 service, click on the "Create Bucket" button on the page. The bucket name must be unique, contain no uppercase letters, and have no special characters. If you enter any of these, an error will display, preventing the bucket from being created.
<img width="887" height="425" alt="image" src="https://github.com/user-attachments/assets/d6065d6a-751a-41b1-8153-bfbdf1132249" />
<img width="887" height="467" alt="image" src="https://github.com/user-attachments/assets/38904f85-4c9f-4565-82de-61f5903d0ce3" />
<img width="885" height="467" alt="image" src="https://github.com/user-attachments/assets/192c62ee-b6e9-414a-ad84-9361cfd7b715" />
<img width="896" height="472" alt="image" src="https://github.com/user-attachments/assets/b42dc45c-c363-4b73-a48a-7eff73f3f615" />
<img width="992" height="518" alt="image" src="https://github.com/user-attachments/assets/3d788a01-5952-4107-a2a4-db087b38e58a" />


For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

## Step 3: Upload Files to the Bucket
Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.
<img width="1023" height="520" alt="image" src="https://github.com/user-attachments/assets/5b9495cf-c1f6-4190-bd2e-f7ed1d9a392c" />
<img width="465" height="402" alt="image" src="https://github.com/user-attachments/assets/fc6f777e-347b-4ff8-bfd9-564f748d2b32" />


You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., https://s3-ap-southeast-2.amazonaws.com/...) to share it.
<img width="746" height="362" alt="image" src="https://github.com/user-attachments/assets/96e4a298-ec99-4831-b7c0-562c2a31f992" />
<img width="887" height="416" alt="image" src="https://github.com/user-attachments/assets/93fcd525-b2f4-4b37-bd65-6d4340beef48" />


## Step 4: Upload a Folder
You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.
<img width="883" height="351" alt="image" src="https://github.com/user-attachments/assets/360522a6-d238-43a7-8bb6-65705926dbae" />

## Step 5: Delete the Bucket
To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.
<img width="350" height="357" alt="image" src="https://github.com/user-attachments/assets/a16c9906-349e-4eab-a3d9-6345b0d77598" />
<img width="866" height="367" alt="image" src="https://github.com/user-attachments/assets/6818c71b-db08-4205-a59b-166a0ede0f35" />


Result
Successfully created, managed, and deleted an S3 bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon S3.
