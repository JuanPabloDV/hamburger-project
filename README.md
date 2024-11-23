# Projeto Vue 3 - Sistema de Pedidos de Hamburguer

Este projeto foi criado com o intuito de aprimorar habilidades e conhecimentos de consumo de APIs e criação de sites em geral, utilizando o **Vue 3** como framework principal.

## Funcionalidades

- Criação de pedidos de hamburguer
- Edição de status de pedidos
- Exclusão de pedidos
- Exibição de pedidos

## Tecnologias Utilizadas

- **Vue 3** - Framework para construção da interface
- **JSON Server** - Simula uma API REST para persistência de dados
- **Yarn** - Gerenciador de pacotes

## Como Rodar o Projeto Localmente

### 1. Faça o clone do repositório:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
```

### 2. Instale as dependências:

Se você ainda não tem o **Yarn** instalado, você pode instalar o Yarn com o seguinte comando:

```bash
npm install --global yarn
```

Agora, instale as dependências do projeto:

```bash
yarn install
```

### 3. Inicie o servidor Vue:

Para rodar o projeto localmente, inicie o servidor Vue com o seguinte comando:

```bash
yarn dev
```

Isso iniciará o servidor Vue e você poderá acessar o front-end do projeto através de `http://localhost:3000`.

### 4. Inicie o servidor backend (JSON Server):

O backend utiliza o **JSON Server** para simular uma API. Para iniciar o servidor backend, use o comando:

```bash
yarn run backend
```

Isso irá iniciar o servidor backend em `http://localhost:4000` e você poderá interagir com a API simulada.

### 5. Acessando a aplicação

Após rodar ambos os servidores (Vue e JSON Server), acesse o front-end no navegador através de `http://localhost:3000` e a API em `http://localhost:4000`.

### Observações

- O consumo da API funciona apenas localmente, já que o **JSON Server** está configurado para rodar de forma local.
- As funcionalidades permitem que você crie pedidos, edite o status, exclua pedidos e visualize os pedidos já realizados.

