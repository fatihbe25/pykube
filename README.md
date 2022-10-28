# a kubernetes cluster implementation with n-instances of docker images that runs python flask web server.


## ingredients: 
  * Dockerfile --> python layer + copy flask files + pip instal flask + run 
  * requirements --> Flask 
 
```bash

docker build -t fatihbe25/pykube .
 
docker run -d fatihbe25/pykube -p 8080:8080  
  
```
 
 test:
 https://localhost:8080 
 
```bash

 docker push fatihbe25/pykube

```
