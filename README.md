# **PROJECT OVERVIEW**

This project demonstrates how to create and manage an AWS IAM user and securely provide access to an Amazon S3 bucket using IAM policies and 
permissions. The main objective is to understand identity management, access control, cloud storage security, and the principle of least privilege 
in AWS.

# **OBJECTIVES**

Create an IAM user in AWS.

Create an Amazon S3 bucket.

Configure IAM policies for S3 access.

Grant only the required permissions to the user.

Test authorized and unauthorized access.

Understand cloud security best practices.

# **PROJECT ARCHITECTURE**

IAM User → IAM Policy → Amazon S3 Bucket → Access to Authorized Objects

# **CREATE AN S3 BUCKET**

Open Amazon S3.

Select Create bucket.

Enter a globally unique bucket name.

Select the required AWS Region.

Keep Block Public Access enabled unless public access is specifically required.

Create the bucket.

<img width="695" height="354" alt="image" src="https://github.com/user-attachments/assets/971e74cd-812b-4def-8287-0356e4a28f50" />

<img width="680" height="348" alt="image" src="https://github.com/user-attachments/assets/2faf6ad2-76f0-479a-87de-75649dd330b8" />

<img width="716" height="354" alt="image" src="https://github.com/user-attachments/assets/1756c998-d4e2-4dae-a467-6166eeee02d4" />

<img width="670" height="329" alt="image" src="https://github.com/user-attachments/assets/b3ba62c9-d6c6-4eed-8681-1de5cb69b12d" />

# **CONFIGURE IMA PERMISSION**

Create or attach a custom IAM policy that grants the user only the S3 permissions required for the project.

Example permissions may include:

s3:ListBucket – List objects in the specified bucket.

s3:GetObject – Download or read objects.

s3:PutObject – Upload objects.

The exact permissions depend on the project requirements.

<img width="701" height="339" alt="image" src="https://github.com/user-attachments/assets/3f52d9c0-bab3-4d24-a335-90a23ffcd43c" />

<img width="648" height="330" alt="image" src="https://github.com/user-attachments/assets/4343b588-94ef-4d62-ba3c-946f87507b41" />

# **TEST USER ACCESS**

Verify that the authorized user can perform the permitted actions.

Confirm that restricted actions are denied.

Check the IAM policy and bucket permissions if access fails.

# **SECURITY CONFIGURATION**

Follow the principle of least privilege.

Keep S3 Block Public Access enabled.

Enable MFA where appropriate.

Never upload AWS access keys, secret keys, or passwords to GitHub.

Review IAM permissions regularly.

# **EXPECTED OUTCOME**

The project demonstrates how AWS IAM controls user permissions and how Amazon S3 resources can be protected against unauthorized access.

<img width="691" height="354" alt="image" src="https://github.com/user-attachments/assets/09ae66f4-5d23-4645-af6c-5d7454781884" />

# **STEPS FOR UPLODING STML FILE**

1. Download sample HTML file from google (e.g. index.html)

<img width="688" height="402" alt="image" src="https://github.com/user-attachments/assets/3677c498-022e-4a2b-8a1b-8dd49ab1a144" />

2. Click add the HTML file

<img width="699" height="361" alt="image" src="https://github.com/user-attachments/assets/50585b7f-6883-4100-a732-dd88f0950c56" />

3. After adding the file cilck upload

<img width="834" height="502" alt="image" src="https://github.com/user-attachments/assets/27855011-e7a3-4a2e-80df-c70d900ce9ac" />

4. File uploaded successfully

<img width="726" height="390" alt="image" src="https://github.com/user-attachments/assets/d5fb0c2e-9ff0-414e-b2fe-8032493e93da" />

5. After click close check the status for uploading HTML file

<img width="861" height="434" alt="image" src="https://github.com/user-attachments/assets/2d7165c2-267b-4e68-83b7-24bcee10edfb" />

<img width="766" height="390" alt="image" src="https://github.com/user-attachments/assets/1a900595-11fd-4a2e-84ea-949f5c7421e9" />

6. copy the link and open the browser

<img width="788" height="481" alt="image" src="https://github.com/user-attachments/assets/07be7848-39aa-4167-9b6b-03271ed47aeb" />

# **CONCLUSION**

This project provides practical experience with AWS user management and secure cloud storage access. It demonstrates the importance of assigning appropriate permissions 
and protecting data stored in Amazon S3.


 










