# scoop-boso

Scoop bucket for [Boso AI](https://boso.com).

## Install

```powershell
scoop bucket add boso https://github.com/e01061978-sketch/scoop-boso
scoop install boso
```

## Run

```powershell
boso
```

Requires Python 3.12+ (Scoop will pull it in via the `python` dependency).
Set API key via `BOSO_API_KEY` env var or a `config.toml` in
`%APPDATA%\boso\`.
