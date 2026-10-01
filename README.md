# API Testing with Postman

Este repositório contém exercícios e projetos de testes de API realizados durante meus estudos de Quality Assurance.

## Ferramentas utilizadas

- Postman
- REST API
- JSON
- JavaScript

## O que pratiquei

- Criação de requisições de API
- Testes de status code
- Validação de respostas
- Testes de tempo de resposta
- Uso de variáveis
- Organização de Collections
- Testes automatizados no Postman

## Projeto disponível

### Postman Basics

Collection criada durante meus estudos para praticar requisições e validações utilizando Postman.

Arquivo disponível neste repositório:

`Postman basics [Arthur Morgan].postman_collection.json`

## Objetivo



- Verificação das respostas da API
- Organização de requests em uma Collection do Postman   

---

## Projeto Conduit API — Testes com Postman

### Sobre o projeto

Projeto prático de testes de API realizado durante minha formação em QA Engineering na Mate Academy, utilizando a API da aplicação Conduit (RealWorld).

O objetivo da atividade foi praticar o envio de requisições HTTP, a validação das respostas e a organização de cenários de teste no Postman.

### Funcionalidades trabalhadas

A coleção contém requisições relacionadas a funcionalidades como:

* Cadastro e autenticação de usuários.
* Consulta de informações de usuários.
* Criação e consulta de artigos.
* Comentários.
* Tags.

### Verificações implementadas

Durante a atividade, trabalhei com:

* Métodos HTTP.
* Validação de status codes.
* Verificação de informações retornadas nas respostas JSON.
* Testes de tempo de resposta.
* Cenários positivos e negativos.
* Variáveis de coleção.
* Scripts de teste utilizando JavaScript no Postman.

### Coleção do projeto

[Visualizar a coleção Conduit API no GitHub](conduit-api-testing.postman_collection.json)

O arquivo JSON disponibilizado permite consultar a organização das requisições e os scripts de teste implementados.

**Observação:** a presença dos scripts na coleção não representa, por si só, um relatório de execução. Os resultados efetivos devem ser comprovados por registros de execução.

### Aprendizados

Esta atividade contribuiu para minha compreensão da comunicação entre cliente e servidor, dos métodos HTTP e da importância de validar tanto o código de status quanto o conteúdo retornado pela API.

**Documentação:** Renata Meirelles da Silva.

## Evidência de execução — Conduit API

Teste realizado no Postman para validar a autenticação de usuário.

**Resultado da execução:** 200 OK — 3 testes aprovados.

- Status code is 200 — PASSED
- Response contains user — PASSED
- Token is returned — PASSED

![Resultado dos testes de login no Postman](WhatsApp%20Image%202026-10-01%20at%2016.22.57.jpeg)

### Evidência de execução — Sign Up

Teste de cadastro de um novo usuário na API Conduit.

**Resultado:** 200 OK — 3 testes aprovados.

- Status code is 200 — PASSED
- Response contains user — PASSED
- Token is returned — PASSED

![Resultado dos testes de Sign Up no Postman](WhatsApp%20Image%202026-10-01%20at%2018.02.56.jpeg)



