# PROJECT 1: PROVISIONING A SECURE AND SCALABLE SERVER ON AWS EC2
## To execute this project:
1.	Launch a new EC2 instance using Ubuntu Server AMI

![img](img/Launch%20EC2%20Instance.png)
![img](img/Launch%20EC2%20Instance%202.png)


2.	Update Package Index by runnig the command: 
    sudo apt update

![img](img/Update%20Package%20Index.png)

3.  Install Apache2 by running the command:
    sudo apt install apache2 -y

![img](img/Install%20Apache2.png)

4.  Start Apache 2 by running the command:
    sudo systemctl start apache2
![img](img/Start%20Apache2.png)

5.  Enable Apache2 to Start on Boot by running the command
    sudo systemctl enable apache2
![img](img/Enable%20apache2.png)

6.  Check status of firewall by running:
    sudo ufw status

7. Allow Apache through the firewall by running:
sudo ufw allow 'Apache'

8.  Reload firewall by running the command:
sudo ufw reload

9.  Verify Apache is running by running the command:
sudo systemctl status apache2

![img](img/Apache%20-%20Active.png)

10. Get the server IP by running the command:
curl ifconfig.me

![img](img/Get%20server%20IP%20address.png)

11. Open a browser and go to http://3.86.212.252 to view Apache2 Ubuntu Default Page
![img](img/Ubuntu%20Default%20Page.png)


12. Create an html file and css file to create a basic static website

![img](img/html%20code.png))
![img](img/css%20code.png)



