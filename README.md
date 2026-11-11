# 🏠 Casa em Dia 2050

Sistema web simples para organizar os equipamentos de uma residência e acompanhar suas manutenções.

> **Projeto acadêmico.** Este repositório contém a documentação de uma demonstração construída na plataforma [Bubble]([https://bubble.io](https://bubble.io/page?id=expotechss2026)), com apenas as funcionalidades essenciais.

---

## 📌 Sobre o projeto

O **Casa em Dia 2050** mostra como a tecnologia pode ajudar nos cuidados com uma casa. O usuário cria uma conta, entra no sistema e registra as manutenções dos equipamentos da sua residência, visualizando tudo em uma única tela.

## 🎯 Objetivo

Desenvolver um sistema simples que permita ao usuário organizar os equipamentos de sua casa e acompanhar as manutenções realizadas ou previstas.

## ❓ Problema

Muitas pessoas esquecem quando foi feita (ou quando deve ser feita) a manutenção de equipamentos como ar-condicionado, geladeira, caixa d'água ou aquecedor. Essas informações costumam ficar espalhadas em papéis, mensagens ou na memória, o que leva a esquecimentos, gastos inesperados e equipamentos com defeito.

## 💡 Solução proposta

Uma aplicação web com três telas (login, cadastro e manutenções), em que o usuário concentra os registros de manutenção da sua casa, com equipamento, tipo de manutenção, data e observação.

## ✅ Funcionalidades

- Criar conta
- Fazer login
- Cadastrar manutenções de equipamentos
- Visualizar as manutenções cadastradas em uma lista

## 🖥️ Telas

| Tela | Conteúdo |
|---|---|
| **Login** | E-mail, senha, botão *Entrar* e link *Criar conta* |
| **Cadastro** | Nome, e-mail, senha, confirmar senha, botão *Cadastrar* e link *Voltar para login* |
| **Manutenções** | Título, lista de manutenções e formulário com botão *Salvar manutenção* |

## 🛠️ Tecnologias

- **Bubble (Bubble Editor):** páginas, banco de dados e workflows
- **Banco de dados nativo do Bubble:** usuários e manutenções
- **Markdown e GitHub:** documentação

## ⚙️ Como o sistema funciona

1. O usuário cria uma conta na tela de **Cadastro**.
2. Entra pela tela de **Login**.
3. Na tela de **Manutenções**, preenche o formulário e clica em **Salvar manutenção**.
4. A manutenção é gravada no banco de dados e aparece na lista.

## 🗄️ Dados armazenados

| Tipo | Campos |
|---|---|
| **User** (nativo do Bubble) | nome, e-mail, senha |
| **Manutencao** | equipamento, tipo, data, observacao, usuario |

## 🧪 Como testar

1. Abra o app no Bubble e clique em **Preview**.
2. Crie uma conta na tela de Cadastro.
3. Salve uma manutenção na tela principal.
4. Confirme que ela aparece na lista.

**Link do app:** `https://bubble.io/page?id=expotechss2026
## 📁 Estrutura do repositório

```
casa-em-dia-2050/
├── README.md
└── docs/
    ├── objetivo.md
    ├── funcionalidades.md
    ├── tecnologias.md
    └── funcionamento.md
```

## ⚠️ Limitações

Demonstração acadêmica com escopo reduzido. Não há edição ou exclusão de registros, notificações, relatórios nem integrações externas.

## 👥 Integrantes

- Eduarda
- Artur
- Gabriel
- Rafael
- João Gabriel

**Instituição:** UNIFECAF Taboão da Serra
