# Online-video-streaming-website
Youtube like online video streaming website hosted on AWS EC2 instance

Deployment:
1. Launch a EC2 instance of any linux provider with public IP adress attached
2. Connect to the instance CLI run update and uprage commands
3. Download httpd daemon on the machine and update the index.html file with the provided html code
4. Set inbound and outbound rules to allow traffic on the instance
5. Using Route53 assign a domain name to the public IP of the instance
6. Then the authorized traffic can access the website
7. We can also add and delete videos from the website by making few changes in the code
