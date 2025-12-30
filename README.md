COMANDOS DOCKER

docker search [nome imagem] - procura as imagens com o nome listado
docker pull [nome da imagem]: [versão] - puxa a imagem para a máquina
docker image ls - lista as imagens buildadas
docker rmi [id_da_imagem] - remove a imagem da máquina
docker container ps - lista os containers
docker ps -a - lista os containers que foram utilizados
docker container rm [id_do_container] - remove o hitórico do container executado
docker run -it [nome imagem ou id da imagem] - executa a imagem de forma iterativa caso seja um sistema operacional
docker run -it --name [nome do container]  [nome imagem ou id da imagem] - executa e dá um nome para a execução
docker run -p (porta do servidor):(porta do docker) [nome da imagem] - executa uma imagem definindo uma porta de host
