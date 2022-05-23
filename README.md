Readme file for Docker-Project 


1) Used below given aws account and created linux ec2 machine
   Email : dhrumil.m@addwebsolution.in
   password: Addweb@123
   region: ap-south-1

2) Created docker-compose.yml file which includes below services
    :nginx (port 80 and 443 
    :MySQL (pre-defined root user password)
    :PHP   (has all php extensions)
    :redis-server
3) Configured monitoring tool on to the server and created "container monitoring dashboard" (used prometheus and grafana)
   Prometheus link : http://3.110.221.105:9090/
   Grafana link : http://3.110.221.105:3000/  (user id : admin, password: admin || Dashboard Docker container starred in General folder)

4) Set an alarm through which you get email notification on any event trigger on docker container(not attempted due to time constraint)
5) Deployed Php website with the use of docker (Use nginx, mysql, php services) created in step 2.
6) Created nginx conf, and for domain, used nip.io domain.
7) Configured ssl for the domain(used self signed certificate) 
8) Site will redirect forcefully from http to https

   php website link : 3.110.221.105.nip.io

9) Provided ssh access key in the attachment public ip 3.110.221.105 of ec2 linux machine on which everything is hosted

10) Github repo link for code: https://github.com/SyedMohdSaif/Docker-Project.git

