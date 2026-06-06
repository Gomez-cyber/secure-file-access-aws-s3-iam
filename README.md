# secure-file-access-aws-s3-iam
AWS S3 security project showcasing IAM policy enforcement to restrict and control file access, demonstrating secure cloud storage design and identity-based access management.
# 🔐 AWS S3 IAM Access Control Project

## 📌 Overview
This project demonstrates secure access control in Amazon S3 using AWS Identity and Access Management (IAM). It shows how to enforce least-privilege access, ensuring only authorized users can access and download files while unauthorized users are restricted.

---

## 🚀 Project Objective
To build a secure cloud storage system where:
- Authorized IAM users can access and download files from an S3 bucket
- Unauthorized IAM users cannot access or view the bucket contents

---

## 🧰 Technologies Used
- Amazon S3 (Simple Storage Service)
- AWS IAM (Identity and Access Management)
- AWS Management Console

---

## 🏗️ Architecture
- A private S3 bucket was created
- Public access was fully blocked
- IAM users were created with different permission levels
- Access was controlled using IAM policies (least privilege principle)

---

## 👥 Users & Permissions

### 👤 Authorized User (`file-user`)
- Can view S3 bucket
- Can access and download files

### 🚫 Unauthorized User (`not-permitted-user`)
- Cannot see the bucket
- Cannot access any files

---

## 🔐 Security Implementation
- Blocked all public access to the S3 bucket
- Used IAM policies to manage user permissions
- Applied least privilege principle
- Ensured access is granted only to authorized users

---

## 🧪 Testing Results

### ✅ Authorized Access
- `file-user` successfully accessed and downloaded files from S3

### ❌ Unauthorized Access
- `not-permitted-user` had no access to the bucket or files

Screenshots
<img width="1361" height="727" alt="s3-bucket-overview png" src="https://github.com/user-attachments/assets/04ccf001-284b-424e-a4d8-c3586b277803" />
<img width="1366" height="729" alt="file-user  authorised access png" src="https://github.com/user-attachments/assets/32f090c4-614d-45bf-bc1c-c18460b3bec8" />
<img width="1366" height="728" alt="not-permitted  unauthorised access png" src="https://github.com/user-attachments/assets/6fa71c12-e9c3-4618-bd34-6130fe8969c6" />
Video of file access


https://github.com/user-attachments/assets/9e45cbb7-c74c-44e6-9b6d-812b50a0d790



https://github.com/user-attachments/assets/8a697073-4119-4a82-a7b2-0245850bda1b

💡 Key Learnings
- How IAM controls access to AWS resources
- Difference between authorized and unauthorized access
- Importance of least privilege security model
- How S3 bucket policies and IAM policies work together

---

## 🔮 Future Improvements
- Implement pre-signed URLs for temporary access
- - Add logging using AWS CloudTrail

    🙌 Author
    Gomez







