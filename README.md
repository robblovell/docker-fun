docker build --tag stage-1 ./stage-1
docker build --tag stage-2 ./stage-2

docker run stage-1
docker run stage-2

