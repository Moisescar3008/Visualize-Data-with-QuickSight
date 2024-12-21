# Visualize Data with QuickSight and S3

This project guides you through the process of uploading data to Amazon S3 and visualizing it using Amazon QuickSight.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Creating an S3 Bucket](#creating-an-s3-bucket)
3. [Uploading Files to S3](#uploading-files-to-s3)
4. [Setting Up in QuickSight](#setting-up-in-quicksight)
5. [Creating Visualizations](#creating-visualizations)
6. [Exporting and Deleting Your Account](#exporting-and-deleting-your-account)
7. [Final Notes](#final-notes)

## Prerequisites

- An AWS account configured.
- Permissions to create and manage buckets in Amazon S3.
- Access to Amazon QuickSight.

## Creating an S3 Bucket

1. Log in to the AWS Management Console.
2. Navigate to the **S3** service.
3. Click on **Create bucket**.
4. Provide a unique name for your bucket and configure the settings as needed.
5. Click **Create bucket** to finalize and upload the files.

   ![Texto alternativo](https://github.com/user-attachments/assets/436d3a19-05e9-42c3-87b0-31c2b6a295b1)



## Setting Up in QuickSight

1. Create a QuickSight account if you don’t already have one.
In the part of registration, this will show you:
    ![Texto alternativo](https://github.com/user-attachments/assets/645f1936-97f2-4d50-b515-a179bd8e1d66)
And after that select S3:
    ![Texto alternativo](https://github.com/user-attachments/assets/fad49bc2-be41-420c-8e1f-b71b43145ea0)
Select our S3 bucket:
     ![Texto alternativo](https://github.com/user-attachments/assets/abe754cc-61e1-4eff-8ecf-1f419efd5760)
And you have your Quicksight account with the S3 Bucket.
2. Navigate to **Databases** and select **New dataset**.
3. Select the **S3** option.
4. Fill in the two fields:
   - In the first field, type the name of your project.
   - In the second field, navigate to your S3 bucket, select the JSON file, and copy its S3 URL.

  ![Texto alternativo](https://github.com/user-attachments/assets/8678c013-b24c-4f03-9111-06000b85fbfd)


## Creating Visualizations

1. Once your database is imported into QuickSight, start creating visualizations based on your requirements.

2. After completing your analysis, you can save it:
   - Click on the right panel.
   - Select **Export**.
   - Choose **PDF File**.

   ![Visualizations](https://github.com/user-attachments/assets/4dfd3248-634f-46e0-ae1b-62c6b7c36bd6)


## Exporting and Deleting Your Account

1. To avoid additional charges, it is recommended to delete your QuickSight account after finishing:
   - Select **Account settings** in the right panel.
   - Confirm the termination of your account.

   ![Screenshot 2024-12-21 145634](https://github.com/user-attachments/assets/7f822869-53a5-4562-b323-ae83442e3ad0)


2. You can recreate the account in the future if needed.

## Final Notes

This process ensures you can upload data, analyze it, and export results without incurring unexpected costs. If you have questions, refer to the [official AWS documentation](https://aws.amazon.com/documentation/).

---

Thank you for using this guide. Good luck with your data analysis!
