## My PROJECT 2: LEMP STACK IMPLEMENTATION

### STEP 1 – INSTALLING THE NGINX WEB SERVER

#### In order to display web pages to our site visitors, i'm going to employ Nginx, a high-performance web server. I’ll use the apt package manager to install this package.

`sudo apt update`

![Apt Update](images/aptupdate.png)

#### I install Nginx using the command below
`sudo apt install nginx`

![nginx update](images/nginx.png)

#### To verify that nginx was successfully installed and is running as a service in Ubuntu,  I run:

`sudo systemctl status nginx`

![nginx status](images/status.png)

#### My server is running and I can access it locally and from the Internet (Source 0.0.0.0/0 means ‘from any IP address’). First, let us try to check how we can access it locally in our Ubuntu shell, run:

`curl http://127.0.0.1:80`

![local running](images/local.png)


#### running my server on the web using public DNS

`ec2-18-206-173-4.compute-1.amazonaws.com`

![web running](images/web.png)

## STEP 2 — INSTALLING MYSQL









