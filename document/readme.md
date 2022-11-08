이미지 <br>
docker pull hyunjun1325/ubuntu_vnc:latest

RUN COMMAND<br>
```sh
docker run -p <host_port>:5900 \ 
           -e RESOLUTION=1920x1080 \
              hyunjun1325/ubuntu_vnc
```




