# Evaluting Smart Contract Fuzzers
Are We There Yet? Unraveling the State-of-the-ArtSmart Contract Fuzzers (Experience Paper)


# How to load each Dockerfile:

1 import the docker image
```
docker import xxxxxDemo.tar testimage
```
2. start docker image
```
docker run -idt -p 5180:80 testimage:latest /bin/bash
```
3. run docker image
```
docker exec -it container_ID_obatined_in_step_2  /bin/bash
```

# ContractFuzzer
```
docker run ......
cd /ContractFuzzer
sh run.sh --contracts_dir contract_folder
```
The covered instructions can be found at file: /tracelog.log


# ILF
```
cd /go/src/ilf
sh ilfTestDepth.sh
```
The log file can be found at /go/src/ilf/log/


# RLF
```
docker run ......
cd /go/src/rlf/

```
