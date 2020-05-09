# docker

"docker ps" for active process 
"docker ps -a" for all processes
"docker stop"
"docker rmi" delete image
"docker run" pull image and run
"docker rm"  delete docker
"docker -it" for interactive (input) and terminal
"docker -d" for detached/background mode
"docker -e" call specific environment parameter -- find by docker inspect under "env" 
"docker -p 8080:5000" map port 8080 to 5000 (internal docker port)
"docker inspect" find parameter
"docker -v /opt/datadir:/var/lib/mysql" for persistent storage
