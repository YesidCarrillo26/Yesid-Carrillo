# *Yesid Santiago Carrillo Almeida*
### **Full stack Developer**
**University** <https://www.escuelaing.edu.co/es/estudiantes>

About me:
- 🌱 I’m currently learning Spring, API REST, MongoDB, Docker and AWS
- 💬 Ask me about Java, Python, Sql, HTML, CSS
- 📫 How to reach me yesid.carrillo@mail.escuelaing.edu.co

![Github Stats](https://github-readme-stats.vercel.app/api?username=YesidCarrillo26&show_icons=true&count_private=true&theme=algolia)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=YesidCarrillo26)](https://github.com/RichardUG/github-readme-stats) 

 ## Comandos maven

```
maven package
```

```
mvn archetype:generate -DgroupId=edu.escuelaing.arep -DartifactId=app -DarchetypeArtifactId=mavenarchetype-quickstart -DinteractiveMode=false
```

```
mvn exec:java -Dexec.mainClass="edu.escuelaing.arep.HttpServer"
```

```
mvn clean install
```

```
heroku local web
```

```
heroku create
```

```
git push heroku main
```
heroku open

```
heroku git:remote -a <nombre>
```
```
echo "Docker File" > DockerFile
```

## Comandos Docker

#### Construir imagen
```
docker build --tag dockersparkprimer .
```
#### Mapear puertos
```
docker run -d -p 34002:6000 --name firstdockercontainer3 dockersparkprimer
```
#### Union instancias contenedores
```
docker-compose up -d
```
#### Referencia local docker imagen
```
docker tag dockersparkprimer dnielben/firstsprkwebapprepo
```
#### Push al repo en docker (antes hacer login)
```
docker push dnielben/firstsprkwebapprepo:latest
```
#### Cambiar nombre repositorio (opcional)
```
docker tag primer-docker-spark:latest dnielben/primersparkweb:latest
```
## AWS
```
sudo yum update -y
```
```
sudo yum install docker
```

```
sudo service docker start
```
```
sudo usermod -a -G docker ec2-user
```
```
docker run -d -p 42000:6000 --name firstdockerimageaws dnielben/firstsprkwebapprepo
```
