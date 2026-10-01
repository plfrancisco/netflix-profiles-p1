# Netflix Profiles Clone

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![status](https://img.shields.io/badge/status-concluído-success)

Clone estático da tela de seleção de perfis e da página inicial da Netflix,
desenvolvido como atividade avaliativa (P1) da disciplina de Frontend. Não
possui qualquer vínculo com a Netflix, Inc.; imagens de filmes e avatares
são placeholders fictícios usados apenas para compor o layout.

## Sumário

- [Visão geral](#visão-geral)
- [Estrutura do projeto](#estrutura-do-projeto)
- [Como executar](#como-executar)
- [Stack técnica](#stack-técnica)
- [Autores](#autores)

## Visão geral

O projeto reproduz, de forma estática, as principais telas da interface da
Netflix:

- Seleção de perfis ("Quem está assistindo?")
- Gerenciamento de perfis (modo de edição, apenas visual)
- Página inicial com banner em destaque e fileiras de catálogo

Construído deliberadamente sem JavaScript, como exercício de fundamentos de
HTML e CSS (semântica, flexbox e efeitos de hover/transição).

## Estrutura do projeto

```
netflix-profiles-p1/
├── assets/
│   ├── posters/        # Pôsteres fictícios usados no catálogo
│   ├── banner.png       # Banner em destaque da home
│   ├── netflix-logo.svg
│   └── perfilX.png      # Avatares dos perfis
├── index.html           # Tela "Quem está assistindo?"
├── editar.html          # Tela de gerenciamento de perfis
├── navegar.html         # Página inicial / catálogo
└── style.css            # Estilos globais
```

## Como executar

Não há dependências ou processo de build.

```bash
git clone https://github.com/plfrancisco/netflix-profiles-p1.git
cd netflix-profiles-p1
```

Abra `index.html` no navegador (duplo clique, ou extensão **Live Server**
do VS Code).

## Stack técnica

HTML5 · CSS3

## Autores

**Pedro Lucas Francisco**
**Nathália Rodrigues Moraes**
