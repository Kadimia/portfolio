# Victor Alves — Portfólio

Site pessoal com apresentação, experiência profissional, objetivos, projetos e currículos (PT/EN).
HTML, CSS e JavaScript puros, sem build e sem dependências.

## Rodar localmente
Abra `index.html` no navegador. Para a lista de projetos carregar de `projects.json`, sirva a pasta:

```bash
python -m http.server 8000   # depois acesse http://localhost:8000
```

## Atalhos
`Ctrl/⌘ + K` ou `/` abre a paleta de comandos · `1`–`6` pulam de seção.

## Como adicionar um projeto
Edite `projects.json` e inclua um item:

```json
{
  "id": "p-meu-projeto",
  "title": "Nome do projeto",
  "desc": "Descrição curta.",
  "status": "done",
  "tech": ["React", "Node.js"],
  "link": "https://github.com/usuario/repositorio",
  "createdAt": 5
}
```

- `status`: `done` (concluído), `doing` (em andamento) ou `planned` (planejado)
- `createdAt`: número maior aparece primeiro
- Faça commit e push: o site se atualiza sozinho.

## Publicar no GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
