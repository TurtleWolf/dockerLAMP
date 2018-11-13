# Docker: DevOp LAMP
> from development to production workflow

[Docker: Dev to Production playlist](https://www.youtube.com/playlist?list=PLETG2T1KvniqIEU_xkadLpugT8nhmNxSR "Easy Docker Dev to Production Setup for Small Projects")   
[How to create a docker-based LAMP stack using docker-compose on Ubuntu 18.04 Bionic Beaver Linux](https://linuxconfig.org/how-to-create-a-docker-based-lamp-stack-using-docker-compose-on-ubuntu-18-04-bionic-beaver-linux "Following this tutorial you will be able to create a LAMP environment using the Docker technology.")  
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")  

## Quick Start  
```bash
# assuming NodeJS & Docker are installed locally  
npm install  
docker-compose up -d  
# -d : to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build
```

## Production  
```bash

# Run in Docker
docker-compose -f docker-compose-production.yml up -d --build
```
