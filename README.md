# Docker environment for build OpenJDK8 on Linux

##### Build image

```bash
docker build -t "env:0.1" .
```

##### And then run

```bash
docker run -it <image_id> 
cd /home/OpenJDK/
bash ./configure
make all
```
