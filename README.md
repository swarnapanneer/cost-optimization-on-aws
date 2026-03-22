🚀 AWS Cost Optimization Practice – Automated Stale Snapshot Cleanup using AWS Lambda

 I practiced a real-time AWS cost optimization project using AWS Lambda and Amazon EC2.

🔎 Problem Statement:
Over time, unused EBS snapshots accumulate in AWS accounts, especially from volumes that are no longer attached to EC2 instances. These stale snapshots increase storage costs unnecessarily.

💡 Solution Implemented:
I developed a Python-based Lambda function that:

✔️ Identifies EBS volumes not attached to any EC2 instance
✔️ Finds snapshots associated with those unattached volumes
✔️ Deletes stale snapshots automatically
✔️ Helps reduce unnecessary storage costs

🛠 AWS Services Used:

1. AWS Lambda
2. Amazon EC2
3. Amazon EBS
4. AWS Identity and Access Management

📌 Key Learnings:

Automating infrastructure cleanup improves cost efficiency
IAM roles are critical for secure service-to-service access
Serverless architecture reduces operational overhead

🚀Output screenshots:
<img width="1366" height="768" alt="cost optimization1" src="https://github.com/user-attachments/assets/7c5e574c-2bba-43cd-adc9-1b9b56cbad81" />

<img width="1366" height="768" alt="cost optimization2" src="https://github.com/user-attachments/assets/eac00cbf-4594-4b96-b6bc-a9e4bee604fe" />

<img width="1366" height="768" alt="cost optimization3" src="https://github.com/user-attachments/assets/485a9f9b-54e5-4250-bab9-31808b374fe6" />
