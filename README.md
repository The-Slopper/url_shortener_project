# rust-urlshortener

Encurtador de URLs em Rust (std). Armazena mapeamentos, valida tokens de admin e
serve arquivos estáticos de QR codes.

## Rodando

```bash
cargo run
```

## Módulos

- `auth` — validação de token de administrador
- `store` — montagem de queries e estatísticas
- `files` — leitura de QR codes gerados
