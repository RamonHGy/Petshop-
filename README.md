# Petshop

Sistema de Agendamento PetShop
🐕 Web Service RESTful desenvolvido em Jakarta EE para sistema de agendamento de banho em petshop. Projeto acadêmico da faculdade com foco em tecnologias enterprise.
🛠️ Tecnologias Utilizadas

Java 8

Jakarta EE - Framework enterprise

GlassFish Server - Servidor de aplicação

Apache Derby - Sistema de gerenciamento de banco de dados

JAX-RS - API REST para web services

JDBC - Conectividade com banco de dados

JSON - Formato de troca de dados

⚡ Funcionalidades

🐾 Agendamento de banho para pets

🐕 Cadastro de pets e proprietários

📡 API RESTful completa (GET, POST, PUT, DELETE)

🔐 Conexão segura com banco de dados

📊 Inserção de dados via endpoints REST

🗄️ Persistência em banco Derby

🏗️ Arquitetura enterprise com Jakarta EE

🚀 Como executar
Pré-requisitos

Java 8+

GlassFish Server 5.1+

Apache Derby

NetBeans IDE (recomendado)

Configuração

Clone o repositório

Copie config.properties.example para config.properties

Configure suas credenciais do banco no arquivo config.properties

Deploy no GlassFish Server

Acesse os endpoints REST

📡 Endpoints da API

GET    /api/agendamentos     - Listar todos os agendamentos

POST   /api/agendamentos     - Criar novo agendamento

PUT    /api/agendamentos/{id} - Atualizar agendamento

DELETE /api/agendamentos/{id} - Cancelar agendamento

GET    /api/pets            - Listar pets cadastrados  

POST   /api/pets            - Cadastrar novo pet

🔒 Segurança

Credenciais do banco configuradas externamente
Arquivo config.properties não versionado
Conexão JDBC segura

🏗️ Arquitetura
Cliente/App → REST API → Jakarta EE → JDBC → Derby Database

                ↓
        Sistema de Agendamento PetShop
🎓 Contexto Acadêmico
Projeto desenvolvido para a disciplina Programação de sistemas da faculdade, focando em:

Desenvolvimento de aplicações enterprise
Implementação de web services RESTful
Integração com banco de dados
Simulação de sistema real de petshop

📈 Evolução do Projeto
Este projeto está em constante aprimoramento. À medida que avanço nos meus estudos e conhecimentos em desenvolvimento backend e arquitetura de sistemas, novas funcionalidades, melhorias de segurança, usabilidade e organização do código serão implementadas.

📌 Melhorias futuras planejadas:

Integração com autenticação de usuários (login e autenticação JWT)

Validação de dados mais robusta

Interface frontend para consumo da API (ex: React ou Angular)

Utilização de testes automatizados (JUnit, REST-assured)

Migração para banco de dados relacional mais robusto (ex: PostgreSQL)


Projeto acadêmico - Sistema de Agendamento para PetShop
