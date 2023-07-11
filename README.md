# Implantação de API web usando Ansible, Dockerfile e Docker Compose

## Introdução

Neste projeto, há a criação de uma máquina virtual Vagrant que será provisionada pelo Ansible, que por sua vez irá criar um serviço do Docker Compose que realiza o build de uma imagem personalizada do Nginx e cria um container a partir desta imagem, que servirá a API web do site [VIACEP](https://viacep.com.br/exemplo/jquery/).

## Como usar este projeto

Para criar a VM:

`vagrant up`

Para acessar a API web, digite na barra de pesquisa de um navegador:

`192.168.56.2:8080`

Para destruir a VM:

`vagrant destroy -f`
