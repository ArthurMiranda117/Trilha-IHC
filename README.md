# Trilha IHC — Fundamentos de Interação Humano-Computador

Site estático desenvolvido como trabalho acadêmico sobre Interação Humano-Computador (IHC), abordando cinco temas centrais da área em páginas navegáveis por abas.

Feito apenas com **HTML e CSS puros**, sem uso de JavaScript ou frameworks.

## Site publicado

O site está disponível ao vivo via GitHub Pages:

**https://arthurmiranda117.github.io/Trilha-IHC/**

## Temas abordados

1. **IHC** — conceito da área, principais termos (usabilidade, UX, UI, acessibilidade, feedback) e seus objetivos.
2. **Design Thinking** — as cinco fases do processo (empatia, definição, ideação, prototipação e teste), ferramentas e características da abordagem.
3. **Heurísticas de Nielsen** — as dez heurísticas de usabilidade propostas por Jakob Nielsen, com exemplos.
4. **WCAG / Paletas de Cores** — princípios de acessibilidade (POUR), níveis de conformidade, regras de contraste mínimo e exemplos visuais de paleta acessível e de contraste adequado/inadequado.
5. **UX/UI** — diferença entre experiência e interface, apresentada em colunas comparativas, e as etapas do processo de desenvolvimento de um produto digital.

## Estrutura do projeto

```
.
├── index.html            # redireciona para atividade1.html (página inicial do GitHub Pages)
├── atividade1.html       # IHC
├── atividade2.html       # Heurísticas de Nielsen
├── atividade3.html       # Design Thinking
├── atividade4.html       # WCAG / Paletas de Cores
├── atividade5.html       # UX/UI
├── estilo.css            # folha de estilo única, compartilhada por todas as páginas
└── README.md
```

## Padrão visual

Todas as páginas seguem o mesmo modelo:

- Barra de navegação fixa no topo, com uma aba para cada tema (a aba da página atual fica destacada).
- Título centralizado e parágrafo de introdução ao tema.
- Seções organizadas por subtítulos em destaque, com conteúdo apresentado em listas no formato de cartão.
- Bloco de **Relatório** ao final de cada página, com uma reflexão sobre o conteúdo estudado, acessível também por um link direto na navegação (`#relatorio`).

A estilização fica centralizada em `estilo.css`, o que garante consistência visual entre todas as páginas e facilita a manutenção do código.

## Como visualizar localmente

Não é necessário nenhum servidor ou instalação. Basta clonar o repositório e abrir qualquer um dos arquivos `.html` diretamente no navegador — a navegação entre as páginas funciona por links relativos.

```bash
git clone https://github.com/ArthurMiranda117/Trilha-IHC.git
cd Trilha-IHC
# abra index.html (ou atividade1.html) no navegador
```

## Publicação (GitHub Pages)

O site é publicado automaticamente a cada `push` na branch `master`, via **Settings > Pages**, com a origem configurada como `Deploy from a branch` → `master` / `(root)`. O histórico de builds pode ser acompanhado na aba **Actions** do repositório.

## Tecnologias

- HTML5
- CSS3
