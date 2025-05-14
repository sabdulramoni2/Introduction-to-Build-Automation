# Introduction to Build Automation

## **Project Overview**
This project shows the use of jenkins as build automation and continous integration tools.
---

## **Features**
### Install Jenkins
- Created a Server (Droplet) on DigitalOcean
- Configured Firewall Rules to open port 22 and port 8080 for our new server
- Installed Docker on DigitalOcean Droplet
- Started Jenkins Docker container with named volume
- Initialized Jenkins

  ### Install Build Tools
  - Configured Plugin for Maven
  - Installed npm and node in Jenkins container
  - Useful Links:
      - Node Installation for Linux distributions: https://github.com/nodesource/distributions
      - Jenkins Plugins: https://plugins.jenkins.io/
  ### Jenkins Basics Demo
  - Configured Git Repository to checkout the code from
  - Configured Job to run tests and build Java Application
