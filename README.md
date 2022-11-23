# ASFclaim
Claims games posted by https://www.reddit.com/user/ASFinfo

All games claimed: https://gist.github.com/C4illin/e8c5cf365d816f2640242bf01d8d3675

## Install
1. enable IPC in ASF (https://github.com/JustArchiNET/ArchiSteamFarm/wiki/IPC)
2. install node.js (v16 or later)
3. `git clone https://github.com/C4illin/ASFclaim.git && cd ASFclaim`
4. `npm install`
5. `node .`



### Using docker?

```yml
# docker-compose.yml

services:
  asfclaim:
    image: ghcr.io/c4illin/asfclaim:master
    container_name: asfclaim
    environment:
      - ASF_PORT=1242
      - ASF_HOST=localhost
      - ASF_PASSWORD=hunter2
```