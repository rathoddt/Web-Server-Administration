Installation   
`sudo apt update`  
`sudo apt install nginx`  

If nginx is not serving traffic on public IP check firewall  
`ufw app list`  
`sudo ufw allow 'Nginx HTTP'`  
`ufw status`  
`systemctl status nginx`  