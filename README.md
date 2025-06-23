# Automated Apache Deployment on EC2

Just wrapped up a successful deployment: Running an Apache webserver on an EC2 instance — fully automated using EC2 User Data.

This repo showcases how to spin up a web-ready Apache server on AWS EC2 using a lightweight, zero-touch setup script. No manual configuration needed — simply launch and deploy!

---

## What This Setup Offers

- Zero manual setup  
- Webserver live on launch  
- Easily replicable across environments  
- Scalable and cost-effective  

It’s amazing how powerful a few lines of Bash can be when paired with AWS! Perfect for quickly deploying:

- Minimal web stacks  
- Prototypes or demos  
- Internal tools and dashboards  

---

## Tech Stack

- Amazon EC2  
- Amazon Linux 2  
- Apache HTTP Server  
- EC2 User Data (Bash scripting)  

---

## How to Use

1. Launch an EC2 Instance (Amazon Linux 2).
   ![Screenshot 2025-06-11 121417](https://github.com/user-attachments/assets/fe4a4ad8-0a4b-41df-b11e-e5a7356bb886)

---

2. In the **Advanced Details** section, paste the contents of `user-data.sh` into the **User Data** field.
   ![Screenshot 2025-06-11 121204](https://github.com/user-attachments/assets/621c3b41-c386-4ad6-a643-9169dac250b6)

---

3. Ensure your security group allows inbound traffic on port **80 (HTTP)**.
   ![Screenshot 2025-06-11 121659](https://github.com/user-attachments/assets/36a24be6-e83c-4fca-9323-072c47a3e33c)

---

4. Launch the instance & Visit the instance’s public IP in your browser — your Apache webserver should be live!

   ![Screenshot 2025-06-11 121527](https://github.com/user-attachments/assets/00bc9ab6-9187-4c34-9a7c-fda3196a5b89)


---

## Perfect for:

  - Prototypes and internal tools
  - Lightweight production services
  - Infrastructure automation practice




