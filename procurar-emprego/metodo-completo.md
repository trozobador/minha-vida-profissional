---
title: Método completo (meu-emprego-novo)
parent: Procurar emprego
nav_order: 3
---

# Método completo: meu-emprego-novo
{: .no_toc }

## O que é

O **[meu-emprego-novo][repo]** é o repositório onde eu documentei, em detalhes, o método que usei para me recolocar no mercado com ajuda de IA. Ele é aberto e gratuito, e reúne duas coisas:

- **O método:** um passo a passo em 10 etapas, do seu perfil profissional até a retrospectiva do que funcionou. Cada etapa tem um capítulo explicativo e um prompt pronto. **Funciona com qualquer IA** e serve para qualquer área profissional.
- **A ferramenta:** um programa com agentes de IA que gera um currículo sob medida, em PDF, para cada vaga. Esta parte é para quem sabe programar.

[Abrir o repositório no GitHub][repo]{: .btn .btn-primary }

{: .dica }
Este site é a porta de entrada, com prompts prontos para copiar e colar. O repositório é o aprofundamento: quando você quiser organizar a busca inteira como um processo, é lá que está o caminho completo.

## O método em 4 fases

| Fase | O que acontece | Quando |
|:--|:--|:--|
| **Preparar** | Você escreve a história real da sua carreira e ajusta o LinkedIn. | Uma vez |
| **Encontrar** | Você busca vagas e separa as que valem a pena. | Em rodadas |
| **Candidatar** | Para cada vaga escolhida: currículo sob medida, revisão e preparação para a entrevista. | A cada vaga |
| **Aprender** | Você olha o que gerou resposta e ajusta o processo. | A cada prazo que você definir |

## As três ideias centrais

1. **Uma única fonte de verdade.** Você escreve uma vez a versão longa e honesta da sua carreira, o **perfil-mestre**. Todo currículo e toda resposta de entrevista saem dele.
2. **A IA propõe, você decide.** A IA pode reorganizar, resumir e traduzir. Não pode inventar. Nada sai com o seu nome sem você ler.
3. **Registrar para aprender.** Uma planilha simples mostra quais currículos e quais fontes de vagas geram resposta.

## Qual caminho seguir

O repositório oferece duas trilhas. As duas seguem o mesmo método; muda só quem produz o currículo.

### Trilha A: com o seu assistente de IA (para todo mundo)

Você usa os prompts do repositório em qualquer IA, como ChatGPT, Claude ou Gemini. **Não precisa baixar nada:**

1. Na [tabela de etapas](#as-10-etapas) abaixo, clique no link do **prompt** da etapa em que você está.
2. O GitHub vai abrir o arquivo. Passe o mouse sobre o quadro do prompt e clique no **botão de copiar**, no canto superior direito.
3. Cole na sua IA e siga as instruções do prompt.

Leia também o **capítulo** de cada etapa: ele explica o objetivo, os erros comuns e quando a etapa está concluída.

{: .atencao }
A etapa 4 (currículo sob medida) do repositório gera o currículo em LaTeX, um formato técnico. Se você não quiser lidar com isso, use a IA para te ajudar a ajustar o currículo no Word ou no Google Docs, seguindo as mesmas regras do capítulo.

### Trilha B: com a ferramenta de agentes (para quem programa)

Um programa em Python roda cinco agentes de IA que leem a vaga e o seu perfil, escrevem o currículo, avaliam, revisam e geram o PDF e um guia de preparação para entrevista. Exige Python e uma chave de API de um provedor de IA, e cada execução tem custo de uso da API.

O passo a passo de instalação está no [README do repositório][trilha-b].

## As 10 etapas

| # | Etapa | Capítulo | Prompt |
|:--|:--|:--|:--|
| 0 | Princípios: as regras para o seu assistente | [ler][d00] | |
| 1 | Perfil-mestre: a história real da sua carreira | [ler][d01] | [copiar][p01] |
| 2 | Busca de vagas | [ler][d02] | [copiar][p02] |
| 3 | Triagem: separar as vagas por aderência | [ler][d03] | [copiar][p03] |
| 4 | Currículo sob medida para cada vaga | [ler][d04] | [criar][p04] · [ajustar][p04b] |
| 5 | Revisão de cobertura: conferir o currículo contra a vaga | [ler][d05] | [copiar][p05] |
| 6 | Preparação para a entrevista | [ler][d06] | [copiar][p06] |
| 7 | Candidatura e acompanhamento | [ler][d07] | [copiar][p07] |
| 8 | Golpes e segurança | [ler][d08] | |
| 9 | LinkedIn | [ler][d09] | [copiar][p09] |
| 10 | Resultados e lições: a retrospectiva | [ler][d10] | [copiar][p10] |

Quer ver o método funcionando do começo ao fim? O repositório acompanha a [busca completa da Ana Souza][exemplo], uma pessoa fictícia, com todos os arquivos que ela produziu em cada etapa.

## Antes da primeira candidatura: golpes

{: .importante }
Quem está procurando emprego é alvo de golpes de recrutamento. **Nunca** baixe e rode um programa ou repositório que a "empresa" mandar durante uma entrevista, **nunca** envie documentos de identidade numa candidatura e **nunca** pague por "kit", curso ou taxa para ser contratado. O [guia de golpes e segurança][d08] tem o checklist completo.

## Dúvidas e sugestões

O repositório aceita perguntas, sugestões e relatos de uso nas [issues do GitHub][issues]. Se o método te ajudou, conte lá: isso ajuda outras pessoas a encontrarem o material.

[repo]: https://github.com/R238Company/meu-emprego-novo
[issues]: https://github.com/R238Company/meu-emprego-novo/issues
[trilha-b]: https://github.com/R238Company/meu-emprego-novo#5-trilha-b-automatizar-o-currículo-com-a-cli
[exemplo]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/exemplo/README.md
[d00]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/docs/00-principios.md
[d01]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/docs/01-profile-truth.md
[d02]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/docs/02-busca-de-vagas.md
[d03]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/docs/03-triagem.md
[d04]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/docs/04-curriculo-sob-medida.md
[d05]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/docs/05-coverage-review.md
[d06]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/docs/06-interview-prep.md
[d07]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/docs/07-rastreamento.md
[d08]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/docs/08-golpes-e-seguranca.md
[d09]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/docs/09-linkedin.md
[d10]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/docs/10-resultados-e-licoes.md
[p01]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/prompts/01-perfil-mestre.md
[p02]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/prompts/02-busca-vagas.md
[p03]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/prompts/03-triagem.md
[p04]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/prompts/04-curriculo-sob-medida.md
[p04b]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/prompts/04b-ajustar-curriculo.md
[p05]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/prompts/05-coverage-review.md
[p06]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/prompts/06-interview-prep.md
[p07]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/prompts/07-resumo-tracker.md
[p09]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/prompts/09-linkedin.md
[p10]: https://github.com/R238Company/meu-emprego-novo/blob/main/meu-emprego-novo-pipeline/prompts/10-retrospectiva.md
