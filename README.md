# 🌐 Cloud-Based Personal Portfolio on AWS EC2

This is a secure, cloud-hosted personal portfolio I built using HTML, CSS, and JavaScript, and deployed on an AWS EC2 instance using RTC (Repository-Themed Cloud) and CSRT (Cloud Secure Resource Transfer Architecture).

## 🧰 Tech Stack
- Frontend: HTML, CSS, JavaScript
- Cloud Deployment: AWS EC2
- Tools Used: PuTTY, WinSCP, SSH
- Security Model: CSRT + RTC Architecture

## 🔐 Features
- Secure deployment using PuTTY and WinSCP
- SSH access to EC2 using private key
- HTTPS access through EC2 public IP (`https://<IP>/portfolio`)
- Resume download button
- Secure file transfer and deployment

## 🎥 Deployment Video
I’ve included a screen recording of the full deployment and live website access.  
👉 **[Click to Watch the Video](./screen-record.mp4)**

*(Note: The EC2 instance is no longer live due to billing. Please refer to the video for the working demo.)*

## 📄 Resume
A downloadable resume is included in the project.  
📎 [Download Resume](./resume.pdf)

## 🗂️ Project Structure
portfolio/
├── index.html
├── style.css
├── script.js
├── resume.pdf
├── screen-record.mp4portfolio/


## 📦 How It Was Deployed (Summary)
1. Launched EC2 (Ubuntu) in public subnet with HTTPS setup
2. Transferred project files using WinSCP
3. Configured Apache/Nginx to serve `/portfolio`
4. Secured access using PuTTY SSH and IAM
5. Verified live site on `https://<EC2-IP>/portfolio`

---

## 📘 Note:
The EC2 instance was deleted to avoid ongoing AWS charges.  
All setup steps, functionality, and result can be seen in the video.

---

