# 🧪 Automação E2E com Cypress - SauceDemo

Este repositório contém o projeto de automação de testes End-to-End (E2E) desenvolvido com **Cypress**, cobrindo os principais fluxos do e-commerce [SauceDemo](https://www.saucedemo.com/).

O projeto utiliza o padrão de arquitetura **Page Object Model (POM)** para garantir a reusabilidade de código, organização dos seletores e fácil manutenção dos testes.

---

## 📌 Funcionalidades Testadas

* **Login:** Autenticação na aplicação.
* **Produtos:** 
  * Validação da listagem de itens.
  * Adição de produtos ao carrinho.
  * Ordenação de produtos por preço e nome.
  * Navegação para o carrinho de compras.

---

## 🏗️ Estrutura do Projeto (Page Object Model)

```text
cypress/
├── e2e/
│   └── chekout.cy.js       # Suíte de testes de adição de produtos no carrinho de compras
│   └── login.cy.js         # Suíte de testes de login 
│   └── products.cy.js      # Suíte de testes de produtos
├── pages/
│   └── CartPage.js         # Mapeamento de elementos e métodos da página de carrinho
│   └── CheckoutPage.js     # Mapeamento de elementos e métodos da página de chekout
│   └── LoginPage.js        # Mapeamento de elementos e métodos da página de login
│   └── ProductsPage.js     # Mapeamento de elementos e métodos da página de produtos
├── support/
│   ├── commands.js         # Comandos customizados do Cypress
│   └── e2e.js              # Configurações globais de suporte
└── cypress.config.js       # Configurações do Cypress
```

## 🛠️ Tecnologias Utilizadas
 *Node.js
 *Cypress
 *JavaScript

#🚀 Como Executar o Projeto
Pré-requisitos
Antes de começar, você precisará ter o Node.js e o Git instalados na sua máquina.

##Passos para execução
*1 Clone este repositório:

git clone [https://github.com/Vladimir-Macedo/cypress-saucedemo-automation.git](https://github.com/Vladimir-Macedo/cypress-saucedemo-automation.git)

*2 Acesse a pasta do projeto:

Bash
cd cypress-saucedemo-automation

*3 Instale as dependências do projeto:

Bash
npm install

*4 Execute os testes:

 *Interface Gráfica (Interactive Mode):

Bash
npx cypress open

 *Modo Headless (Terminal):

Bash
npx cypress run

#✒️ Autor
Desenvolvido por Vladimir Macedo 👋

Sinta-se à vontade para entrar em contato ou conectar no LinkedIn!
