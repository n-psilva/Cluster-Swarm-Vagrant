# Cluster-Swarm-Vagrant

## O projeto cria um cluster swarm com dois nós, sendo um deles o principal.

Após a criação de uma pasta para receber os arquivos acima, digitar no terminal os seguintes comandos para subir o cluster e conferir os nós:

obs.: deverá estar na pasta onde se encontra o arquivo Vagrantfile

>\lab-vagrand> vagrant up

-acessar nó master

>vagrant ssh master

-confere os nós

>docker node ls

obs.: o comando deve ser realizado com usuario root

