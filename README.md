# docker-phoebus-alarmd

Dockerfile for Phoebus

## Ubuntu

On Mac run it as:
```bash
HOSTNAME=mymachine # or 192.168.1.XXX
XAUTH_PATH=/Users/user/.Xauthority
docker run -it --rm -e DISPLAY=${HOSTNAME}:0  -v ${XAUTH_PATH}:/tmp/.Xauthority -e XAUTHORITY=/tmp/.Xauthority epics-phoebus
```
