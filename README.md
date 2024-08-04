# DESAFIO QA BEEDOO

## Visão Geral

Este repositório contém a solução para o Desafio QA Beedoo, focado na criação de user stories, casos de teste, e evidências de teste para o módulo de curso disponível [aqui](https://creative-sherbet-a51eac.netlify.app/).

## Decisões tomadas para Criar as User Stories
Após análise do Módulo de Cursos foram observados pontos em relação a:

1. **Identificação dos Usuários**: Temos um ator: Administrador
2. **Definição do Objetivo**: Gerenciar cursos na plataforma
3. **Critérios de Aceitação**: 
   - Critério 1: Cadastrar cursos para visualizar na lista de cursos.
   - Critério 2: Excluir cursos da lista de cursos.
   - Critério 3: Campos da tela de cadastro: 

| Campo                         | Tipo                       | limite de caracteres | Obrigatório |
| -------------                 | :-------------:            | :--:                 | :---: |
| **Nome**                      | alfanumericos e especiais  |  150                 | Sim   |
| **Descrição do curso**        | alfanumericos e especiais  |  500                 | Não   |
| **Instrutor**                 | alfanumericos e especiais  |  80                  | Sim   |
| **URL da imagem**             | alfanumericos e especiais  |   -                  | Não   |
|**Data Inicio:** não pode ser antes que a data atual.|      |                      | Sim   |
|**Data Final:** não pode ser antes que a data de inicio.|   |                      | Sim   |
|**N° de vagas:** não pode ser negativo.|   numérico         |                      | Sim   |
|**Tipo de curso:** seleção obrigatória.|  selecionável      |                      | Sim   |

## User Story
As user stories foram tomadas conforme testado manualmente as páginas e estão anexadas na aba 'User story' da planilha anexada.

## Casos de Teste
Os cenários e casos de testes e evidencias estão documentados em uma planilha disponbilizada [👉 **AQUI** 👈](https://docs.google.com/spreadsheets/d/1RczV-ojQQMy180BrqHgRCXOvKTd7ojl6vkaM2XsibBE/edit?usp=sharing).
