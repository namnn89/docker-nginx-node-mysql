################## Docker for nginx node mysql ###################
Step 1: install source code 
        cd source code/src
	    npm install 
Step 2: Stop all docker
	docker stop $(docker ps -aq)
	docker rm $(docker ps -aq)
	docker rmi $(docker images -q)

Step 3: docker-compose up -d --build

