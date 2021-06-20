#use existing base image
FROM alpine


#run commands to install additional programs
RUN apk add --update redis 
RUN apk add --update gcc


#write a command to tell the image what to do once the container is started 
CMD ["redis-server"]