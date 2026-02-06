# aventurine.works

Statyczny serwis tekstowy dla aventurine.works (multi-lang) oparty o Jekyll. Obecnie zawiera wersje EN.

## Uruchomienie lokalne

1) Zainstaluj bundler:

```bash
gem install bundler
```

2) Zainstaluj zaleznosci:

```bash
bundle install
```

3) Uruchom lokalnie:

```bash
bundle exec jekyll serve
```

## TDD workflow

Jedna komenda jakosci:

```bash
./scripts/quality.sh
```

## Hooki lokalne

Repo dostarcza hooki w `.githooks/`. Aby je wlaczyc:

```bash
git config core.hooksPath .githooks
```

## GitHub Pages

Workflow w `.github/workflows/pages.yml` buduje i publikuje strone po przejsciu testow jakosci.

## Domeny

- `awenturyn.org` (PL-only, osobne repo)
- `aventurine.works` (multi-lang)
