# Docker and Docker Compose Install Scripts

This repo provides an easy method for installing Docker and Docker-Compose on Linux Systems.

# Supported Operating Systems
* CentOS 7+
* Ubuntu 18.04+
* Debian (Coming Soon)

# Software Installed
* Docker and all supporting software
* Docker-Compose
* Haveged for additional entropy on VMs

# Install instructions
1. Copy the appropriate file for your OS to the desired location on your system
2. Run `chmod +x docker-install-%youros%.sh`
3. Run `./docker-install-%youros%.sh`

# Install Verification
1. Run `docker -v` to verify the version of Docker installed
2. Run `docker-compose -v` to verify the version of Docker-Compose installed

# Additional Information 
* Docker: https://docs.docker.com/engine/install/
* Docker-Compose: https://docs.docker.com/compose/install/
* Haveged: http://issihosts.com/haveged/