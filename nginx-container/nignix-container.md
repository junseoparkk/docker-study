## nginx 컨테이너 생성

### 1) index.html 생성

### 2) docker run

```bash
$ docker run -d --rm \
  --name nginx-container \
  -p 50000:80 \
  -v $(pwd)/index.html:/usr/share/nginx/html/index.html \
  nginx
```
