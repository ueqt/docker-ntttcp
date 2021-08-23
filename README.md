# docker-ntttcp
ntttcp container

```bash
# reciever
docker run -p 5000-5200:5000-5200 ueqt/ntttcp:linux
# sender
docker exec <dockerid> -it --/bin/bash
# ntttcp -s<target ip> -t 300
```
