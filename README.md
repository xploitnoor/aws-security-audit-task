# AWS Security Audit Task

This repository documents the security configuration steps I performed on AWS during my internship task

## 🔐 Steps Completed

1. **Enabled CloudTrail**
   - Created a multi-region CloudTrail.
   - Configured logs to be delivered into an S3 bucket.
   - Verified events (e.g., `CreateBucket`, `PutBucketEncryption`) in Event History.

2. **Enabled MFA (Multi-Factor Authentication)**
   - Activated MFA for the AWS root account.
   - (Can be tested during login with authenticator app).

3. **Created Secure S3 Buckets**
   - Created 3 buckets:
     - `aws-cloudtrail-logs-xxxxx`
     - `internee-backup-pk`
     - `internee-backup-us`
   - Enabled **bucket encryption** to secure stored data.

4. **Firewall / DDoS Protection**
   - AWS Shield Standard is automatically enabled (provides free basic protection).

5. **Logs & Monitoring**
   - Verified logs in **CloudTrail Event History**.
   - Events recorded for S3 bucket creation and encryption updates.


screenshots of each steps are attached 
