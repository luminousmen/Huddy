Huddy
=====

Huddy = Hugo + Caddy docker container


###### Installation

```bash
    docker pull luminousmen/huddy:latest
    docker run -d -p 80:80 luminousmen/huddy caddy
```


###### Build site

To actually generate site and run it in container uncomment last two lines in `Dockerfile` then:

```bash
    docker build -t <tag> .
    docker run -d -p 80:80 <tag> caddy
```
