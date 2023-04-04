# Python-based-ecommerce-site-on-ubuntu-server-nginx-gunicorn

<<<<<<< HEAD
Prereq!!
Ubuntu, Nginx, Gunicorn, Django, PostgreSQL
=======
***** Prereqs*****
- Ubuntu
- Nginx
- Gunicorn
- Django
- PostgreSQL

*** Steps***
Note: for this web hosting,  I used ubuntu 20 in aws. 

- clone this repository into your server after installing git 

**Using bash script to install and deploy the app**
run the below commands
1. chmod +x eccommerce-1/setup.sh
2. chmod +x eccomerce-1/gunicorn.sh
3. ./eccommerce-1/setup.sh
Note: You will need to modify the gunicorn.sh file and replace your ip address on the server_name to your own public ip address. use the command below to do this

 vim ~/eccommerce/gunicorn.sh

 After modifying the ip address run the below command: 

 ./eccommerce/gunicorn.sh

 Note: remember to use port 80 while accessing your website using your public ip address



>>>>>>> stage
