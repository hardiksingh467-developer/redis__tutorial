# Redis
## The best practice to utilize Redis is through Docker
## Redis is also like a Server which by default runs on PORT 6379
## Redis runs on command line, To visualize Redis in a GUI we need Redis Stack
## In Redis-Stack we have Redis and a Tool to visualize our Redis instance
## We will pull the image specified as redis/redis-stack, not the redis/redis-stack-server, as that image is for Production use
## If we take a look at the docker command to pull and run redis stack image from Docker Hub, we will see that we are exposing two PORTs 6379 for Redis and 8001 for the GUI

## Normal database such as MongoDB are cheaper to incorporate and stores data in Hard Disk, but they are slow
## Hence we do not use it as a Primary Database, plus if the server restarts our entire data will be wiped out