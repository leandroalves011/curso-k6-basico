# Introdução aos testes de performance com k6

Exemplo de projeto do curso básico de testes de perfomance com K6 da `QAcademy`

> Abaixo estão as especificações da API de teste criada pela `QAcademy`, utilizada para a realização dos testes de perfomance para validar os requisitos abaixo.

# User API

## 🔖 Requisitos funcionais

### Cadastro

- [x] Deve retornar os id ao cadastrar um novo usuário
- [x] Deve retornar 201 ao cadastrar um novo usuário
- [x] Deve retornar 400 ao tentar cadastrar sem email e senha
- [x] Deve retornar 400 se o email for duplicado

| campos   | descrição                   | tipo  | obrigatório |
| :------- | :-------------------------- | :---- | :---------- |
| email    | usuário identificador único | email | sim         |
| password | senha do usuário            | texto | sim         |

## 🔖 Requisitos não funcionais

### Cadastro

- [ ] O cadastro com sucesso deve ocorrer em até 2 segundos
- [ ] Cadastros sem sucesso devem ocorrer em até 2 segundos
- [ ] Deve poder cadastrar até 100 usuários simultâneos
- [ ] A margem de erro no cadastro deve ser de pelo menos 1%

## 🚀 Tecnologias

- [Node.js] - plataforma de desenvolvimento
- [Express] - framework onde a API foi construída
- [MongoDB] - Banco de dados (Não relacional)
- [k6] - ferramenta para teste de carga, performance, stress etc...

## 👨🏻‍💻 Como executar o projeto

[Node.js](https://nodejs.org/) v16 ou superior para executar.

Para liberar o gerenciador de pacotes Yarn:

```
corepack enable
```

Execute os comandos abaixo para instalar das dependências do projeto:

```sh
cd curso-k6-basico/api
yarn install
yarn dev
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Sintam-se livres para me contatar a respeito de dúvidas, sugestões ou qualquer tipo de melhoria sobre o projeto 💚

@leandroalves011
