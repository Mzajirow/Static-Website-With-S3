# ☕ Cafe Static Website on AWS S3

This project demonstrates how to deploy a static website using **Amazon S3**. It was completed as part of a hands-on lab exercise in a cloud computing course environment. The lab walks through setting up a secure, cost-effective, and durable static site infrastructure, including lifecycle management and cross-Region replication.

---

## 📁 Project Structure


---

## 🚀 What This Project Covers

- ✅ Hosting a static website on Amazon S3
- ✅ Granting public read access via a bucket policy
- ✅ Enabling **versioning** to prevent data loss
- ✅ Applying **lifecycle policies** to manage storage cost
- ✅ Setting up **cross-Region replication** for durability & disaster recovery

---

## 🖥️ Live Preview

> 🔗 **Live Preview**: *Hosted in a temporary AWS lab environment – no longer publicly accessible*  
> See screenshots below for configuration and output.

---

## 🧪 Lab Tasks Overview

### Task 1: Prepare Files
- Extracted `index.html` and asset folders from a `.zip` file.

### Task 2: S3 Bucket Creation
- Created an S3 bucket in `us-east-1`
- Enabled static website hosting
- Disabled "Block all public access"
- Set `index.html` as the landing page

### Task 3: Upload Files
- Uploaded HTML and asset files to S3
- Verified static site via S3 endpoint

### Task 4: Bucket Policy
- Configured a bucket policy to auto-enable public read access

### Task 5: Versioning
- Enabled versioning on the S3 bucket
- Modified and uploaded updated HTML to demonstrate file version tracking

### Task 6: Lifecycle Rules
- Rule 1: Moved old versions to S3 Standard-IA after 30 days
- Rule 2: Deleted old versions after 365 days

### Task 7: Cross-Region Replication
- Enabled replication to a second bucket in another AWS region
- Verified replicated files and tested delete behavior

---

## 📸 Screenshots

Add the following to your `screenshots/` folder and link them here in the README:

| Task | Screenshot |
|------|------------|
| Static Website Enabled | ![Static Hosting](screenshots/01-static-hosting.png) |
| Public Access Policy | ![Bucket Policy](screenshots/02-bucket-policy.png) |
| Website Preview | ![Site Preview](screenshots/03-site-preview.png) |
| Versioning Enabled | ![Versioning](screenshots/04-versioning.png) |
| Lifecycle Rules | ![Lifecycle](screenshots/05-lifecycle.png) |
| Replication Setup | ![Replication](screenshots/06-replication.png) |

---

## 💡 Lessons Learned

- How to configure S3 for web hosting
- Best practices for access control, versioning, and disaster recovery
- Cost optimization via lifecycle rules

---

## 📂 Technologies Used

- AWS S3
- IAM Roles
- Lifecycle Policies
- HTML / CSS (static site)

---

## 📬 Contact

If you’d like to see a demo or learn more about this project:

📧 [alexejirow@gmail.com]  
🔗 [GitHub Profile](https://github.com/yourusername)

---

> ✅ This project is part of my cloud computing portfolio. Screenshots demonstrate functionality in place of an active live link.
