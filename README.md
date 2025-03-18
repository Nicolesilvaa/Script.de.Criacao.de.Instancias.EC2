# Script de Criação de Instâncias EC2 🚀
> Script não autoral. Esse script foi encontrado em um laboratório da trilha AWS Re/Start. 
  
## Objetivo principal: 🎯

- O script automatiza todo o processo de criação de uma instância EC2, desde a configuração de rede até a instalação do servidor LAMP.

- Verifica a existência de recursos conflitantes (instâncias e grupos de segurança) e permite ao usuário decidir se deseja excluí-los.

- Cria um grupo de segurança com as portas 22 (SSH) e 80 (HTTP) abertas para acesso público.

- Usa um script de user-data para configurar automaticamente o servidor LAMP durante a inicialização da instância.

## Curiosidade - O que é o LAMP ? ❓

> LAMP é um acrônimo que representa uma pilha de tecnologias  utilizada para desenvolver e hospedar aplicações web.

L → Linux

A → Apache

M → MySQL/MariaDB

P → PHP/Perl/Python

## Como o LAMP Funciona:

- O Linux fornece o sistema operacional para executar os outros componentes.

- O Apache recebe requisições de clientes (navegadores) e serve as páginas web.

- O MySQL/MariaDB armazena e gerencia os dados da aplicação.

- O PHP (ou outra linguagem) processa a lógica do servidor, interage com o banco de dados e gera conteúdo dinâmico para o Apache servir.

 ## **Autora:** Nicole Silva 💁🏿‍♀️
