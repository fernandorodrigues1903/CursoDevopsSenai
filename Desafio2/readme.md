##Para baixar o container

-> docker pull fernandoantunesfju/desafio2

##Para rodar o container

-> docker run -d -p 8087:9090 -e APP_NAME=<app_name> -e APP_COLOR=<app_color> fernandoantunesfju/desafio2

###Variáves de espera da aplicação

-> <app_name> --> Nome para aparecer na tela

-> <app_color> --> Cor no fundo (blue, green, yellow, etc...)
