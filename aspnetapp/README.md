# docker

https://docs.docker.com/engine/examples/dotnetcore/#create-a-dockerfile-for-an-aspnet-core-application

Navigate to API project folder in DEV command prompt then:
$ docker build -t aspnetapp .
$ docker run -d -p 9090:80 --name myapp aspnetapp

Open browser to:
http://localhost:9090/api/values