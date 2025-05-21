# hosting-static-website
Static Website Hosting on AWS S3 + CloudFront + Route 53
# Static Website Hosting on AWS S3

This project demonstrates how to host a static HTML/CSS website using AWS S3, with optional CloudFront and Route 53 for CDN and domain support.

## 🧰 Tools & Services Used
- AWS S3 (static hosting)
- AWS CloudFront (CDN)
- AWS Route 53 (optional domain setup)
- Bash script for deployment
- GitHub for version control

## 🗂 Folder Structure
- /website → HTML/CSS files
- /scripts → Deployment automation script
- /cloudformation → Infrastructure as code template

## 🧪 How to Use
1. Clone this repo
2. Modify website content in `website/`
3. Run `scripts/deploy.sh` to upload to S3
4. Access your website via S3 public URL

## 🌍 Live Demo
[Link to your S3 hosted site]

## 📸 Screenshots
(Include images showing AWS S3 bucket, URL, etc.)

## 📌 Future Improvements
- Add HTTPS via CloudFront
- Add custom domain via Route 53
