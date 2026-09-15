# Setup

Place the files like this in `aditya-13115/aditya-13115`:

```text
README.md
.github/
└── workflows/
    ├── snake.yml
    └── stats.yml
```

The stats workflow creates these generated files automatically:

```text
profile/
├── stats-dark.svg
├── stats-light.svg
├── top-langs-dark.svg
└── top-langs-light.svg
```

The README already references those local files, so it no longer depends on
`github-readme-stats.vercel.app` for the stats and language cards.

The workflow runs hourly and can also be started manually from GitHub Actions.
