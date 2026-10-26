<p align="center">
<img src="assets/capa.png" alt="GPT customizado" width="100%">
</p>

<h1 align="center">GPT Customizado</h1>
<p align="center"><i>Assistente de escrita criado como GPT especializado no bootcamp da DIO</i></p>

<p align="center">
<img src="https://img.shields.io/badge/ChatGPT-10A37F?style=flat-square&logo=openai&logoColor=white" alt="ChatGPT">
<img src="https://img.shields.io/badge/Prompt%20engineering-D97757?style=flat-square" alt="Prompt engineering">
<img src="https://img.shields.io/badge/DIO-E4105D?style=flat-square" alt="DIO">
<img src="https://img.shields.io/badge/tipo-estudo-64748B?style=flat-square" alt="tipo: estudo">
</p>

## Sumário

- [Sobre](#sobre)
- [O que foi praticado](#o-que-foi-praticado)
- [Como visualizar](#como-visualizar)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Autor](#autor)

## Sobre

Case prático do **bootcamp da DIO**: criar e configurar um **GPT customizado** no ChatGPT, com instruções próprias, base de conhecimento e tom de comunicação definidos, para atuar como **assistente de escrita**.

## O que foi praticado

| Pasta | Conceito |
| --- | --- |
| `Base_Bruta/` | Exemplos de conteúdo de entrada, antes do tratamento |
| `Base_Tratada/` | Conteúdo organizado para servir de conhecimento ao GPT |
| `Scripts/` | Instruções do que o GPT deve fazer |

```mermaid
flowchart LR
    A[Base bruta] --> B[Tratamento] --> C[Base tratada]
    D[Instruções] --> E[GPT customizado]
    C --> E --> F[Assistente de escrita]
```

## Como visualizar

Os arquivos documentam a configuração do GPT. Para reproduzir, crie um GPT no ChatGPT (*Explore GPTs → Create*), use as instruções de `Scripts/` e envie os arquivos de `Base_Tratada/` como conhecimento.

## Estrutura do repositório

```text
Projeto-GPT-DIO/
├── Base_Bruta/
├── Base_Tratada/
├── Scripts/
└── assets/capa.png
```

## Autor

**Saulo Prado** · Analista de Sistemas · Gestão de Ativos de TI, orçamento, automação e dashboards

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Saulo%20Prado-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saulo-prado-ab4a0b96/)
[![GitHub](https://img.shields.io/badge/GitHub-sauloprado-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sauloprado)
