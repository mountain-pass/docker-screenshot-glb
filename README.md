# docker-screenshot-glb


## Reference:

- https://github.com/Shopify/screenshot-glb

## Build / Pull:

```sh
docker build --tag mountainpass/screenshot-glb .
# or
docker pull mountainpass/screenshot-glb
```

## Usage:

```sh
docker run -it --rm -v "`pwd`:`pwd`" -w "`pwd`" mountainpass/screenshot-glb screenshot-glb --help
```