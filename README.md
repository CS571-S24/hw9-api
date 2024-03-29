build
```bash
docker build . -t ctnelson1997/cs571-s24-hw9-api
docker push ctnelson1997/cs571-s24-hw9-api
```

run
```bash
docker pull ctnelson1997/cs571-s24-hw9-api
docker run --name=cs571_s24_hw9_api -d --restart=always -p 58109:58109 -v /cs571/s24/hw9:/cs571 ctnelson1997/cs571-s24-hw9-api
```

run fa
```bash
docker pull ctnelson1997/cs571-s24-hw9-api
docker run --name=cs571_fa_s24_hw9_api -d --restart=always -p 59109:58109 -v /cs571_fa/s24/hw9:/cs571 ctnelson1997/cs571-s24-hw9-api
```
