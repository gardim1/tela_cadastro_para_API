# Projeto de Frontend para Tela de Cadastro

Este projeto foi desenvolvido como parte da implementação de uma API para uma tela de cadastro, utilizando **React** com **Vite**. O frontend foi criado apenas para interagir com a API desenvolvida em **Node.js** e **MongoDB** (disponível em outro repositório).

## Tecnologias Utilizadas

- **React** - Biblioteca JavaScript para construir a interface de usuário
- **Vite** - Ferramenta de construção rápida e leve para desenvolvimento
- **Axios** - Cliente HTTP para fazer as requisições à API
- **Node.js** (para a API) - O backend pode ser encontrado em outro repositório

## Como Utilizar

1. Clone este repositório (Frontend):
    ```bash
   git clone <URL-deste-repositorio-do-frontend>
    ```

2. Clone o repositório do Backend (Node.js + MongoDB):
   O backend foi desenvolvido separadamente. Para obter a API que lida com as funcionalidades de cadastro, clone o repositório correspondente:
   ```bash
   git clone <URL-do-repositorio-do-backend>
   ```

3. Instalar dependências (Frontend):
   - Dentro da pasta do projeto frontend clonado, instale as dependências:
     ```bash
     `npm install`
     ```

4. Configuração das conexões:
   - Certifique-se de que o frontend está configurado corretamente para fazer requisições HTTP para a API. O backend deve estar rodando em uma porta específica (ex.: `http://localhost:3000`).
   - Verifique no código fonte do frontend (geralmente no arquivo de configuração ou nos serviços) se a URL da API está apontando corretamente para o endereço em que o backend está rodando.

5. Rodar o projeto (Frontend):
   - Para iniciar o frontend:
     ```bash
     npm run dev
     ```
   - Isso irá rodar o projeto localmente, normalmente na porta `http://localhost:5173` (ou outra definida pelo Vite).

## Funcionalidades

- **Adicionar Cadastro**: O frontend permite que o usuário preencha um formulário de cadastro e envie os dados para a API.
- **Editar Cadastro**: O usuário pode editar informações de um cadastro existente (essa funcionalidade requer que o backend esteja rodando e aceitando edições).
- **Excluir Cadastro**: O usuário pode excluir um cadastro existente, com uma chamada à API.

## Estrutura do Projeto
```bash
.
├── src/
│   ├── components/      # Componentes React reutilizáveis
│   ├── services/        # Arquivos para fazer as chamadas à API (ex.: Axios)
│   ├── pages/           # Páginas da aplicação
│   ├── App.jsx          # Componente principal
│   └── main.jsx         # Arquivo principal de inicialização do React
├── public/              # Arquivos estáticos (HTML, favicon, etc.)
├── vite.config.js       # Configurações do Vite
├── package.json         # Dependências do projeto
└── README.md            # Instruções e informações do projeto
```

## Observações

Este frontend foi desenvolvido para ser utilizado em conjunto com a API implementada em **Node.js** e **MongoDB**. Certifique-se de que a API está rodando corretamente para que o frontend consiga consumir os dados e interagir com as funcionalidades de cadastro.
