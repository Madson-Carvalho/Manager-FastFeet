# FastFeet - Controle de Encomendas

## Unidade Curricular: Desenvolvimento de Sistemas para Web (DSWE)
**Professor:** Bruno Bandeira Fernandes

## Projeto Final (React.js e API Node.js)
### AV3 - Peso: 30%
### Data de Entrega: 26/06

## Equipe
De 3 a 4 integrantes

## Objetivo
Desenvolver o front-end utilizando React.js e uma API REST com Node.js para o controle de encomendas da transportadora fictícia FastFeet.

## Requisitos do Projeto
- **Front-end:** React.js
- **Back-end:** Node.js
- **Entrega:**
  - Código-fonte com link do GitHub (única pasta contendo web e api).
  - Testes Unitários do Back-end.
  - Deploy do Front-end e Back-end.
  - Apresentação da metodologia de desenvolvimento, artefatos criados e resultados.
- **Apresentação:**
  - Tempo: 20 minutos
  - Avaliação: 
    - 70% código-fonte
    - 30% apresentação
  - Critérios:
    - Entrega até as 18:59h do dia 26/06 na plataforma AVA, com código do GitHub.
    - Requisitos funcionais sem erros.
    - Qualidade nos slides e na apresentação.

## Descrição do Desafio
Este desafio requer conhecimentos adicionais além dos abordados em aula, demandando pesquisa e autonomia para resolver problemas. A atividade envolve o desenvolvimento de uma API em Node.js e um front-end em React.js para gerenciar encomendas.

## Regras da Aplicação
- **Tipos de Usuário:**
  - Entregador
  - Admin
- **Funcionalidades:**
  - Login com CPF e Senha
  - CRUD de Entregadores, Encomendas e Destinatários
  - Marcar encomendas como aguardando, retiradas, entregues ou devolvidas
  - Listar encomendas próximas ao local do entregador
  - Alterar senha de usuário
  - Listar entregas de um usuário
  - Notificar destinatário a cada alteração no status da encomenda

## Regras de Negócio
- Apenas admins podem realizar operações de CRUD em encomendas, entregadores e destinatários.
- Para marcar uma encomenda como entregue, é obrigatório o envio de uma foto.
- Somente o entregador que retirou a encomenda pode marcá-la como entregue.
- Apenas o admin pode alterar a senha de um usuário.
- Entregadores não podem listar encomendas de outros entregadores.

## Conceitos Importantes
- Testes unitários e e2e
- Deploy da API (back-end) online
- Implementação parcial do front-end (mínimo 50% dos requisitos)
- Deploy do front-end
- Integração com serviços externos (se possível)

## Estrutura do Repositório
├── api/ # Código-fonte do Back-end (Node.js)
├── web/ # Código-fonte do Front-end (React.js)
└── README.md # Documentação do Projeto


## Como Rodar o Projeto

### Pré-requisitos
- Node.js
- NPM ou Yarn
- Git

### Instalação
1. Clone o repositório:
    ```sh
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```

2. Instale as dependências do back-end e do front-end:
    ```sh
    cd api
    npm install
    # ou
    yarn install
    
    cd ../web
    npm install
    # ou
    yarn install
    ```

### Executando a API (Back-end)
```sh
cd api
npm start
# ou
yarn start
```

### Executando o Front-end
```sh
cd web
npm start
# ou
yarn start
```

### Link de acesso
https://fastfeet-807q.onrender.com/
