Ziel dieses Projekts ist es, ein Gradle-Projekt "from scratch" zu erzeugen, das ohne weitere Hilfsmittel in Heroku
hochgeladen werden kann.

# Bedienungsanleitung

1. https://start.spring.io

Group: com.example

Artifact: __restservice__

Dependencies: _Spring Web_ (spring-boot-starter-web)

Java-Version: _11_

2. Zip-Paket extrahieren unter M:\Projects
  
  Danach _M:\Projects\restservice_ umbenennen in _M:\Projects\gradle.restservice_

3. Restservice implementieren: https://spring.io/guides/gs/rest-service/

4. git init

5. git add ...

6. git commit -m "initial commit"

7. git branch -M master

8. git e add origin https://github.com/chris125964/gradle.restservice.git

9. git push -u origin master

10. heroku apps:create --region=eu github-restservice

11. git push heroku master