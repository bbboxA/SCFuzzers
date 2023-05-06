# SmartcontractFuzzers
Are existing fuzzers good enough for auditing smart contract? (Experience Paper)


# How to load each Dockerfile:

1 import the docker image
```
docker import tomConfuzzDemo.tar kaifaconfuzz
```
2. run docker image
```
docker run -idt -p 5180:80 kaifaconfuzz:latest /bin/bash
```
