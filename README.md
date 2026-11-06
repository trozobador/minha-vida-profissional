# Minha Vida Profissional

Prompts prontos e guias simples para usar inteligência artificial (IA) a seu favor: na **busca de emprego** e no **desenvolvimento das suas habilidades**. Tudo gratuito e sem precisar saber programar.

**👉 Acesse o site: https://trozobador.github.io/minha-vida-profissional/**

## Como usar

1. **Escolha um prompt** no site. Cada página explica para que ele serve e o que você precisa ter em mãos.
2. **Copie o prompt** com o botão de copiar.
3. **Cole numa IA** (ChatGPT, Claude ou Gemini), complete o que estiver entre colchetes `[ASSIM]` e envie.

## O que tem aqui

- **Primeiros passos com IA**: qual IA usar, como colar um prompt e anexar arquivos, e os cuidados que você deve ter.
- **Procurar emprego**: análise de currículo × vaga e automação da busca de vagas com um agente de IA.
- **Desenvolver habilidades**: como usar a IA para aprender com autonomia (em breve).

## Por que este projeto existe

Em maio de 2026, aos 49 anos, fui desligado num layoff e passei quase seis meses desempregado. O que me tirou do fundo do poço foi pedir ajuda, passar a aparecer nas redes, usar a IA como parceira e continuar aprendendo. No fim de outubro fui contratado para trabalhar com IA.

Este projeto reúne o que funcionou para mim, de um jeito que **qualquer pessoa** consegue usar. A história completa está na [página inicial do site](https://trozobador.github.io/minha-vida-profissional/#por-que-este-site-existe).

## Autor

**Ricardo Martins**: [GitHub](https://github.com/trozobador) · [LinkedIn](https://www.linkedin.com/in/costaricardomartins/) · [X](https://x.com/ricardoparallax) · [Instagram](https://www.instagram.com/trozobador/)

---

## Para quem quer editar o site

- Feito com [Jekyll](https://jekyllrb.com/) e o tema [Just the Docs](https://just-the-docs.com/).
- Edite na branch `develop`. O site é publicado automaticamente quando há merge na `main`.
- Cada página é um arquivo `.md` com um cabeçalho (`title`, `parent`, `nav_order`).
- Coloque os prompts dentro de um bloco ` ```text ` seguido de `{: .prompt }` para ganhar o botão de copiar e a quebra de linha automática.

Para rodar localmente (opcional, com Docker):

```bash
docker run --rm -it -p 4000:4000 -v "$PWD:/srv/jekyll" -w /srv/jekyll ruby:3.3 \
  bash -c "bundle install && bundle exec jekyll serve --host 0.0.0.0"
```

Depois abra http://localhost:4000/minha-vida-profissional/
