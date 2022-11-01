# Bootcamp_Jornada_Devops_com_AWS_Impulso

# Bootcamp oferecido pela Dio



Introdução ao Sistema Operacional Linux

- shutdown 0 - Desliga a máquina imediatamente
- Salvar estado da máquina o linux iniciará mais rápido depois pois o estado anterior.
- ip a - Mostra as informações de rede da máquina
- inet - Se refere ao ip local da máquina

Para acessar remoto de uma máquina windows para linux:
Será necessário instalar no windows o app (Putty)
E pegar o ip dá máquina linux
- sudo apt-get install openssh-server - Serviço Necessário para realizar acesso remoto
- para se conectar ao servidor aws devemos ir no terminal linux e digitar: ss -i Ubuntu-AWS.pem ubuntu@34.207.109.48 *de acordo como foi criado o servidor no AWS EC2

- sudo chmod 600 Ubuntu-AWS.pem ubuntu@34.207.109.48 - Dando as permissões necessárias para acesso ao servidor via ubuntu
- Excluir uma instância na AWS sempre que não desejar usar para não ter combranças.
- pwd mostra onde eu estou no sistema de arquivos
-/ diretório raiz

