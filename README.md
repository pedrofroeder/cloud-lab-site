# Cloud Lab Site

Laboratório prático de estudos em Cloud e DevOps utilizando OpenStack.

## Objetivo

Criar uma infraestrutura básica em nuvem, publicar um serviço web em Linux e versionar o projeto com Git e GitHub.

## Ambiente

- OpenStack
- Ubuntu 24.04
- Nginx
- Git
- GitHub

## Arquitetura atual

Internet
↓
Floating IP
↓
Router
↓
Rede privada
↓
VM Ubuntu
↓
Nginx
↓
index.html

## O que foi feito

- Criação de rede e sub-rede no OpenStack
- Criação de Security Group
- Criação de Router
- Associação de Floating IP
- Acesso SSH com chave
- Instalação do Nginx
- Publicação de uma página HTML
- Versionamento com Git
- Publicação do repositório no GitHub

