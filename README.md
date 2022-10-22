Polecenie do zbudowania obrazu:
```
docker build -t przemyslawbajda/lab2.v1 --ssh default .
```

Polecenie do uruchomienia kontenera:
```
docker run -d --name lab2 -p 8080:8080 przemyslawbajda/lab2.v1
```

Polecenia do zapisania obrazu w repozytorium:
```
docker commit lab2 przemyslawbajda/lab2.v1
docker push przemyslawbajda/lab2.v1
```

Linki:
https://hub.docker.com/r/przemyslawbajda/lab2.v1