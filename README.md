# Lista de Tarefas 06: Spring Boot + Vue.js + CORS

Projeto da atividade "Lista de Tarefas 06", focado na integração de um backend Spring Boot e um frontend Vue.js, com ênfase na correção de problemas de **CORS (Cross-Origin Resource Sharing)**.

---

## 1. Análise do Problema (CORS)

Ao executar o projeto base, foi identificado um erro que impedia o frontend (em `http://localhost:8081`) de consumir os dados da API backend (em `http://localhost:8080`).

A inspeção do console do navegador revelou um erro de política de CORS.

## 2. Correção Aplicada

Para solucionar o problema, foi necessário configurar o backend para aceitar explicitamente as requisições vindas do frontend.
