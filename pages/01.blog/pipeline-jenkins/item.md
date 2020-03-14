---
title: Infra estrutura em código ? não diga bobagens, como assim ?
author: Glaucius Djalma Pereira Junior

hero_classes: text-light title-h1h2 overlay-dark-gradient hero-large parallax
hero_image: pipeline.jpg
show_sidebar: true

taxonomy:
    category: blog
    tag: [jenkins, pipeline, fluxo, devops]
---

Bom pessoal, eu decidi escrever um código dias atrás, para implementação de ambiente em cloud pública, no caso deste artigo, AWS, bom, não preciso dizer do que se trata a AWS, então, vamos la.

Para este setup e configuração, estou considerando o abaixo :

- Deploy de VPC não default
- Deploy de security groups, rotas, internet gateways e afins
- Deploy de subnets orientadas por tier, camada, ou pedaço do negócio, separadas por privadas e 
públicas
- Deploy de EC2 com user data para setup e deploy de aplicativos em tempo de start-up, melhor, por que voçe pode criar um template de deploy (lauch template) e criar suas máquinas sempre com um modelo, para auto scaling groups é obrigatório

No meu repositório no Github você pode obter os códigos, vai la !!!

git clone https://github.com/glaucius/aws-terraform.git

Até o próximo.


