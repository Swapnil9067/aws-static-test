# AWS Static Website Hosting

**Live URL:** http://swapnil-thik-static-site.s3-website.ap-south-1.amazonaws.com

---

## About This Project

A static website deployed on **Amazon S3** as part of my AWS cloud portfolio.
Hosted in AWS ap-south-1 (Mumbai) region.

---

## Screenshots

### Live Website
<img width="1920" height="1080" alt="Screenshot 2026-06-07 065414" src="https://github.com/user-attachments/assets/23c08fd8-f675-471c-be6a-2a5634baab43" />

### S3 Bucket Configuration
<img width="1920" height="1080" alt="Screenshot 2026-06-07 063513" src="https://github.com/user-attachments/assets/4cd942ec-3247-456f-9102-01b5679d7dfb" />
<img width="1920" height="1080" alt="Screenshot 2026-06-07 064038" src="https://github.com/user-attachments/assets/b30a9121-1864-4012-83c4-0ab055ad2c6a" />

### Policy Configuration
<img width="1920" height="1080" alt="Screenshot 2026-06-07 064624" src="https://github.com/user-attachments/assets/a9589b2b-f388-47da-951a-3f08a438f8f5" />
<img width="1920" height="1080" alt="Screenshot 2026-06-07 064642" src="https://github.com/user-attachments/assets/5488ee02-18a1-460b-ae65-8c25c2c01fc8" />
<img width="1920" height="1080" alt="Screenshot 2026-06-07 064754" src="https://github.com/user-attachments/assets/2bcd29d2-ecbb-4605-97cb-a37d3f283ee7" />

### Static Website Hosting Enabled
<img width="1921" height="1025" alt="Screenshot 2026-06-07 064210" src="https://github.com/user-attachments/assets/692b27b7-1d81-4864-8bbd-9f733a28bfa8" />
<img width="1920" height="1080" alt="Screenshot 2026-06-07 064218" src="https://github.com/user-attachments/assets/4030d11e-53b5-4553-a5f7-5450728efb0f" />
<img width="1920" height="1080" alt="Screenshot 2026-06-07 064246" src="https://github.com/user-attachments/assets/6b1cd436-8b5f-4f81-831f-01799cbbba41" />
<img width="1920" height="1080" alt="Screenshot 2026-06-07 064352" src="https://github.com/user-attachments/assets/c65dbb1e-83e3-47b2-b9dd-22a170748d70" />
<img width="1920" height="1080" alt="Screenshot 2026-06-07 064442" src="https://github.com/user-attachments/assets/54865a51-4efa-4320-ac69-cf9b3d394c8e" />
<img width="1920" height="1080" alt="Screenshot 2026-06-07 064453" src="https://github.com/user-attachments/assets/3bec1e63-9476-448c-811a-9a23e6509fa8" />

---

## What I Did

- Created an S3 bucket in AWS ap-south-1 (Mumbai)
- Disabled Block Public Access and applied a bucket policy for public read
- Enabled Static Website Hosting with index.html as the index document
- Uploaded the website file to S3
- Website is live and accessible via S3 endpoint URL

---

## Architecture
User Browser
|
v
Amazon S3 (Static Website Hosting)
ap-south-1 | Mumbai Region

---

## Services Used

| Service | Purpose |
|---|---|
| Amazon S3 | Static file storage and website hosting |
| S3 Bucket Policy | Public read access for website visitors |
| AWS IAM | Access control and permissions |

---

## Files

| File | Description |
|---|---|
| index.html | Main website page |
| bucket-policy.json | S3 bucket policy applied for public access |

---

## What I Learned

- S3 bucket creation and configuration
- Bucket policy and public access settings
- Static website hosting on AWS
- IAM permissions and least privilege concept
- AWS ap-south-1 (Mumbai) region setup

---

## About Me

**Swapnil Thik** — Network Engineer transitioning to Cloud  
AWS Certified Cloud Practitioner (2026) | Fortinet NSE3 (2025)  
[LinkedIn](https://linkedin.com/in/swapnil-thik) | 
[GitHub](https://github.com/Swapnil9067)
