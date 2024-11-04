# Ex--6-AWS-Account-setup-and-S3-creation-
# Introduction

In this lab, we are going to be introduced to one of the famous Cloud Service providers, Amazon Web Services (AWS). We will work on Amazon Simple Storage Service (S3), which provides storage through web service interfaces (REST, SOAP, and BitTorrent). In S3, the data is stored in the form of buckets. Buckets serve as root folders where we can add, create, or upload files and folders. We can create multiple buckets for different purposes, and each bucket can have different access control policies.

## Objectives

- Create a Bucket in Amazon S3.
- Add Objects (files and folders) to the bucket.
- Access, move, download, and delete the objects.
- Delete the Bucket.

## Illustration

### Step 1: Choose S3 Service

Choose the S3 service from the list of services provided by AWS.

(![image](https://github.com/user-attachments/assets/d641bb01-a8f8-405c-914b-5ff7840a539d))

### Step 2: Create a Unique Bucket

After selecting the S3 service, click on the "Create Bucket" button on the page. The bucket name must be unique, contain no uppercase letters, and have no special characters. If you enter any of these, an error will display, preventing the bucket from being created.

![image](https://github.com/user-attachments/assets/6a447548-5dbb-4bee-be9a-14823d0bf6b0)

![image](https://github.com/user-attachments/assets/8f0c2e75-1106-4666-b67d-6335aab13ab8)

![image](https://github.com/user-attachments/assets/216498f3-1fbd-457e-b930-9589d28be372)

![image](https://github.com/user-attachments/assets/71c2e496-28bb-4f42-bf14-8cbe08eff585)

![image](https://github.com/user-attachments/assets/a2d2d240-9250-49b6-9acb-062339e2f746)


For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

### Step 3: Upload Files to the Bucket

Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.

![image](https://github.com/user-attachments/assets/1093a03c-6b67-4a0f-8baa-5e5aa2a1fcb0)

![image](https://github.com/user-attachments/assets/3a137296-7bce-474e-9aee-90f1270da0b5)

You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., `https://s3-ap-southeast-2.amazonaws.com/...`) to share it.

![image](https://github.com/user-attachments/assets/213b9304-7fc2-443d-88a7-9e093dcf6d43)

![image](https://github.com/user-attachments/assets/84431c22-23ab-4a72-8c8a-52c79945a6d0)


### Step 4: Upload a Folder

You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.

![image](https://github.com/user-attachments/assets/f0ad8c4e-0d66-490f-a4e0-3ecc1d39ba25)

### Step 5: Delete the Bucket

To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.

![image](https://github.com/user-attachments/assets/c09b5618-9d48-4d70-b59a-e76dd9c163f6)

![image](https://github.com/user-attachments/assets/d3e6652a-26a5-45ed-8b20-d92d88dc7dd0)


## Result

Successfully created, managed, and deleted an S3 bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon S3.

