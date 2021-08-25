## Run

`docker-compose up`

## Install sonar scanner for yout plataform and run

```sonar-scanner \
     -Dsonar.projectKey=core_business_local\
     -Dsonar.sources=.\
     -Dsonar.host.url=http://localhost:9000\
     -Dsonar.login=YOUR_KEY
```

## TODO

Copy plugin on container build `docker cp ./plugins/sonar-flutter-plugin-0.3.2.jar sonarqube_sonarqube_1:/opt/sonarqube/extensions`
