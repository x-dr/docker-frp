### build
```shell
docker build -t frps .
```

### use
```shell
docker run -itd --net=host  --name frps -v $PWD/frps/config:/frps/config -v $PWD/frps/logs:/frps/logs gindex/frps
```