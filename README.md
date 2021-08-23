# docker-ntttcp
ntttcp container

```bash
# reciever
docker run ueqt/ntttcp:linux -p 5000-5500:5000-5500
# sender
docker exec <dockerid> -it --/bin/bash
# ntttcp -s<target ip> -t 300
```
