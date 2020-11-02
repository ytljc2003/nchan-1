# nchan.io

Nchan Publish/Subscribe server (Pub/Sub). 

**Note**: 
#### local/master: run with redis server
#### local/slave:  run without redis server, need change nginx.nchan.default.conf to set up redis server
#### html:         copy to nginx html path, test subscribe


## Build

### Build Locally:

```bash
cd local/master
./build.sh

or

cd local/slave
./build.sh
```

## Run

### Locally:
Go to `local` dir
```bash
cd local/master

or

cd local/slave
```
Run:
```bash
docker-compose up
```
Stop:
```bash
Ctrl+C
```

Remove:
```bash
docker-compose down
```