# Base Image 
FROM ubuntu:16.04

# Owner of the Image
MAINTAINER Amit Vashist <amitvashist7@outlook.com>

# Update the APT Repo
RUN apt-get update 

# Install Apache Packages 
RUN apt-get install apache2 -y

# Deploy Custom Web Page
COPY index.html /var/www/html/index.html 

# Expose Port
EXPOSE 80 
EXPOSE 3306 

# Run Apache Server 
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"] 
