# use and existing docker image as a base
FROM alpine

# download and isntall a dpedency
RUN apk add --update gcc
RUN apk add --update redis

# tell image what to do when it starts as a container
CMD [ "redis-server" ]
