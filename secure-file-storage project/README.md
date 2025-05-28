# Secure File Storage on AWS (Cloud-Based Project)

This project showcases how to securely store and access files in the cloud using *Amazon S3* with best practices around access control, cost efficiency, and visibility.

## 🚀 Project Overview
I designed and implemented a secure file storage system on AWS, simulating how businesses can store, control, and audit access to sensitive files.

## 🔧 What I Did
- Created an Amazon S3 bucket for secure storage
- Set up IAM policies for access control
- Configured AWS CLI and uploaded test files
- Enabled server access logging for visibility and audit trail
- Applied controlled bucket policies for secure public/private access

## 🛡 Security Features
- *IAM Policies* to manage permissions
- *Bucket Policies* to restrict or allow specific access
- *Server Access Logging* for full visibility of access requests

## 💰 Cost Optimization
- Avoided public IPv4 charges by using secure access methods
- Enabled logging without triggering extra charges
- Ensured minimal use of chargeable resources in AWS Free Tier

## 🌍 Real-World Relevance
This setup mimics how startups or small businesses can:
- Store customer data safely
- Track who accesses what
- Reduce cloud costs
- Control external/public access to files

## 📂 Technologies Used
- AWS S3
- AWS IAM
- AWS CLI
- JSON (for IAM & bucket policies)

## 🧪 How to Reproduce
1. Create an S3 bucket
2. Set up IAM user and attach a custom policy
3. Configure AWS CLI with the IAM credentials
4. Upload files securely using the CLI
5. Enable server access logging
6. Apply bucket policy to control access

## 🙌 Author
Opeyemi Oteniya   
[GitHub Profile](https://github.com/yemiote)