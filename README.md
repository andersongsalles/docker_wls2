# Comandos para iniciar o docker com wsl2 e sonarqube

```
sudo service docker start

docker run -d --name sonarqube -e SONAR_ES_BOOTSTRAP_CHECKS_DISABLE=true -p 9000:9000 sonarqube:latest

sonar-scanner.bat -D"sonar.login=admin" -D"sonar.password=1234"

6c0c3d17b1df582269909a5c6cd913d4302abe48
```

