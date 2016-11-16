# Apiman
Docker version of Apiman

This is an example of [apiman](http://www.apiman.io/latest/download.html).

# Usage

Try to execute 
```
docker run -d -p 8080:8080 celsoagra/apiman
```
NOTE: This image provides a standalone wildfly profile for apiman. Please, don't change the port of local host. When the port is changed (such as 8081:8080), an error occurs. This problem can be viewed in the [issue APIMAN-242](https://issues.jboss.org/browse/APIMAN-242).

# Profile
```
Login: admin
Password: admin123!
```

# Urls
```
Wildfly 10 -> localhost:8080
Apiman -> localhost:8080/apimanui
Keycloak -> localhost:8080/auth
```

# Docker
The source is available on [Docker Hub](https://hub.docker.com/r/celsoagra/apiman/).
