### Shell into alpine

`docker container run --rm -it alpine sh`

Mount current directory:

`docker container run --rm -it -v $(pwd):/usr/src/proj alpine sh`
