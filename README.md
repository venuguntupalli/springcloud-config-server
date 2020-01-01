# springcloud-config-server

POC implementation of distrubuting configurations and using them in the application. POC is based on 'Spring cloud configserver with git as backend' 

This repository has following projects

1) discovery-server
 Spring boot Eureka Server act as service registry 
 
2) config-server
Spring boot config server to support for externalized configuration in a distributed system.

3) config-client-app
  Spring boot config server client app that reads configurations from config-server. It discovers config-server through discovery-server


