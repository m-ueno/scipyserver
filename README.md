Dockerized Notebook + SciPy Stack
=================================

Docker container for the [SciPy stack](../scipystack) and configured IPython notebook server.

## Quickstart

Assuming you have docker installed, run this to start up a notebook server on https://localhost.

```
docker run -d -v `pwd`:/notebooks -p 443:8888 -e "PASSWORD=password" mueno/scipyserver
```

