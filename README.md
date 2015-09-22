Minilla docker
========================
Docker for automated test and build of [Minilla](https://metacpan.org/pod/Minilla) projects.

Is possible this used in integration servers

unit test build step
```
docker run -v $(pwd):/tmp/minilla avastsoftware/minilla minil test
```

and for make distribution build step
```
docker run -v $(pwd):/tmp/minilla avastsoftware/minilla minil dist 
(release tests are enabled)
```
(and save *.tar.gz artifacts for example)
