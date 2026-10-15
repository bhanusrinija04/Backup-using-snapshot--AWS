    # AWS Backup Automation for Disaster Recovery

A Python-based AWS backup automation project designed to help protect cloud data and support recovery during accidental deletion, data loss, or infrastructure failures.

## 📌 Project Overview

This project explores automating AWS backup operations using Python and the Boto3 SDK. It focuses on creating Amazon EBS snapshots and supporting the restoration of data when recovery is needed.

## 🎯 Objectives

- Automate AWS backup operations using Python and Boto3.
- Create snapshots of Amazon EBS volumes.
- Support recovery by restoring data from available snapshots.
- Improve awareness of cloud data protection and disaster recovery practices.

## 🛠️ Technologies Used

- **Language:** Python
- **AWS SDK:** Boto3
- **Cloud Services:** Amazon EC2, Amazon EBS, Amazon EBS Snapshots

## ⚙️ How It Works

1. Configure AWS credentials and permissions.
2. Identify the EBS volume that needs to be backed up.
3. Use Python and Boto3 to initiate a snapshot.
4. Check the snapshot status to confirm completion.
5. When recovery is required, use the snapshot to create a new EBS volume and follow the required recovery steps.

*The exact workflow depends on the implementation in this repository.*

## 🚀 Getting Started

### Prerequisites

- Python 3 installed
- An AWS account
- AWS IAM permissions appropriate for the EC2 and EBS operations used by the script
- Boto3 installed

### Installation

Clone the repository:

```bash
git clone https://github.com/bhanusrinija04/Backup-using-snapshot--AWS.git
cd Backup-using-snapshot--AWS
```

Install Boto3:

```bash
python -m pip install boto3
```

Configure your AWS credentials using a secure method, such as the AWS CLI or an IAM role.

**Important:** Never upload AWS access keys, secret keys, or other credentials to GitHub.

## 🧪 Testing and Validation

- Run the script in an appropriately configured AWS environment.
- Verify that the expected snapshot is created.
- Check the snapshot status in the AWS console or through Boto3.
- If restoration is implemented, verify recovery using a test volume and non-production data.

## 🌟 What I Learned

- Using Python and Boto3 to interact with AWS services.
- Understanding EBS snapshots and cloud backup workflows.
- Learning the importance of recovery planning and secure cloud access.

## 👩‍💻 Author

**Bhanu Srinija**

AI/ML | Software Development | AWS

[GitHub Profile](https://github.com/bhanusrinija04) · [LinkedIn](https://www.linkedin.com/in/bhanu-srinija-kalakoti-4b36b4295/)
