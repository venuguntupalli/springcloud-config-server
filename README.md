# springcloud-config-server

POC implementation of distributing configurations and using them in the application. POC is based on 'Spring cloud configserver with git as backend' 

This repository has following projects

1) <b> discovery-server</b>
 </br> Spring boot Eureka Server act as service registry 
 
2)  <b>config-server</b>
</br> Spring boot config server to support for externalized configuration in a distributed system.

3)  <b>config-client-app</b>
 </br> Spring boot config server client app that reads configurations from config-server. It discovers config-server through discovery-server

It has dependency on another git reposiroty of configurations

# Process for setting up developement environment

git clone https://github.com/venuguntupalli/scf-config-repository.git

git clone https://github.com/venuguntupalli/springcloud-config-server.git

cd springcloud-config-server <br/>

in mac/linux os run below command <br/>
./gradlew <br/>
./gradlew clean build <br/>

In windows os run below command <br/>
gradlew <br/>
gradlew clean build <br/>

import projects into your favorite IDE <br/>

Here is the order of running spring boot applications <br/>
<b> discovery-server</b> <br/>
<b>config-server</b> <br/>
<b>config-client-app</b> <br/>


