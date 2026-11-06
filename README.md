# Minha Vida Profissional

Prompts e guias para usar IA na busca de emprego e no desenvolvimento profissional.

**Acesse o site:** https://trozobador.github.io/minha-vida-profissional/

## Como contribuir / editar

- O site é feito com [Jekyll](https://jekyllrb.com/) e o tema [Just the Docs](https://just-the-docs.com/).
- Edite na branch `develop`. O site é publicado automaticamente quando há merge na `main`.
- Cada página é um arquivo `.md` com um cabeçalho (`title`, `parent`, `nav_order`).
- Coloque os prompts dentro de um bloco ` ```text ` seguido de `{: .prompt }` para ganhar o botão de copiar e a quebra de linha automática.

### Rodar localmente (opcional)

```bash
docker run --rm -it -p 4000:4000 -v "$PWD:/srv/jekyll" -w /srv/jekyll ruby:3.3 \
  bash -c "bundle install && bundle exec jekyll serve --host 0.0.0.0"
```

Depois abra http://localhost:4000/minha-vida-profissional/
