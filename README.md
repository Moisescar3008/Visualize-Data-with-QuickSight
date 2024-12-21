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
5. Click **Create bucket** to finalize.

   ![Creating an S3 bucket](<img width="749" alt="bucket creation" src="https://github.com/user-attachments/assets/436d3a19-05e9-42c3-87b0-31c2b6a295b1" />)

## Uploading Files to S3

1. Upload the necessary files to your Amazon S3 bucket.

   ![Uploading files to S3](path/to/image1.png)

2. Select the bucket where the files are located.

   ![Selecting a bucket](path/to/image2.png)

## Setting Up in QuickSight

1. Create a QuickSight account if you don’t already have one.
2. Navigate to **Databases** and select **New dataset**.
3. Select the **S3** option.
4. Fill in the two fields:
   - In the first field, type the name of your project.
   - In the second field, navigate to your S3 bucket, select the JSON file, and copy its S3 URL.

   ![Setting up a dataset in QuickSight](path/to/image3.png)

## Creating Visualizations

1. Once your database is imported into QuickSight, start creating visualizations based on your requirements.

   ![Creating visualizations in QuickSight](path/to/image4.png)

2. After completing your analysis, you can save it:
   - Click on the right panel.
   - Select **Export**.
   - Choose **PDF File**.

   ![Exporting a visualization](path/to/image5.png)

## Exporting and Deleting Your Account

1. To avoid additional charges, it is recommended to delete your QuickSight account after finishing:
   - Select **Account settings** in the right panel.
   - Confirm the termination of your account.

   ![Deleting QuickSight account](path/to/image6.png)

2. You can recreate the account in the future if needed.

## Final Notes

This process ensures you can upload data, analyze it, and export results without incurring unexpected costs. If you have questions, refer to the [official AWS documentation](https://aws.amazon.com/documentation/).

---

Thank you for using this guide. Good luck with your data analysis!
