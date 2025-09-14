
# *Entre códigos e circuitos*

# Comandos .cmd 🎯


# Atividade: README.md + Comandos CMD para Hardware

## 📝 O que é um README.md?
É um arquivo muito comum em projetos de software e programação, serve para apresentar e explicar um projeto.

## 💻 Comandos CMD voltados para hardware
1. **Comando:** `wmic cpu get name`  
   **Função:** Exibe o nome e modelo do processador instalado no sistema..  
   **Uso:** Para saber qual CPU está no computador.
   **Exemplo de saída:** Name
Intel(R) Core(TM) i7-9750H CPU @ 2.60GHz


2. ## 💻 Comandos CMD voltados para hardware
 **Comando:** `wmic diskdrive get model,serialnumber`  
 **Função:** Exibe modelo e número serial dos discos rígidos conectados.  
 **Uso:** Identificar discos físicos instalados.
 **Exemplo de saída:** Model               SerialNumber
Samsung SSD 860 EVO  S3Z9NB0K123456X


 
 3. ## 💻 Comandos CMD voltados para hardware
 **Comando:** `wmic memorychip get capacity,speed`  
 **Função:**  Mostra a capacidade (em bytes) e velocidade da memória RAM instalada. 
 **Uso:** Conferir quantidade e velocidade de cada módulo de RAM.
 

  4. ## 💻 Comandos CMD voltados para hardware
 **Comando:** Ver espaço em disco (total e livre) `wmic logicaldisk get name, size, freespace`  
 **Função:** Mostra o espaço total e disponível em cada partição (em bytes).  
 **Uso:** Digite o comando no CMD.

Converta os valores para GB, dividindo por 1.073.741.824.
 

  5. ## 💻 Comandos CMD voltados para hardware
 **Comando:** Ver adaptadores de rede e MAC `wmic nic get name, macaddress`  
 **Função:** Exibe os adaptadores de rede instalados e seus respectivos endereços MAC.  
 **Uso:** Ideal para identificar interfaces físicas de rede.

Execute no CMD normalmente.
 

  6. ## 💻 Comandos CMD voltados para hardware
 **Comando:** Ver informações da placa de vídeo `wmic path win32_videocontroller get name, adapterram`  
 **Função:** Exibe o nome da placa de vídeo e quantidade de memória de vídeo.  
 **Uso:** Execute no CMD.

A memória será exibida em bytes.

## 👤 Autor
Gabriele Alvares Dias

## 📅 Data
14/09/2025

## 📧 Contato
gabrielealvaresdias@gmail.com

## 🧠 O que aprendi?
Alguns comandos(atalhos) que não sabia como usava.
