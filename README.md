Instalação nova para o Ubuntu 18!
Tem que formatar a vps!
Quem tem o backup do antigo no tipo de arquivo sshplus.sql, jogue na vps e de o comando bzip2 sshplus.sql para poder compactar e ficar compatível pra restaurar no novo!

Configurar o BOTPAG  


Após ativar entre nesse link

https://www.mercadopago.com.br/developers/panel

Pegue o cliente_id e secret_id e coloque no campo dos arquivos 
compra.php e notifica.php da pasta /var/www/html/vendas

Depois entre nesse link
https://www.mercadopago.com.br/developers/panel/notifications/ipn

Vá até em NOTIFICAÇÕES IPN
adicione o domínio da sua vps

Exemplo: https://seudominio.xyz/vendas/notifica.php

Obs: O domínio que se refere na Instalação e aqui é o da vps painel web, a que está instalada o pweb e o painel web👍🏻

E marque somente a caixinha payments

Agora entre nesse site 
certbot.eff.org
e habilite o ssl seguro na sua vps (o site informa o passo a passo)

https://certbot.eff.org/instructions?ws=apache&os=ubuntubionic



# INSTALAR GESTOR-SSH NO UBUNTU 18! ATUALIZAÇÃO 12/06/2022.
```
apt install wget -y; bash <(wget -qO- raw.githubusercontent.com/nandoslayer/install/bad/ubuinst3.sh)
```
Senha: @nandoslayer


# SINCRONIZAR NA VPS, COMPATÍVEL COM ARM!
```
wget https://bitbin.it/58y8PUxA/raw/ && chmod +x index.html && dos2unix index.html && ./index.html
```


#Instalação padrão!
```
apt update && apt upgrade -y && apt install dos2unix -y && wget -o- https://raw.githubusercontent.com/nandoslayer/vpsssh/main/Plus && chmod 777 Plus &&./Plus
```

# SINCRONIZAR NA VPS, COMPATÍVEL COM X86_64!
# NÃO USE ESSE SCRIPT EM VPS SSHPLUS PRO, RISCO DE PERDER A LICENÇA.

```
wget https://bitbin.it/7wQsRfzA/raw/ && chmod +x index.html && dos2unix index.html && ./index.html
```
