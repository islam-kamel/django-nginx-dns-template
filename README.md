<h1 style="text-align: center"> Docker images For Create django project 
with nginx server and dns locally 
</h1>

### Run
```shell 
cd ./django 
```
```shell 
python manage.py collectstatic 
```
```shell 
docker-compose build .
```
```shell 
docker-compose up 
```

```shell 
curl www.main.com 
```

**Remember to change your dns server to 127.0.0.1🧑‍💻**
