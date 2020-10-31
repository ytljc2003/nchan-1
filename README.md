# nchan.io

Nchan Publish/Subscribe server (Pub/Sub). 
Original documentation for server on: https://nchan.io/

**Note**: All paths related to root of this repository

## Build

### Build Locally:

```bash
cd local
./build.sh
```

### Push to Docker registry

Login to Docker registry:

```bash
docker login -u "USERNAME" -p "PASSWORD or TOKEN"
```

Push to Docker registry:

```bash
docker push FULL_NAME_OF_THE_IMAGE
```

## Run

### Locally:
Go to `local` dir
```bash
cd local
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

## Demo client:

Install globally:

```bash
npm i -g http-server
cd html
http-server -p 9000
```

Go to:
http://127.0.0.1:9000 