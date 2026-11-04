# AGENTS.md

- Site estático em um arquivo só (`index.html`), publicado no GitHub Pages a partir da branch `main`, pasta raiz.
- Público: alunos em Chromebook. Animações só com `transform`/`opacity`; respeitar `prefers-reduced-motion`.
- Não remover o bloqueio de copiar/colar da caixa de resposta (`paste`, `drop`, `copy`, `cut`, `beforeinput insertFrom*` e a checagem de salto de texto no `input`).
- Perguntas em `FASES`, títulos de nível em `NIVEIS` (sempre `FASES.length + 1` itens), mínimo de caracteres em `MIN`.
- Testar localmente: `npx serve .` ou o `node` em `.claude/launch.json`, e passar pelas 8 fases.
