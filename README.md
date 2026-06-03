# AWS Static Website Hosting Project

**Deployed by:** Swapnil Thik  
**Region:** AWS ap-south-1 (Mumbai)

---

## Architecture

```
User → CloudFront (CDN + HTTPS) → S3 Bucket → IAM Policy
                                       ^
                                 GitHub Actions (CI/CD)
```

---

## Tech Stack

| Service | Purpose |
|---|---|
| Amazon S3 | Static file hosting |
| CloudFront | CDN + HTTPS |
| IAM | Least-privilege deploy user |
| GitHub Actions | CI/CD auto deployment |

---

## Files

| File | Description |
|---|---|
| index.html | Main website |
| bucket-policy.json | S3 public read policy |
| iam-deploy-policy.json | IAM policy for deploy user |
| .github/workflows/deploy.yml | GitHub Actions CI/CD |

---

## Deployment Steps

1. Create S3 bucket, disable Block Public Access, enable Static Website Hosting
2. Apply bucket-policy.json
3. Create IAM user with iam-deploy-policy.json, generate Access Key
4. Add AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY to GitHub Secrets
5. Push to main — auto deploys via GitHub Actions
6. (Optional) Create CloudFront distribution pointing to S3 endpoint

---

## What I Learned

- S3 static website hosting and bucket policies
- IAM least-privilege access control
- CloudFront CDN with HTTPS
- GitHub Actions CI/CD pipeline for AWS
- AWS CLI for S3 operations

---

*AWS Cloud Portfolio Project — Swapnil Thik | AWS Certified Cloud Practitioner 2026*
