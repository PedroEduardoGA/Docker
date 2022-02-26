# Docker
É uma ferramenta que possibilita a geração de containers para rodar aplicações, aplicações web entre outros, entregando um container com um sistema operacional e configurações próprias, também possui um conjunto de serviços online que possibilitam a instalação de ferramentas via "imagens" sem a necessidade de instalar a ferramente completa pelo procedimento padrão.

## Jenkins 
É um servidor de automação open source, com ele é possível criar uma pipeline(sequência de procedimentos) para os códigos e conseguir realizar testes, compilação com apenas um clique, ao gerar o container basta acessar a porta selecionada na geração do container (por padrão 8097) e seguir os procedimentos de configuração de usuário.
Antes de usar o comando _docker-compose up -d_ certifique-se de gerar a imagem dele utilizando dockerfile com o comando: _docker build . -t jenkins-docker_.

## RabbitMq
É um softwere que permite o envio e recebimento de mensagens via uso de filas com protocolos seguros, para gerar o container bastar usar o comando _docker-compose up -d_, ele baixara a imagem selecionada do dockerhub automaticamente e então depois de configurar seus parâmetros de usuário basta acessar o painel digitando _localhost:5672_ no navegador, é possivel fazer implementações de envio e recebimento de mensagens automático em diversas linguagens de programação.
