# sagner-docs

Repositorio de documentos de Alejandro Sagner SpA, publicados en `docs.alejandrosagner.com`.

## Estructura

```
web/
  index.html          ← hub principal (lista de expedientes)
  assets/logos/       ← logos SVG del brand kit
  docs/               ← documentos HTML individuales
```

## Deploy

Netlify lee la carpeta `web/` como directorio de publicación (ver `netlify.toml`).
Cada `git push` a `main` dispara un deploy automático.

## Agregar documentos

1. Copiar los archivos HTML al folder correspondiente dentro de `web/docs/`
2. Agregar la card/fila en `web/index.html`
3. `git add . && git commit -m "docs: [descripción]" && git push`

## Historial de expedientes

| Carpeta | Descripción | Versión | Fecha |
|---|---|---|---|
| `docs/` | ISO 14001 — Respuesta ambiental para Electrans | v1a | 2026-06-01 |
