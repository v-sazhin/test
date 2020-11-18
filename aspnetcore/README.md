# IO.Swagger - ASP.NET Core 2.0 Server

Все формы передаются в формате multipart/form-data, ответы от сервера приходят в виде json.

## Run

Linux/OS X:

```
sh build.sh
```

Windows:

```
build.bat
```

## Run in Docker

```
cd src/IO.Swagger
docker build -t io.swagger .
docker run -p 5000:5000 io.swagger
```
