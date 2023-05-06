# Evaluting Smart Contract Fuzzers
Are We There Yet? Unraveling the State-of-the-ArtSmart Contract Fuzzers (Experience Paper)


# How to load each Dockerfile:

1 import the docker image
```
docker import xxxxxDemo.tar testimage
```
2. run docker image
```
docker run -idt -p 5180:80 testimage:latest /bin/bash
```

# ContractFuzzer
```
docker run ......
cd /ContractFuzzer
sh run.sh
```


# RLF
```
docker run ......
cd /go/src/rlf/

```
