Deploy flask and redis application using docker stack
and apply this command for deploy application

$ git clone https://github.com/Abhay956/my-project-1.git

$ cd my-project-1/

$ docker swarm init --advertise-addr=(ip address)

$ docker stack deploy --compose-file docker-stack.yml my-project-1

$ docker stack ps my-project-1
