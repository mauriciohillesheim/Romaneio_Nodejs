# Sistema de Romaneio Digital

## Descrição

Este projeto é um **sistema de romaneio digital** que tem como objetivo gerenciar o envio e o recebimento de materiais. Ele foi desenvolvido para otimizar o controle logístico, garantindo maior precisão, agilidade e confiabilidade no processo de gestão de materiais. O sistema permite o cadastro de clientes e materiais, além de fornecer uma interface para visualização e confirmação do recebimento de materiais.

O sistema é desenvolvido com **Node.js** no backend, **MySQL** para gerenciamento do banco de dados e **HTML/CSS/JavaScript** no frontend, tornando-o uma aplicação web responsiva, simples de usar e de fácil manutenção.

## Funcionalidades

- **Cadastro de clientes**: Inserção de informações como nome, CNPJ, projeto, local, volumes e endereço de entrega.
- **Listagem de clientes**: Visualização da lista completa de clientes com seus respectivos dados.
- **Edição e exclusão de clientes**: Possibilidade de editar e remover clientes cadastrados.
- **Conferência de materiais**: Ferramenta para conferir e confirmar o recebimento de materiais no local de entrega.
- **Relatórios de envio e recebimento**: Emissão de relatórios para controle de materiais enviados e recebidos.

## Tecnologias Utilizadas

- **Backend**: Node.js (Express)
- **Banco de Dados**: MySQL
- **Frontend**: HTML, CSS, JavaScript
- **Bibliotecas**: body-parser, mysql2, dotenv, cors

## Requisitos

- **Node.js** (versão 14 ou superior)
- **MySQL** (versão 8 ou superior)
- **Navegador compatível com HTML5**

## Configuração do Projeto

1. Clone este repositório.
2. Instale as dependências utilizando o comando `npm install`.
3. Crie um banco de dados MySQL e configure as variáveis de ambiente no arquivo `.env`:
   ```bash
   DB_HOST=localhost
   DB_USER=root
   DB_PASS=sua_senha
   DB_NAME=romaneio_db
   ```
4. Execute o servidor com o comando `node src/app.js`.
5. Acesse a aplicação em `http://localhost:3000`.

## Estrutura do Projeto

```bash
romaneio-app/
├── public/              # Arquivos estáticos (HTML, CSS, JS)
├── src/                 # Arquivos do servidor e lógica do backend
│   ├── config/          # Configuração do banco de dados
│   ├── controllers/     # Controladores da aplicação
│   ├── models/          # Modelos e comunicação com o banco de dados
│   ├── routes/          # Rotas da API
│   └── app.js           # Arquivo principal do servidor
├── .env                 # Variáveis de ambiente
├── package.json         # Gerenciamento de dependências
└── README.md            # Documentação do projeto
```

## Como Usar

1. **Cadastrar Cliente**: Acesse a página de cadastro de clientes e preencha os dados necessários.
2. **Listar Clientes**: Visualize os clientes cadastrados através da página de listagem.
3. **Conferir Materiais**: Confirme o recebimento de materiais por meio da interface de verificação.
4. **Gerenciar Clientes**: Use as opções de edição e exclusão para manter os dados de clientes atualizados.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias e correções.

--- 

Essa descrição oferece uma visão clara do sistema, suas funcionalidades, e como configurá-lo.
