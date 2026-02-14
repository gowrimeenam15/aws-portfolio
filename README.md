# 🚀 AWS Cloud Practitioner Portfolio

This project is a professional cloud portfolio hosted on **Amazon S3** and deployed using a fully automated **CI/CD pipeline** via **GitHub Actions**.

## 🌐 Live Demo
You can view the live site here: 
[http://gowri-cloud-portfolio-2026.s3-website.ap-south-1.amazonaws.com](http://gowri-cloud-portfolio-2026.s3-website.ap-south-1.amazonaws.com)

## 🛠️ Tech Stack
* **Cloud:** Amazon Web Services (S3, IAM)
* **DevOps:** GitHub Actions (CI/CD)
* **Frontend:** HTML5, CSS3

## 🏗️ Architecture
1. **Source Control:** Code is managed in this GitHub repository.
2. **Automation:** A GitHub Action workflow (`main.yml`) triggers on every push to the `main` branch.
3. **Deployment:** The AWS CLI syncs the repository files to an S3 bucket configured for static website hosting.
4. **Security:** AWS credentials are stored securely in GitHub Secrets.

## 🚀 How to Deploy Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/gowrimeenam15/aws-portfolio.git](https://github.com/gowrimeenam15/aws-portfolio.git)