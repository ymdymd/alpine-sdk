# alpine-sdk
alpine-sdk dockerfile

## build container
```sh
docker build -t ymdymd/alpine-sdk .
```

## run container
```sh
docker run -it ymdymd/alpine-sdk
```

## run container with binding current directory
```sh
docker run -it -v $(pwd):/home/alpine-sdk/$(basename $(pwd)) --rm ymdymd/alpine-sdk
```
