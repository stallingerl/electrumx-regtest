
ElectrumX - Regtest Server
===============================================


Documentation
=============

See <a href="https://electrumx.readthedocs.io/" target="_blank">readthedocs.</a>

To start an ElectrumX in Regtest run: 

```docker-compose up``` 

To enter an interactive shell session on the running containers:

```docker exec -it regtest bash```
```docker exec -it electrumx bash```

This will start a docker container with doichain/node-only running a daemon in regtest and a container with ElectrumX.


Images
=============

ElectrumX Regtest:

Docker:
<a href="https://hub.docker.com/repository/docker/stallingerl/electrumx-doi" target="_blank">electrumx-doi</a>

Github:
<a href="https://github.com/Doichain/electrumx" target="_blank">doichain/electrumx</a>

Doichain Daemon node-only:

Docker:
<a href="https://hub.docker.com/r/doichain/node-only" target="_blank">node-only</a>
    

Github:
<a href="https://github.com/Doichain/docker/tree/master/node-only" target="_blank">doichain/node-only</a>
    

