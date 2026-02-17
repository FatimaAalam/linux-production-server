# Linux Nginx Server Deployment

This project demonstrates setting up a Linux server on AWS EC2, installing Nginx, and deploying a simple HTML page.

---

## Steps Performed

### 1. Create and Connect to EC2 Instance
- Created an EC2 instance on AWS.  
- Allowed SSH, HTTP (80), and HTTPS (443) traffic.  
- Connected to the instance using SSH.

### 2. Update System and Install Nginx
```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl enable nginx
sudo systemctl start nginx
```
### 3. Verify nginx service
```
systemctl status nginx
```
### 4. Deploy HTML Page
- Navigate to `/var/www/html` directory:
```
cd /var/www/html
```
- Create an `index.html` file.
- Open your EC2 public IP in the browser. The HTML page should load.

