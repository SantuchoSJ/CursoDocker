# Use an existing docker  image as a base
FROM alpine

# Download and install a dependency
RUN apk add --update redis

##Las nuevas instrucciones, desde esa para abajo, no puede usar el cache

# Tell the image what to do when it starts as a container
CMD ["redis-server"]



#docker build -t user/name:version