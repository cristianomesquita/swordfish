# [SW API NodeJS]
SW Challenge API

Para configurar está api em abiente de produção é necessário configurar um servidor web
ou usar algum serviço de terceiros como o heroku por exemplo. Para maiores detalhes sobre
como fazer deploy no ambiente heroku acesse o [Dev center do heroku, deploy com nodejs](https://devcenter.heroku.com/articles/getting-started-with-nodejs#set-up)

Está api está disponível em um droplet na [Digital Ocean](https://www.digitalocean.com)
Para colocar um servidor online na Digital Ocean é necessário criar uma conta e alugar um droplet.

## Configurações de servidor 

A api está rodando em um droplet com as seguinte configurações 512 MB de memória ram / 20 GB de armazenamento SSD / Sistema operacional - CentOS 7.4 x64.


## Primeiros passos

Após contratar o servidor primeiro passo é instalar o sistema operacionar neste caso o
CentOS 7.4, assim que terminar a instalação a digital ocean enviará para o email cadastrado o IP do droplet e os dados de acesso via SSH.

### Acessando via SSH

Agora de posse dos dados de acesso abra o terminal e digite ssh root@<IP> pressione enter, 
agora insira a senha que foi enviada para seu email e logo após cadastre sua senha definitiva.

### Instalações de ambiente

#### NodeJS

    Pronto agora as intalações de ambiente, primeiro instale o nvm (node version manager), rode este comando no seu terminal conectado via SSH: 
    curl https://raw.githubusercontent.com/creationix/nvm/v0.23.2/install.sh | bash 
    Feito isso você deve reiniciar seu terminal. Para instalar o versão especifica do nodejs neste caso a 8.4.0 execute o comando nvm install 8.4.0.

#### MongoDB
