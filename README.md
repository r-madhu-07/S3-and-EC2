# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
## NAME: M DANISH SAMUEL
## REG NO: 212224040057

## Aim
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

---

## Procedure

### a) Steps to Create a First S3 Bucket

1. **Sign in to AWS Management Console**
   - Go to: https://console.aws.amazon.com/s3

2. **Open the S3 Service**
   - Search for **S3** in the search bar and open it.

3. **Create Bucket**
   - Click the **Create bucket** button.

4. **Configure Bucket Settings**
   - **Bucket name**: Choose a globally unique name.
   - **AWS Region**: Select the region where you want to store your data.

5. **Object Ownership**
   - Choose:
     - **ACLs disabled** (recommended) — Bucket owner has full control.
     - **ACLs enabled** — Control access via access control lists.

6. **Block Public Access Settings**
   - By default, public access is blocked. Leave it as-is unless you need public access.

7. **Bucket Versioning** (Optional)
   - Choose whether to enable versioning for objects in the bucket.

8. **Encryption** (Optional)
   - Select encryption options: **SSE-S3**, **SSE-KMS**, or none.

9. **Advanced Settings** (Optional)
   - Add tags, configure logging, etc.

10. **Create the Bucket**
    - Click **Create bucket** at the bottom of the page.

---

### b) Steps to Launch an EC2 Instance

1. Go to the **EC2 Dashboard** in AWS Console.
2. Click on **Launch Instance**.
3. **Choose an Amazon Machine Image (AMI)** (e.g., Amazon Linux).
4. **Select an Instance Type** (e.g., t2.micro for Free Tier).
5. **Create or Choose a Key Pair** for SSH access.
6. **Configure Network Settings** (use default VPC/subnet).
7. **Configure Storage** (default root volume is fine).
8. **Review and Launch**
   - Review settings and click **Launch Instance**.
9. **Wait for the instance** to enter the **running** state.

---

### c) Connect to Your EC2 Instance

- **Linux Users**: Use SSH command with your `.pem` key.
- **Windows Users**: Use RDP with decrypted admin password.

---

### d) Steps to Clean Up (Terminate the Instance)

1. Go to **EC2 Instances**.
2. Select your instance → **Instance State** → **Terminate**.

---
## Snapshots
#### Snap Shot 1: Simple Storage Service (S3)
![Screenshot 2025-05-21 102653](https://github.com/user-attachments/assets/7855d7ad-f9ea-49b8-91a6-ad495b0a7633)
#### Snap Shot 2:  EC2 (Elastic Compute Cloud) – Instance
![Screenshot 2025-05-21 102550](https://github.com/user-attachments/assets/52d44c89-5dd5-4d1a-a2fe-41c04b0bce52)

## Result

Thus, a **Simple Storage Service (S3)** and **EC2 (Elastic Compute Cloud)** instance has been successfully created and launched in AWS.
