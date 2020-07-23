# continuous-integration-delivery-deployment
Step by step what continuous integration, delivery and deployment are.


## Después de la instalación
1) Ejecutar 
```
docker run -p 8080:8080 jenkins/jenkins:lts
```
2)
````
docker exec <dockerId> cat /var/jenkins_home/secrets/initialAdminPassword
