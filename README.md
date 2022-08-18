# Laboratório para estudos

### **Pré-requisitos:**

- VirtualBox v5.4+
- Vagrant
- Recursos de 3G de memória RAM

### **Conteúdo**

Neste repositório você encontrará um ambiente para estudos com docker, todo esse ambiente será utilizado na live sobre Monitoramento de Aplicações com ferramentas opensource.

O arquivo Vagrantfile subirá duas instâncias com configurações distintas para o teste em prática de comunicação e monitoramento.

O processo será feito todo automatizado através da ferramenta ansible nas duas instâncias instantalando os seguintes pacotes:

- apt-transport-https
- ca-certificates
- curl
- gnupg-agent
- software-properties-common
- default-mysql-client
- nfs-common
- snapd
- git
- vim
- docker-ce
- docker-ce-cli
- containerd.io
- docker-compose-plugin
- docker-compose

### Instalação

Para realizar a instalação deste ambiente siga estes passos:

1. Precisamos clonar o repositório para nossa máquina
```
$ git clone https://github.com/4linux/Continuos-Monitoring.git
```
2. Agora acessaremos e vamos inicializar os ambientes:

```
$ cd Continuos-Monitoring
$ vagrant up
```

Aguarde a finalização do processo e após a conclusão poderemos acessar qualquer instância com o comando abaixo:

```
$ vagrant ssh lab1
```
**Ou**
```
$ vagrant ssh lab2
```

### **Ótimos estudos!!**