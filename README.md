### Resumo do que foi feito no projeto até agora (API SEM BANCO DE DADOS):

![capa](https://github.com/user-attachments/assets/f90e2ab1-bd65-48bb-9cd1-e89546a0515d)

Próximos passos: Banco de Dados, Interfaces de usuário, Design, consumo da API pelo React, Configuração e Deploy.

Este projeto proporcionou a experiência de desenvolver um sistema básico de gerenciamento de tarefas usando Go com Fiber, explorando conceitos fundamentais como rotas HTTP, manipulação de dados estruturados, e integração de ferramentas de desenvolvimento como o Postman para testes de API.

1. **Configuração do Ambiente**:
    - Configuração inicial do ambiente de desenvolvimento com Go e Fiber.
    - Instalação e configuração do Air para hot reloading.
2. **Definição da Estrutura de Dados**:
    - Criação da estrutura `Todo` para representar tarefas com campos como `ID`, `Completed`, e `Body`.
3. **Endpoints HTTP com Fiber**:
    - Implementação de endpoints HTTP utilizando o framework Fiber.
    - Criação dos endpoints para:
        - Criar um novo Todo (`POST /api/todos`).
        - Listar todos os Todos (`GET /api/todos`).
        - Obter um Todo específico (`GET /api/todos/:id`).
        - Atualizar um Todo existente (`PATCH /api/todos/:id`).
        - Excluir um Todo (`DELETE /api/todos/:id`).
4. **Manipulação de Dados**:
    - Utilização de estruturas de dados em memória para armazenar os Todos.
    - Implementação das operações CRUD (Create, Read, Update, Delete) para manipular os Todos.
5. **Teste e Integração**:
    - Testes dos endpoints usando o Postman para verificar o funcionamento correto das operações CRUD.
    - Resolução de problemas comuns como erros de conexão e configuração do ambiente.
