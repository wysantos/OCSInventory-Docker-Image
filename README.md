# OCSInventory-Docker-Image
OCS Inventory NG - Based in "OCSInventory Official Docker Image"

# Utilização

## Clonando o projeto:
```
~/docker$ git clone https://github.com/wysantos/OCSInventory-Docker-Image.git
```

## Iniciando o Container da Aplicação:
```
~/docker$ cd OCSInventory-Docker-Image/
~/docker$ docker-compose up -d
```

## Acessando a instalação do OCS Inventory pela primeira vez:
```
http://<IP_do_servidor_docker ou localhost>/ocsreports/
```

## Clique em enviar para manter a configuração padrão:

<img src="https://github.com/wysantos/OCSInventory-Docker-Image/blob/master/.img/setup1.png">

 * Após alguns minutos se não houver um refresh automático da tela, clique em reload e confirme o reenvio do formulário.
 
<img src="https://github.com/wysantos/OCSInventory-Docker-Image/blob/master/.img/setup2.png">

 * caso receba uma solicitação para atualização da base de dados, confirme o update.
 
<img src="https://github.com/wysantos/OCSInventory-Docker-Image/blob/master/.img/setup3.png">

 * Quando a atualização estiver pronta, clique para entrar no OCS-NG.
 
<img src="https://github.com/wysantos/OCSInventory-Docker-Image/blob/master/.img/setup4.png">

 * Preencha com o usuário "admin" e senha "admin" para avessa a interface inicial do OCS Inventory.
 
<img src="https://github.com/wysantos/OCSInventory-Docker-Image/blob/master/.img/setup5.png">

 * Agora é só explorar a interface e realizar suas personalizações.
 
<img src="https://github.com/wysantos/OCSInventory-Docker-Image/blob/master/.img/setup6.png">
