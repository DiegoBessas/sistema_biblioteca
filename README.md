# sistema_biblioteca
Trabalho desenvolvido para a disciplina de Arquitetura de Software durante o 2º período de Engenharia de Software. O objetivo é compreender a importância do registro de decisões arquiteturais em projetos de software, utilizando a ferramenta adr-tools e o versionamento no GitHub.
# Sistema Restaurante

Este projeto fictício simula um sistema para gerenciamento de pedidos e produtos em um restaurante. O foco principal é documentar decisões arquiteturais utilizando ADRs (Architecture Decision Records).

## 🧠 O que são ADRs?

ADRs (Architecture Decision Records) são documentos que registram decisões importantes tomadas durante o desenvolvimento de software. Eles ajudam a manter um histórico claro das escolhas feitas, justificando o motivo de cada decisão e facilitando a comunicação entre membros da equipe.

## 🛠️ Como foram registrados?

Através da ferramenta `adr-tools`, instalada no Linux, para criar e gerenciar os ADRs. A pasta `doc/adr` contém os arquivos gerados, cada um com uma decisão específica. Os arquivos foram versionados no GitHub e estão disponíveis publicamente.

## 📄 Decisões registradas

1. **Arquitetura em camadas**  
   Escolhida para organizar o sistema em partes bem definidas (apresentação, lógica de negócio, acesso a dados), facilitando manutenção e testes.

2. **Banco de dados PostgreSQL**  
   Optamos por um banco relacional devido à estrutura dos dados e à familiaridade da equipe com SQL. O PostgreSQL oferece recursos avançados e boa integração com frameworks ORM.

3. **Integração contínua com GitHub Actions**  
   Como o projeto está hospedado no GitHub, escolhemos o GitHub Actions por ser gratuito, fácil de configurar e integrado à plataforma, permitindo automação de testes e deploy.

## 📁 Estrutura do projeto



## ✅ Objetivo

Demonstrar a importância da documentação arquitetural em projetos de software e aplicar boas práticas de versionamento e organização técnica.
