##REQUESITOS 

-UBUNTU 20.04 (OBRIGATORIO)
-VM COM MINIMO: 2CPU 4GB RAM
-VM COM RECOMENDADO: 4CPU 6GB RAM


## CRIAR SUBDOMINIO E APONTAR PARA O IP DA SUA VPS ##

FRONTEND_URL: app.seudominio.com

BACKEND_URL:  api.seudominio.com

## CHECAR PROPAGAÇÃO DO DOMÍNIO ##

https://dnschecker.org/

## COPIAR A PASTA PARA ROOT E RODAR OS COMANDOS ABAIXO ##
git clone https://github.com/grimvik90/whaticket-power.git
sudo chmod +x ./whaticket-power/whaticketsaas

cd ./whaticket-power

sudo ./whaticketsaas

===================================================

login: admin@admin.com
senha: 123456
