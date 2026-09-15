# Jogo Mario

## Descrição

Projeto **Mario Jump**, um jogo Front-End simples inspirado no universo do Mario. O jogador controla o personagem e deve pular os obstáculos sem colidir com os tubos. O projeto foi organizado para a atividade de Git e GitHub, mantendo todo o código executável dentro de `frontend/`.

## Objetivo

Praticar desenvolvimento Front-End e, principalmente, organização de projeto, versionamento com Git, uso das branches `dev` e `main`, commits e integração do desenvolvimento.

## Tecnologias

- HTML5
- CSS3
- JavaScript
- Node.js / npm
- Vite
- Git e GitHub

## Estrutura do projeto

```text
jogoMario/
├── backend/
├── docs/
│   ├── branding/
│   ├── mer/
│   ├── mockups/
│   ├── models/
│   │   └── uml/
│   └── requirements/
├── frontend/
│   ├── images/
│   ├── media/
│   ├── index.html
│   ├── package.json
│   ├── script.js
│   └── style.css
├── .gitignore
├── LICENSE
└── README.md
```

Os diretórios ainda sem conteúdo possuem `.gitkeep` para que sejam versionados pelo Git.

## Instalação

É necessário ter o Node.js instalado. No terminal, entre na pasta do Front-End e instale as dependências:

```bash
cd frontend
npm install
```

## Execução

Ainda dentro de `frontend/`, execute:

```bash
npm run dev
```

O Vite exibirá no terminal o endereço local para abrir o jogo no navegador.

## Como jogar

Pressione uma tecla do teclado para fazer o Mario pular. Evite colidir com o tubo. A música começa após a primeira interação com o jogo.

## Integrantes

> Preencha esta tabela com os dados reais de todos os integrantes antes da entrega.

| Nome | Matrícula | Papel |
|---|---|---|
| PREENCHER | PREENCHER | Scrum Master |
| PREENCHER | PREENCHER | Desenvolvedor |
| PREENCHER | PREENCHER | Documentador |
| PREENCHER | PREENCHER | Testador |

## Fluxo de branches

O desenvolvimento deve ocorrer primeiro na branch `dev`. Depois dos commits e da validação, a `dev` deve ser integrada à `main` por merge ou Pull Request. O histórico incluído neste projeto demonstra esse fluxo localmente; ao publicar no GitHub, envie as duas branches.

Exemplo:

```bash
git push -u origin main
git push -u origin dev
```

## Licença

Este projeto utiliza a licença MIT. Consulte o arquivo `LICENSE` na raiz.
