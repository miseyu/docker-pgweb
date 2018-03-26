# docker-pgweb

## Usage

### Building the image:

```
docker build -t docker-pgweb --no-cache --rm=true ./
```

### Run:

```
pgweb --bind=0.0.0.0 --listen=8080
```