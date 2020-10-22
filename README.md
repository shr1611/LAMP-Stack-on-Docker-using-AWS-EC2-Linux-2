# LAMP-Stack-on-Docker-using-AWS-EC2-Linux-2
Docker Image for LAMPStack is installed on Ubuntu 14.04, AWS EC2 Linux 2 Instance.

Dockerhub repository : https://hub.docker.com/repository/docker/shrutijb/lampstack_on_aws_ec2

------------------------------------------------------------------------

Problem statement

» Create a docker image for LAMPS web server – use the EC2 environment created in HW1
Install docker pre-requisites and docker engine on EC2 instance.
Launch a container using docker run to ensure everything works.
Install LAMP stack inside an Ubuntu 14.04 container and ensure everything works.
Upload at docker hub, create your username at docker hub and upload there. Make sure the image is public usable.

-------

» Steps followed (in brief)

Launched an AWS Linux 2 AMI Ubuntu machine as an AWS EC2 instance and connected via SSH
Created a Dockerfile with the LAMP server installation commands.
Built a docker image using the Dockerfile and ran the container on ec2 ubuntu 14.04
Installed the LAMPstack inside the docker container.
Pushed the image from ec2 instance to dockerhub
