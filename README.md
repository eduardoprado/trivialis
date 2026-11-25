# Trivialis

Site para criar e jogar quiz e trivia em grupo, no estilo trivia de bar.

A versão atual é só front-end: não há back-end nem banco de dados, e tudo roda e fica salvo localmente no navegador.

## Stack

- [Vite](https://vite.dev/) + [React](https://react.dev/) + TypeScript
- [oxlint](https://oxc.rs/docs/guide/usage/linter) para lint

## Rodando localmente

Requer Node 22 ou superior.

```bash
npm install
npm run dev
```

## Scripts

| Comando           | O que faz                                      |
| ----------------- | ---------------------------------------------- |
| `npm run dev`     | Sobe o servidor de desenvolvimento             |
| `npm run build`   | Checa os tipos e gera o build em `dist/`       |
| `npm run preview` | Serve o build de `dist/` localmente            |
| `npm run lint`    | Roda o oxlint                                  |
