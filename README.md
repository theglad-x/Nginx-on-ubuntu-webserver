# Nginx Webserver on Ubuntu Instance


This project is part of my participation in the HNG Internship. The task involves deploying a website onto an AWS EC2 Ubuntu instance, configuring NGINX to serve the website, and ensuring that the website is accessible through a public IP address. The objective is to deploy static content in a cloud environment.

In this project I deployed a simple static website on AWS EC2 Ubuntu instance using NGINX as the web server. 


## Setup for the Deployment
1. Launch an EC2 Ubuntu instance on AWS.
2. Install NGINX on the EC2 instance.
3. Configure NGINX to serve the website.
4. Access the website through the public IP address of the EC2 instance.

# Launch an EC2 instance 



![Screenshot (498)](https://github.com/user-attachments/assets/bacd7c19-7b23-47a3-b9b2-a5eee8374fbe)


![Screenshot (503)](https://github.com/user-attachments/assets/b6e8b5fa-bf6b-4915-a68a-dd7dce207dbe)

![Screenshot (500)](https://github.com/user-attachments/assets/e30fc7e2-9a63-4794-bd14-5df8e6c276ea)


![Screenshot (501)](https://github.com/user-attachments/assets/9374b42c-6967-442e-8d63-144137c6fba6)

# Confirm that the instance is running

![Screenshot (502)](https://github.com/user-attachments/assets/1925e9bd-5541-45e5-ba17-c096c05a918e)

# Connect to the instance

![Screenshot (506)](https://github.com/user-attachments/assets/7fbaddd2-35e7-433c-915a-3a1c66c76f80)


# update package index
```bash
sudo apt update
```

# Install nginx
![Screenshot (509)](https://github.com/user-attachments/assets/f6be1475-a346-4321-969f-ccc25290b9c6)

# Confirm that nginx is running

![Screenshot (510)](https://github.com/user-attachments/assets/db578890-e643-479c-99db-58f5a06f91b1)

 # Access the website through the public IP address of the EC2 instance.
![Screenshot (511)](https://github.com/user-attachments/assets/d7866e90-d111-4352-a5f3-27a7282ed663)
