# Lab3_zd
 
 Polecenie użyte do zbudowania obrazu:
 -
 ``` docker build --ssh default="C:\Users\kamsi\.ssh\id_rsa" -f Dockerfile -t kamsinox/lab2.v1 . ```
 
 Polecenie użyte do uruchomienia kontenera:
 -
 ``` docker run -d --name lab2-cont -p 8080:8080 kamsinox/lab2.v1 ```

Zapis obrazu do DockerHuba
-
Aby przesłać obraz do repozytorium na DockerHubie, użyłem aplikacji Docker Desktop. <br>
Po zalogowaniu się w aplikacji, wybrałem obraz, kliknąłem w 3 kropki i wcisnąłem przycisk "Push to hub".
![obraz](https://user-images.githubusercontent.com/92575198/199552464-feec5dd9-5920-4259-b435-41b51b2a98e9.png)

Link do repozytorium: https://hub.docker.com/repository/docker/kamsinox/lab2.v1
