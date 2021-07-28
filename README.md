# docker-cheatsheet


For Creating Image and pushing it to dockhub to the following:

1. build the image on the wanted OS (if image is build on a windows machine the image can only be used on windows machines - this is the same for arm and linux)
e.g. 
```
git clone <REPO>
cd <REPO>
```
```
docker build . -t <dockername>/<imagename>:<tag>
```
```
docker login
```
-> enter credentials of dockerhub login

```
docker push <dockername>/<imagename>:<tag>
```
