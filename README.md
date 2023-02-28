# Instalação do Grafana 9.3.6 via Docker

1- Iniciar o Ubuntu 20.04.  
No terminal do Linux, executar o comando **`sudo dockerd`** para inicializar o Docker.

![image](https://user-images.githubusercontent.com/126198206/221887102-33b079ca-817a-4f35-a2a0-de79ec6f73da.png)

2- Abra um novo terminal do Linux para executar os comandos abaixo.

![image](https://user-images.githubusercontent.com/126198206/221887213-3fe15a97-a4db-4e85-a68e-36e5bcfd8c92.png)

3- Baixar, criar container e executar o Grafana.  
**`sudo docker run -d -p 3000:3000 -v grafana:/var/lib/grafana --name grafana grafana/grafana:9.3.6`**

4- Iniciar o container do Grafana.  
**`sudo docker start grafana`**

Obs.: Sempre ao inicializar o Docker, precisa iniciar o container do grafana.  
**`sudo docker start grafana`**
