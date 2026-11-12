# Vitor Oliveira | Portfólio Pessoal

Portfólio de **Vitor Oliveira**, estudante de Análise e Desenvolvimento de Sistemas (ADS) na UDF - Universidade do Distrito Federal. O site apresenta minha formação, stack tecnológica e projetos, e foi construído em um único arquivo HTML, sem etapa de build.

**Site:** https://vitorkng.github.io

---

## Sobre o projeto

Este repositório contém o código-fonte do meu portfólio. O objetivo foi criar uma página rápida, responsiva e fácil de manter, com visual inspirado em portfólios modernos de engenharia de software.

## Funcionalidades

- Tema escuro por padrão, com opção de tema claro na navbar (a escolha fica salva no navegador)
- Navbar fixa com efeito *glassmorphism* e navegação suave entre seções
- Hero com um terminal animado que mostra uma `struct` em C sobre mim
- Seções de Sobre, Habilidades, Projetos em destaque, Formação e Contato
- Cards de projeto com descrição, tags de tecnologia e link direto para o repositório
- Botão para copiar o e-mail com feedback visual
- Animações de entrada ao rolar a página (*scroll reveal*)
- Layout responsivo para celular, tablet e desktop
- Respeita a preferência de movimento reduzido do sistema
- HTML semântico, com atributos de acessibilidade e foco visível no teclado

## Tecnologias

| Categoria | Ferramentas |
|---|---|
| Estrutura e estilo | HTML5, [Tailwind CSS](https://tailwindcss.com/) (via CDN), CSS customizado |
| Interatividade | JavaScript puro (sem frameworks) |
| Tipografia | Space Grotesk e JetBrains Mono (Google Fonts) |
| Hospedagem | GitHub Pages |

## Estrutura

```
.
├── index.html   # Site completo: HTML, CSS e JavaScript
└── README.md    # Este arquivo
```

## Como rodar localmente

Não é necessário instalar nada.

```bash
# 1. Clone o repositório
git clone https://github.com/VitorKng/VitorKng.github.io.git

# 2. Entre na pasta
cd VitorKng.github.io

# 3. Abra o index.html no navegador
```

Para rodar com um servidor local, use qualquer um destes comandos:

```bash
python -m http.server 8000
# ou
npx serve
```

Depois acesse `http://localhost:8000`.

## Como personalizar

Todo o conteúdo está em `index.html`, separado por seções com comentários.

| O que alterar | Onde procurar |
|---|---|
| Textos de apresentação | Seções `HERO` e `SOBRE` |
| Habilidades | Itens `<li class="chip">` em cada card de `HABILIDADES` |
| Projetos | Blocos `<article>` em `PROJETOS` (título, descrição, tags e `href`) |
| Formação | Seção `FORMAÇÃO` |
| E-mail | Atributo `data-email` do botão `copyEmail` |
| LinkedIn e GitHub | Links na seção `CONTATO` |
| Cores | Objeto `colors` no `tailwind.config` e bloco "Tema claro" no CSS |

Para adicionar um projeto, copie um bloco `<article>` inteiro da seção Projetos e edite o conteúdo.

## Projetos em destaque

| Projeto | Descrição | Tecnologias |
|---|---|---|
| [VitorKng](https://github.com/VitorKng/VitorKng) | Repositório de perfil do GitHub | GitHub, Markdown |
| [Modelagem de Banco de Dados (SGBD)](https://github.com/VitorKng/Modelagem_de_Banco_de_Dados_SGBD) | Modelagem relacional, DDL, DML e DQL | MySQL, SQL, BRmodelo |
| [Algoritmos e Pensamento Computacional](https://github.com/VitorKng/Algoritimos_e_Pensamento_Computacional) | Algoritmos, vetores, matrizes e lógica | C, GCC |
| [Desenvolvimento Front-End para Web](https://github.com/VitorKng/Desenvolvimento_Front-End_Web) | Estudos de HTML e CSS | HTML, CSS |
| [Engenharia de Prompt: Fundamentos](https://github.com/VitorKng/engenharia-de-prompt-fundamentos) | Técnicas de prompting para LLMs | Engenharia de Prompt |

## Deploy

O site é publicado com o GitHub Pages, direto da branch `main`.

1. Crie um repositório público chamado `VitorKng.github.io`.
2. Envie o `index.html` para a raiz do repositório.
3. Em **Settings > Pages**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`.
4. Aguarde alguns minutos. O site fica disponível em `https://vitorkng.github.io`.

## Contato

- GitHub: [github.com/VitorKng](https://github.com/VitorKng)
- LinkedIn: [linkedin.com/in/vitor-oliveira-alvess-2318303b5](https://www.linkedin.com/in/vitor-oliveira-alvess-2318303b5)
- E-mail: vitoroliveiraalves06@gmail.com

---

Feito por **Vitor Oliveira**.
