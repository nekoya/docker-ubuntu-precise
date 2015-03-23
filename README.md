# Docker base image of Ubuntu 12.04 (precise)

## features

- set `DEBIAN_FRONTEND noninteractive`
- set TimeZone as JST (+09:00)
- use `fpt.jaist.ac.jp` APT mirror

## usage

```
FROM nekoya/precise
RUN apt-get update && apt-get install -y \
    foo \
    bar
```
