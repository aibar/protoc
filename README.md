    docker run --rm -it -v $PWD:/mnt aibar/protoc -I=proto --java_out=src proto/*.proto
