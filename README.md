# Rent4U Website - Hosting Using AWS EC2

This repository contains the source code and project files for **Rent4U**, a car rental service platform hosted on **Amazon EC2**. The website allows users to browse, select, and book cars online with ease.

## 🚀 Project Overview

Hosting the Rent4U website on AWS EC2 ensures scalability, availability, and cost-effective deployment in the cloud environment. The setup leverages EC2 with Elastic IP, secure SSH access, and optimized web servers to provide a reliable and secure web presence.

## ✨ Key Features

- **Simple Deployment:** Supports deployments using SCP, GitHub Actions, or AWS CodeDeploy.
- **High Availability:** EC2 instances deployed across multiple Availability Zones.
- **Performance Optimization:** Uses Apache/NGINX with compression (gzip/Brotli) for faster loading.
- **Security:** HTTPS with SSL/TLS certificates, Security Groups, and SSH key-based access.
- **Backup & Recovery:** EBS Snapshots and AMI creation for disaster recovery.

## 🛠️ Technologies Used

### 📌 Frontend
- HTML
- CSS *(optionally with Bootstrap or Tailwind)*
- JavaScript *(vanilla or jQuery)*
- Images and Assets

### 📌 Cloud & Infrastructure
- **Amazon EC2** – Main hosting environment
- **Elastic IP** – Static, consistent public IP address
- **Security Groups** – Control inbound/outbound traffic
- **SSH Key Pairs** – Secure server access
- **EBS (Elastic Block Store)** – Persistent file storage
- **Amazon Route 53** – Domain Name Service (DNS)
- *(Optional)* CloudFront CDN for performance boost

  
## 📂 Website Structure

- `index.html` → Home Page
- `search.html` → Search Page
- `about.html` → About Page
- `bestcars.html` → Our Best Cars Page
- `contact.html` → Contact Page
- `assets/` → Images, logos, stylesheets, etc.


## ⚙️ Deployment Steps (Summary)

1. Launch EC2 Instance → Configure Security Groups (allow HTTP/HTTPS/SSH)
2. Install Apache or NGINX
3. Upload project files using `scp` or `curl`
4. Configure SSL (optional for HTTPS)
5. Map your domain with Route 53 to the Elastic IP
6. Access the website via browser using domain or public IP


## ✅ Outcome & Benefits

- **High Reliability:** Global access with minimal downtime
- **Performance:** Fast load times via server optimization
- **Security:** Full HTTPS support for encrypted communication
- **Scalability:** Supports future growth using Auto Scaling Groups and Load Balancers
- **Disaster Recovery:** Regular backups with AMI and EBS snapshots


## 📧 Contact

For feedback or contributions, feel free to create issues or pull requests.

