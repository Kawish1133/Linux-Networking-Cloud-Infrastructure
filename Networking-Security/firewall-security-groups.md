#  firewall-security-groups.md — Firewall & AWS Security Groups


# Firewall network traffic ko control karta hai. AWS Security Group EC2 instance ke liye virtual firewall hota hai.

    Ubuntu UFW commands:

#   Command                     	Purpose
sudo ufw status	Firewall           status
sudo ufw status verbose	          Detailed status
sudo ufw allow 22/tcp	          Allow SSH
sudo ufw allow 80/tcp    	      Allow HTTP
sudo ufw allow 443/tcp	           Allow HTTPS
sudo ufw deny 8080/tcp            Block Jenkins port
sudo ufw delete allow 80/tcp	  Remove HTTP rule
sudo ufw enable                   Enable firewall
sudo ufw disable          	       Disable firewall
