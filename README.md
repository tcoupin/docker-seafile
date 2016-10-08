# docker-seafile
Data and Dockerfile to build seafile based on debian or raspbian. Ready to go !

```
docker run -p 8000:8000 -p 8082:8082 tcoupin/seafile-sqlite
```

See at docker-compose for mount volume for data and conf.

Default user : foo@bar.com, password foobar

Docker images :
- https://hub.docker.com/r/tcoupin/seafile-sqlite/
- https://hub.docker.com/r/tcoupin/rpi-seafile-sqlite/
